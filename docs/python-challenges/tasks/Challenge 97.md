# Guess the number: whole-number guesses

## Your task

Extend Guess the number: random target to reject guesses with a non-zero decimal part. Use rounding to compare the entered value with a whole-number value, but never silently round a fractional guess into an accepted guess.

## What to enter

Numeric guesses from 1 to 100. Values such as 86.0 count as whole numbers; values such as 86.7 must be rejected. A correct whole-number guess will eventually be entered. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Use the same heading and feedback as the random guessing game. For every fractional guess show `Not a whole number. Please enter again` instead of a too-high or too-low message, then read another guess.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`float()` — turn text into a number that can have a decimal part.** For example, `float("2.5")` gives the number `2.5`.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`round()` — round a number.** `round(3.7)` gives `4`. With no second argument it returns a whole number. An exact half goes to the nearest even whole number, so `round(2.5)` is `2` and `round(3.5)` is `4`.
- **`while` — repeat while a check stays true.** Use a colon and an indented block. Make sure something checked by the loop can change, such as reading a new attempt.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.

## Hint

??? tip "Show a hint"

    Check whether a guess is a whole number before comparing it with the target. Rounding can help with the check, but the original fractional guess must not become a valid attempt.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Python built-in functions](https://docs.python.org/3/library/functions.html)
- [Python text tools](https://docs.python.org/3/library/stdtypes.html#str.upper)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

For the test table only, temporarily use 67 as the hidden number. Restore random selection afterwards.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 97: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 97: test runs</caption>
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
        <td><code>45</code><br><code>86.7</code><br><code>86</code><br><code>67</code></td>
        <td><code>Guess the hidden number between 1 and 100.</code><br><code>Your guess is too low. Try again.</code><br><code>Not a whole number. Please enter again</code><br><code>Your guess is too high. Try again.</code><br><code>Correct! Well done.</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>67.0</code></td>
        <td><code>Guess the hidden number between 1 and 100.</code><br><code>Correct! Well done.</code></td>
      </tr>
    </tbody>
  </table>
</div>
