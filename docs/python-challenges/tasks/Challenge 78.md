# Tyre and brake wear: check the inputs

## Your task

Extend Tyre and brake wear with retry loops. Accept only the six listed test speeds, then accept only a positive stopping distance. Use these classroom reference distances: 20 mph → 6 m, 30 → 14 m, 40 → 24 m, 50 → 38 m, 60 → 55 m, 70 → 75 m. These figures are supplied data for this programming exercise.

## What to enter

Speed attempts until one of 20, 30, 40, 50, 60 or 70 is entered, followed by distance attempts until a number greater than zero is entered. All attempts are numeric. Type each value on a separate line, pressing Enter after each one.

## What your program should show

For each invalid speed show `Choose 20, 30, 40, 50, 60 or 70 mph.` For each invalid distance show `Enter a distance greater than 0.` Then show the same two pass/fail lines as Tyre and brake wear.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`float()` — turn text into a number that can have a decimal part.** For example, `float("2.5")` gives the number `2.5`.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`while` — repeat while a check stays true.** Use a colon and an indented block. Make sure something checked by the loop can change, such as reading a new attempt.
- **`and` — require both checks to be true.** For example, `age >= 12 and age <= 16` checks whether an age is within that range, including the ends.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.

## Hint

??? tip "Show a hint"

    Check the speed fully before asking for the distance. A speed between two listed values has no reference distance in this task.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Read the lesson on loops that continue until a condition changes](https://snakify.org/lessons/while_loop/)
- [Work through the lesson one small step at a time](https://snakify.org/lessons/while_loop/steps/1/)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 78: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 78: test runs</caption>
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
        <td><code>15</code><br><code>40</code><br><code>-5.6</code><br><code>23.2</code></td>
        <td><code>Choose 20, 30, 40, 50, 60 or 70 mph.</code><br><code>Enter a distance greater than 0.</code><br><code>Your car passed the braking distance test.</code><br><code>Well done</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>25</code><br><code>20</code><br><code>0</code><br><code>7</code></td>
        <td><code>Choose 20, 30, 40, 50, 60 or 70 mph.</code><br><code>Enter a distance greater than 0.</code><br><code>Your car failed the braking distance test.</code><br><code>Submit your car for a tyre and brake test soon.</code></td>
      </tr>
    </tbody>
  </table>
</div>
