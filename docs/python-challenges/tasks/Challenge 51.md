# Charity collection: revised bonus

## Your task

Add three friends' collections, then calculate the final amount using the new offer. Use the revised company offer: below £1000 add £100; from £1000 through £2000 double the total; above £2000 double only the first £2000 and leave the rest unchanged.

## What to enter

Three whole-pound amounts, each zero or greater. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Two lines: `A total of £t was raised.` then `With the company bonus, this is £f.` Replace t and f with the original and final amounts.

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
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    Separate the total into the three bands in the offer. For the highest band, the offer applies differently to the first part and the amount beyond it.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Read the lesson on making decisions](https://snakify.org/lessons/if_then_else_conditions/)
- [Work through the lesson one small step at a time](https://snakify.org/lessons/if_then_else_conditions/steps/1/)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 51: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 51: test runs</caption>
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
        <td><code>745</code><br><code>690</code><br><code>1024</code></td>
        <td><code>A total of £2459 was raised.</code><br><code>With the company bonus, this is £4459.</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>100</code><br><code>100</code><br><code>100</code></td>
        <td><code>A total of £300 was raised.</code><br><code>With the company bonus, this is £400.</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>500</code><br><code>500</code><br><code>0</code></td>
        <td><code>A total of £1000 was raised.</code><br><code>With the company bonus, this is £2000.</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>1000</code><br><code>1000</code><br><code>0</code></td>
        <td><code>A total of £2000 was raised.</code><br><code>With the company bonus, this is £4000.</code></td>
      </tr>
    </tbody>
  </table>
</div>
