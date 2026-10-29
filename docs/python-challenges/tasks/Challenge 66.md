# Charity collection: repeated result

## Your task

Use the revised charity offer and emphasise the final amount by displaying it three times using a loop. Use the revised company offer: below £1000 add £100; from £1000 through £2000 double the total; above £2000 double only the first £2000 and leave the rest unchanged.

## What to enter

Three whole-pound amounts, each zero or greater. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `A total of £t was raised.` then `With the company bonus, this is:`. Show the final amount in the format `£f!!!` on each of the next three lines.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`+` — add numbers.** For example, `8 + 4` gives `12`. Make sure the values are numbers: joining text works differently.
- **`*` — multiply numbers.** For example, `6 * 4` gives `24`. Python uses `*`, rather than the multiplication sign you may use on paper.
- **`-` — subtract one number from another.** For example, `9 - 4` gives `5`. The order of the numbers matters.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    Calculate the final amount once. The loop should repeat the display, rather than repeatedly adding the company bonus.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 66: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 66: test runs</caption>
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
        <td><code>398</code><br><code>193</code><br><code>478</code></td>
        <td><code>A total of £1069 was raised.</code><br><code>With the company bonus, this is:</code><br><code>£2138!!!</code><br><code>£2138!!!</code><br><code>£2138!!!</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>100</code><br><code>100</code><br><code>100</code></td>
        <td><code>A total of £300 was raised.</code><br><code>With the company bonus, this is:</code><br><code>£400!!!</code><br><code>£400!!!</code><br><code>£400!!!</code></td>
      </tr>
    </tbody>
  </table>
</div>
