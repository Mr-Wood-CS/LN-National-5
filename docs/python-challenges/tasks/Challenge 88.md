# House floor area

## Your task

Read and store the length and width of each room in matching lists. After all measurements are entered, use the stored data to display each room's area and the total floor area. Assume rooms are rectangles and do not overlap.

## What to enter

Number of rooms (a positive whole number), then each room's length and width in metres. Measurements are positive numbers and may contain decimals. Type each value on a separate line, pressing Enter after each one.

## What your program should show

For each room show `Room n` then `length x width = area metres squared`. Display measurements and room areas without unnecessary trailing zeros. Finally show `Total Area = total metres squared` with the total rounded and displayed to exactly two decimal places.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`float()` — turn text into a number that can have a decimal part.** For example, `float("2.5")` gives the number `2.5`.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **Lists — store several related values together.** For example, `colours = ["red", "blue"]` stores two text values in order. In these tasks, a Python list is used as an array.
- **`.append()` — add one value to a list.** `colours.append("green")` adds a new item at the end. Start with `[]` if the list is empty.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **Square brackets — read a stored position.** For example, `colours[0]` reads the first item. Python list positions start at zero, not one.
- **`*` — multiply numbers.** For example, `6 * 4` gives `24`. Python uses `*`, rather than the multiplication sign you may use on paper.
- **A running total — add each new amount to what is already stored.** Start it at zero before the loop. `total = total + amount` updates it without losing the earlier amounts.
- **`:.2f` formatting — show exactly two decimal places.** For example, `f"{3.5:.2f}"` produces `3.50`. This changes how a value is displayed.
- **`:g` formatting — avoid unnecessary trailing zeros.** For example, `f"{4.0:g}"` shows `4`. Use this for the room-by-room report; the final total uses `.2f` instead.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    Store the measurements before producing the room report. Round the total only for display, so earlier rounding does not change it.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 88: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 88: test runs</caption>
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
        <td><code>3</code><br><code>3.56</code><br><code>4.7</code><br><code>2.26</code><br><code>3.69</code><br><code>4.5</code><br><code>4.7</code></td>
        <td><code>Room 1</code><br><code>3.56 x 4.7 = 16.732 metres squared</code><br><code>Room 2</code><br><code>2.26 x 3.69 = 8.3394 metres squared</code><br><code>Room 3</code><br><code>4.5 x 4.7 = 21.15 metres squared</code><br><code>Total Area = 46.22 metres squared</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>1</code><br><code>2</code><br><code>3</code></td>
        <td><code>Room 1</code><br><code>2 x 3 = 6 metres squared</code><br><code>Total Area = 6.00 metres squared</code></td>
      </tr>
    </tbody>
  </table>
</div>
