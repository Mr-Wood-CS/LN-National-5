# Leftover paint

## Your task

Calculate how many whole pots of paint cover a job and how much area the leftover paint could cover. Part of a pot cannot be bought. Use the same coverage rate for every pot.

## What to enter

Two positive numbers: area to paint in square metres, then area covered by one pot. Decimal values are allowed. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `You will need p pots of paint.` then `You can paint a m2 with the left over paint.` Show p as a whole number and a rounded and formatted to exactly two decimal places.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`float()` — turn text into a number that can have a decimal part.** For example, `float("2.5")` gives the number `2.5`.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`math.ceil()` — round upwards to a whole number.** Write `import math` first. `math.ceil(2.1)` gives `3`, while `math.ceil(2.0)` gives `2`.
- **`*` — multiply numbers.** For example, `6 * 4` gives `24`. Python uses `*`, rather than the multiplication sign you may use on paper.
- **`-` — subtract one number from another.** For example, `9 - 4` gives `5`. The order of the numbers matters.
- **`:.2f` formatting — show exactly two decimal places.** For example, `f"{3.5:.2f}"` produces `3.50`. This changes how a value is displayed.

## Hint

??? tip "Show a hint"

    Buying enough whole pots may leave spare coverage. A job that needs an exact number of pots should leave no spare coverage.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Rounding upwards with ceil](https://docs.python.org/3/library/math.html#math.ceil)
- [Working with numbers](https://snakify.org/lessons/integer_float_numbers/)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 95: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 95: test runs</caption>
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
        <td><code>178</code><br><code>25</code></td>
        <td><code>You will need 8 pots of paint.</code><br><code>You can paint 22.00 m2 with the left over paint.</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>50</code><br><code>25</code></td>
        <td><code>You will need 2 pots of paint.</code><br><code>You can paint 0.00 m2 with the left over paint.</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>3.5</code><br><code>2</code></td>
        <td><code>You will need 2 pots of paint.</code><br><code>You can paint 0.50 m2 with the left over paint.</code></td>
      </tr>
    </tbody>
  </table>
</div>
