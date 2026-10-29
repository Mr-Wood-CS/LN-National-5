# Horse hands

## Your task

Store the fifteen horses in the supplied data table in three matching lists: name, age and height. Display horses whose age and height are both within the rider's chosen maximums. Height is measured in hands; for this exercise all heights are whole numbers.

## What to enter

Two positive whole numbers: maximum height in hands, then maximum age in years. The horse details are fixed data, not typed during a run. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show each suitable horse as `name, age years, height hands`, in the supplied order. If none qualifies, show `No suitable horses.` Do not show any other heading.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **Lists — store several related values together.** For example, `colours = ["red", "blue"]` stores two text values in order. In these tasks, a Python list is used as an array.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **`len()` — count items or characters.** `len("Hello")` is `5`; for a list it counts the stored items. Spaces count as characters in text.
- **Square brackets — read a stored position.** For example, `colours[0]` reads the first item. Python list positions start at zero, not one.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`and` — require both checks to be true.** For example, `age >= 12 and age <= 16` checks whether an age is within that range, including the ends.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    A horse must meet both limits, including values equal to a limit. Use the same list position to keep a horse's name, age and height together.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Read the lesson on storing values in lists](https://snakify.org/lessons/lists/)
- [Work through the lesson one small step at a time](https://snakify.org/lessons/lists/steps/1/)


## Data to use

<div class="challenge-table-scroll" role="region" aria-label="Horse hands: supplied data" tabindex="0">
  <table class="challenge-table challenge-table--data">
    <caption>Horse hands: supplied data</caption>
    <thead>
      <tr>
        <th scope="col">Name</th>
        <th scope="col">Age (years)</th>
        <th scope="col">Height (hands)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row">Black Beauty</th>
        <td>14</td>
        <td>15</td>
      </tr>
      <tr>
        <th scope="row">Francine</th>
        <td>8</td>
        <td>14</td>
      </tr>
      <tr>
        <th scope="row">Langrish</th>
        <td>15</td>
        <td>14</td>
      </tr>
      <tr>
        <th scope="row">Amber</th>
        <td>6</td>
        <td>16</td>
      </tr>
      <tr>
        <th scope="row">Bracken</th>
        <td>12</td>
        <td>17</td>
      </tr>
      <tr>
        <th scope="row">Clover</th>
        <td>5</td>
        <td>13</td>
      </tr>
      <tr>
        <th scope="row">Daisy</th>
        <td>18</td>
        <td>15</td>
      </tr>
      <tr>
        <th scope="row">Echo</th>
        <td>9</td>
        <td>16</td>
      </tr>
      <tr>
        <th scope="row">Fern</th>
        <td>7</td>
        <td>14</td>
      </tr>
      <tr>
        <th scope="row">Hazel</th>
        <td>16</td>
        <td>16</td>
      </tr>
      <tr>
        <th scope="row">Jasper</th>
        <td>10</td>
        <td>15</td>
      </tr>
      <tr>
        <th scope="row">Luna</th>
        <td>4</td>
        <td>12</td>
      </tr>
      <tr>
        <th scope="row">Misty</th>
        <td>11</td>
        <td>17</td>
      </tr>
      <tr>
        <th scope="row">Rowan</th>
        <td>20</td>
        <td>16</td>
      </tr>
      <tr>
        <th scope="row">Willow</th>
        <td>13</td>
        <td>15</td>
      </tr>
    </tbody>
  </table>
</div>

## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

The PDF does not supply all fifteen records. The classroom data table below completes the dataset; use it for every test.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 87: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 87: test runs</caption>
    <thead>
      <tr>
        <th scope="col">Test</th>
        <th scope="col">Type these values<br>one per line</th>
        <th scope="col">You should see</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row">1</th>
        <td><code>14</code><br><code>8</code></td>
        <td><code>Francine, 8 years, 14 hands</code><br><code>Clover, 5 years, 13 hands</code><br><code>Fern, 7 years, 14 hands</code><br><code>Luna, 4 years, 12 hands</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>12</code><br><code>4</code></td>
        <td><code>Luna, 4 years, 12 hands</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>10</code><br><code>2</code></td>
        <td><code>No suitable horses.</code></td>
      </tr>
    </tbody>
  </table>
</div>
