# Charity collection

## Your task

Add the money raised by three friends. If their total is at least £1000, a company doubles it. Otherwise the total stays unchanged.

## What to enter

Three whole-pound amounts, each zero or greater. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Always show `A total of £t was raised.` with the original total. If it is at least £1000, also show `This will be doubled to £f.` with the final amount. Otherwise, show only the first line.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`+` — add numbers.** For example, `8 + 4` gives `12`. Make sure the values are numbers: joining text works differently.
- **`if` — do something only when a check is true.** End the heading with a colon and indent the action underneath it. If the check is false, that action is skipped.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    Keep the original total so that the first message remains correct even if the company adds money. Exactly £1000 qualifies.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 35: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 35: test runs</caption>
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
        <td><code>A total of £1069 was raised.</code><br><code>This will be doubled to £2138.</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>300</code><br><code>300</code><br><code>400</code></td>
        <td><code>A total of £1000 was raised.</code><br><code>This will be doubled to £2000.</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>100</code><br><code>200</code><br><code>300</code></td>
        <td><code>A total of £600 was raised.</code></td>
      </tr>
    </tbody>
  </table>
</div>
