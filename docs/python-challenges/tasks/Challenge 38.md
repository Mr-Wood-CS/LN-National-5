# Compare two rectangles

## Your task

Calculate the areas of two rectangles and report which is larger. Handle equal areas too.

## What to enter

Four positive numbers: first rectangle length and width, then second rectangle length and width. Decimal values are allowed. Type each value on a separate line, pressing Enter after each one.

## What your program should show

`Rectangle 1 has the largest area`, `Rectangle 2 has the largest area`, or `Both rectangles have the same area`.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`float()` — turn text into a number that can have a decimal part.** For example, `float("2.5")` gives the number `2.5`.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`*` — multiply numbers.** For example, `6 * 4` gives `24`. Python uses `*`, rather than the multiplication sign you may use on paper.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.

## Hint

??? tip "Show a hint"

    Find both areas before deciding which message to show. A longer side alone does not tell you which rectangle has more area.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 38: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 38: test runs</caption>
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
        <td><code>12</code><br><code>6</code><br><code>7</code><br><code>9</code></td>
        <td><code>Rectangle 1 has the largest area</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>2</code><br><code>3</code><br><code>4</code><br><code>5</code></td>
        <td><code>Rectangle 2 has the largest area</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>2</code><br><code>6</code><br><code>3</code><br><code>4</code></td>
        <td><code>Both rectangles have the same area</code></td>
      </tr>
    </tbody>
  </table>
</div>
