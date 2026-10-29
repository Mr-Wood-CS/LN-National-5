# Standard scratch golf score

## Your task

Each par-3 hole contributes 3 shots, each par-4 hole 4 shots, and each par-5 hole 5 shots. Add their contributions, then add the signed difficulty adjustment to find the standard scratch score.

## What to enter

Four whole numbers: count of par-3 holes, count of par-4 holes, count of par-5 holes, then difficulty adjustment. Counts are zero or greater; the adjustment may be negative. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `The Standard Scratch for the course is:` on one line and the score on the next.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`*` — multiply numbers.** For example, `6 * 4` gives `24`. Python uses `*`, rather than the multiplication sign you may use on paper.
- **`+` — add numbers.** For example, `8 + 4` gives `12`. Make sure the values are numbers: joining text works differently.

## Hint

??? tip "Show a hint"

    Treat each type of hole as its own group. The adjustment already has a sign, so a negative adjustment should reduce the score.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Read the lesson on entering and displaying information](https://snakify.org/lessons/print_input_numbers/)
- [Work through the lesson one small step at a time](https://snakify.org/lessons/print_input_numbers/steps/1/)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 16: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 16: test runs</caption>
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
        <td><code>6</code><br><code>10</code><br><code>2</code><br><code>-2</code></td>
        <td><code>The Standard Scratch for the course is:</code><br><code>66</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>6</code><br><code>6</code><br><code>6</code><br><code>0</code></td>
        <td><code>The Standard Scratch for the course is:</code><br><code>72</code></td>
      </tr>
    </tbody>
  </table>
</div>
