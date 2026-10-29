# Tyre and brake wear

## Your task

Compare a measured stopping distance with the supplied reference for the selected speed. A distance equal to the reference passes. Use these classroom reference distances: 20 mph → 6 m, 30 → 14 m, 40 → 24 m, 50 → 38 m, 60 → 55 m, 70 → 75 m. These figures are supplied data for this programming exercise.

## What to enter

A whole-number speed chosen from 20, 30, 40, 50, 60 or 70, then a positive distance in metres. The distance may contain decimals. Type each value on a separate line, pressing Enter after each one.

## What your program should show

If the distance is greater than the reference, show `Your car failed the braking distance test.` then `Submit your car for a tyre and brake test soon.` Otherwise show `Your car passed the braking distance test.` then `Well done`.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`float()` — turn text into a number that can have a decimal part.** For example, `float("2.5")` gives the number `2.5`.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.

## Hint

??? tip "Show a hint"

    The speed selects a reference distance. After finding that reference, you have a separate comparison to make with the measured distance.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 50: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 50: test runs</caption>
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
        <td><code>40</code><br><code>26.7</code></td>
        <td><code>Your car failed the braking distance test.</code><br><code>Submit your car for a tyre and brake test soon.</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>40</code><br><code>24</code></td>
        <td><code>Your car passed the braking distance test.</code><br><code>Well done</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>20</code><br><code>5</code></td>
        <td><code>Your car passed the braking distance test.</code><br><code>Well done</code></td>
      </tr>
    </tbody>
  </table>
</div>
