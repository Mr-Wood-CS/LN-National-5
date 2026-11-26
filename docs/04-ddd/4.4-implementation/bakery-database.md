# Building a Two-Table Database

A directory lists bakeries and their products. It must store each bakery once, link every product to an existing bakery, and let users list products by town and price.

| Table | Fields |
| --- | --- |
| `Bakery` | `BakeryID` (primary key), `BakeryName`, `Town` |
| `Product` | `ProductID` (primary key), `ProductName`, `PricePence`, `BakeryID` (foreign key) |

This is a **one-to-many** relationship. A bakery can supply several products. Each product belongs to one bakery. Several products can share the same `BakeryID`, but each product must have its own `ProductID`.

## Implement the relationship in SQLite

```sql
PRAGMA foreign_keys = ON;

CREATE TABLE Bakery (
    BakeryID INTEGER PRIMARY KEY,
    BakeryName TEXT NOT NULL,
    Town TEXT NOT NULL
);

CREATE TABLE Product (
    ProductID INTEGER PRIMARY KEY,
    ProductName TEXT NOT NULL,
    PricePence INTEGER NOT NULL,
    BakeryID INTEGER NOT NULL REFERENCES Bakery(BakeryID)
);
```

`REFERENCES Bakery(BakeryID)` defines the foreign key. `NOT NULL` makes the link compulsory. In SQLite, enable foreign-key enforcement for the connection before running the examples. In a graphical database tool, the equivalent is to create the relationship between the two key fields and enable referential integrity.

## Populate the tables

Insert the bakery records first so the product records can refer to them. Prices are stored as whole pence, so £1.20 is stored as `120`.

```sql
INSERT INTO Bakery (BakeryID, BakeryName, Town)
VALUES (1, 'Clyde Bakery', 'Glasgow'),
       (2, 'Harbour Bakery', 'Greenock'),
       (3, 'Park Bakery', 'Glasgow');

INSERT INTO Product (ProductID, ProductName, PricePence, BakeryID)
VALUES (101, 'Morning roll', 80, 1),
       (102, 'Oat biscuit', 120, 1),
       (103, 'Empire biscuit', 120, 3),
       (104, 'Sourdough loaf', 350, 3),
       (105, 'Fruit scone', 100, 2);
```

## Check referential integrity

Run this example separately from the setup. It tries to link a new product to bakery `99`, which does not exist.

```sql
INSERT INTO Product (ProductID, ProductName, PricePence, BakeryID)
VALUES (106, 'Shortbread', 110, 99);
```

SQLite reports a foreign-key constraint failure, and no product is added. With these constraints, SQLite also rejects deleting a bakery while products still refer to it.

[Next lesson — SQL SELECT Operations](3.4.1-sql-select.md)

[See the implemented Bakery query](3.4.3-sql-equi-joins.md#filtering-and-sorting-joined-results)
