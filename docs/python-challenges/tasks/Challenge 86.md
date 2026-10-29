# Dance group

## Your task

Read and store the names and ages of four competitors in matching lists. After all four have been entered, display the correct competition level for each. Junior is under 12, Teen is 12–17, and Senior is 18 or older.

## What to enter

Eight lines: name then age for the first competitor, followed by name and age for each remaining competitor. Ages are whole numbers of zero or more. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `Names and Competition List:` then four lines in the format `name - level`. Preserve input order and capitalise Junior, Teen and Senior exactly as shown.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **Lists — store several related values together.** For example, `colours = ["red", "blue"]` stores two text values in order. In these tasks, a Python list is used as an array.
- **`.append()` — add one value to a list.** `colours.append("green")` adds a new item at the end. Start with `[]` if the list is empty.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **Square brackets — read a stored position.** For example, `colours[0]` reads the first item. Python list positions start at zero, not one.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    Keep each competitor's name and age at the same position in the two lists. Be careful with ages at the start of a new level.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Read the lesson on storing values in lists](https://snakify.org/lessons/lists/)
- [Work through the lesson one small step at a time](https://snakify.org/lessons/lists/steps/1/)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 86: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 86: test runs</caption>
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
        <td><code>Jean Gray</code><br><code>13</code><br><code>Max Eisenhardt</code><br><code>24</code><br><code>James Howlett</code><br><code>15</code><br><code>Anna Marie</code><br><code>9</code></td>
        <td><code>Names and Competition List:</code><br><code>Jean Gray - Teen</code><br><code>Max Eisenhardt - Senior</code><br><code>James Howlett - Teen</code><br><code>Anna Marie - Junior</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>A</code><br><code>11</code><br><code>B</code><br><code>12</code><br><code>C</code><br><code>17</code><br><code>D</code><br><code>18</code></td>
        <td><code>Names and Competition List:</code><br><code>A - Junior</code><br><code>B - Teen</code><br><code>C - Teen</code><br><code>D - Senior</code></td>
      </tr>
    </tbody>
  </table>
</div>
