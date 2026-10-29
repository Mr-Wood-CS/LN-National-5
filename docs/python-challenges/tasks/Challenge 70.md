# Lines cheat: choose the number

## Your task

Extend Lines cheat so the user chooses how many times to repeat their sentence. Use a fixed-count loop controlled by that number.

## What to enter

A sentence, then a whole-number repetition count of zero or more. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show the sentence once per line for the requested number of lines. A count of zero produces no output.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.

## Hint

??? tip "Show a hint"

    The loop count now comes from a variable rather than a fixed number in your program. Read both inputs before starting the loop.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Read the lesson on fixed-count loops](https://snakify.org/lessons/for_loop_range/)
- [Work through the lesson one small step at a time](https://snakify.org/lessons/for_loop_range/steps/1/)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 70: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 70: test runs</caption>
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
        <td><code>Keep learning!</code><br><code>3</code></td>
        <td><code>Keep learning!</code><br><code>Keep learning!</code><br><code>Keep learning!</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>Keep learning!</code><br><code>0</code></td>
        <td><em>No output</em></td>
      </tr>
    </tbody>
  </table>
</div>
