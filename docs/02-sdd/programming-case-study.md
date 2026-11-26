# The Bike Hire Shop

A bike hire shop charges **£6 per hour**. Customers can hire a bike for **1 to 4 whole hours**. The program asks for the number of hours. If a whole number is outside this range, it displays an error and asks again. Once the customer enters an accepted value, the program displays the total cost in pounds. Assume the customer enters whole numbers.

## 1. Analysis

The purpose is to calculate and display the cost of hiring one bike for a valid number of hours.

| Inputs | Processes | Outputs |
| --- | --- | --- |
| Number of hours entered by the customer | Check whether the hours are from 1 to 4 inclusive. Ask again while the value is outside that range. Multiply the accepted hours by 6. | An error message for each rejected value. The total cost in pounds once the hours are accepted. |

[Software Analysis](2.1-analysis/1.2-analysis.md)

## 2. Design

Use integers for the hours, hourly rate and total cost because all three are whole numbers. Test the hours before calculating the cost so that a rejected value never produces a total.

**Algorithm**

```text
1 Get the number of hours
2 Validate the number of hours
3 Calculate the total cost
4 Display the total cost in pounds
```

**Refinement**

```text
2.1 Start conditional loop while hours is less than 1 or greater than 4
2.2     Display "Enter a whole number from 1 to 4."
2.3     Get a new number of hours
2.4 End conditional loop

3.1 Multiply hours by 6 and store the result in total cost
```

[Software Design Overview](2.3-design/3.1-explanation.md) · [Design Notation](2.3-design/3.3-design-notation-explanation.md)

## 3. Python implementation

```python linenums="1"
hourly_rate = 6
hours = int(input("How many hours do you want to hire the bike for? "))

while hours < 1 or hours > 4:
    print("Enter a whole number from 1 to 4.")
    hours = int(input("How many hours do you want to hire the bike for? "))

total_cost = hours * hourly_rate
print(f"Total cost: £{total_cost}")
```

The `while` loop checks the current value before each pass. A valid first input skips the loop body. A rejected input is replaced by the next entry. The calculation and total appear after the loop, so the program displays one total per hire.

[Input Validation](2.4-implementation/04-standard-algorithms/4.3-input-validation.md) · [Calculations](2.4-implementation/01-input-output/1.9-calculations.md)

## 4. Testing

Start a fresh run for each row. In the exceptional tests, enter the second value when the program asks again.

| Input sequence | Type | Expected result | Actual result |
| --- | --- | --- | --- |
| `2` | Normal | Display `Total cost: £12` without an error. | £12 with no error. |
| `1` | Extreme | Accept the minimum and display `Total cost: £6`. | £6 with no error. |
| `4` | Extreme | Accept the maximum and display `Total cost: £24`. | £24 with no error. |
| `0`, then `2` | Exceptional, then normal | Show an error, ask again and display `Total cost: £12` after accepting 2. | Error shown, input requested again, then £12. |
| `5`, then `3` | Exceptional, then normal | Show an error, ask again and display `Total cost: £18` after accepting 3. | Error shown, input requested again, then £18. |

[Test Data and Test Tables](2.5-testing/01.md)

## 5. Evaluation

The results support the judgement that the program is **fit for purpose for whole-number inputs**. It accepts both boundaries and calculates the correct costs of £6 and £24. It rejects 0 and 5, asks again and calculates the cost using the accepted replacement. Text input is outside the brief. Entering text would raise a `ValueError` during conversion with `int()`.

[Evaluating a Program](2.7-evaluation/01-evaluating-code.md) · [Types of Programming Errors](2.5-testing/02-types-of-errors.md)

## Independent brief: Bowling lane hire

A bowling centre charges **£8 per game** for one lane. Ask how many games the customer wants to book. Accept **2 to 6 whole games**, show an error and ask again for any whole number outside that range, then display the total cost in pounds. Assume the customer enters whole numbers.

### Check your work

- State the purpose and identify the input, processes and outputs.
- Choose appropriate data types and write a numbered algorithm with refinements.
- Use one conditional loop to reject out-of-range values and read a replacement. Display the total after the loop.
- Prepare a test table with a normal value, both valid boundaries and the values immediately outside them. Include a valid retry after an invalid entry.
- Run the program and compare the actual and expected results. Write an evaluation judgement that cites at least one test result.
