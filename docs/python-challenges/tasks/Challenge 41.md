# Solid, liquid or gas

## Your task

At normal atmospheric pressure, water is solid at 0°C or below, gas at 100°C or above, and liquid between those temperatures. Report its state.

## What to enter

One temperature in degrees Celsius. Negative and decimal values are allowed. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `At t degrees centigrade,` then `water will be a state.` Replace t and state with the entered temperature and `solid`, `liquid` or `gas`. Whole temperatures may include `.0`.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`float()` — turn text into a number that can have a decimal part.** For example, `float("2.5")` gives the number `2.5`.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    Think carefully about the two boundary temperatures. Each belongs to a different end state, rather than to the middle range.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 41: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 41: test runs</caption>
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
        <td><code>78</code></td>
        <td><code>At 78 degrees centigrade,</code><br><code>water will be a liquid.</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>0</code></td>
        <td><code>At 0 degrees centigrade,</code><br><code>water will be a solid.</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>100</code></td>
        <td><code>At 100 degrees centigrade,</code><br><code>water will be a gas.</code></td>
      </tr>
    </tbody>
  </table>
</div>
