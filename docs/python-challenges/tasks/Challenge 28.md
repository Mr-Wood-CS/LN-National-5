# Total cupcake cost

## Your task

Write a Python program for this task.

Calculate the total cost of several cupcakes from the price of one. One dollar equals 100 cents.

## What to enter

Three whole numbers: dollars per cupcake (at least 0), cents per cupcake (0–99), then cupcake quantity (at least 0). Type each number on a new line, pressing Enter after each one.

## What your program should show

Two whole numbers on one line separated by one space: total whole dollars, then remaining cents (0–99). Do not add a dollar sign or put a zero before a one-digit cents amount.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`*` — multiply numbers.** For example, `6 * 4` gives `24`. Python uses `*`, rather than the multiplication sign you may use on paper.
- **`+` — add numbers.** For example, `8 + 4` gives `12`. Make sure the values are numbers: joining text works differently.
- **`//` — whole-number division.** It tells you how many complete groups fit when sharing positive amounts. For example, `17 // 5` gives `3`.
- **`%` — remainder, also called modulo.** It tells you what is left after division. For example, `17 % 5` gives `2`.
- **Brackets — control which calculation happens first.** Python works out the part in brackets first: `(2 + 3) * 4` gives `20`.

## Hint

??? tip "Show a hint"

    Dollars and cents are two ways of describing the same amount of money. Would using one unit while doing the calculation make things easier? Remember that the final answer needs both parts again.

## Need a hand?

If you are stuck, try one of these help pages, then come back to your program.

- [Read the lesson on working with numbers](https://snakify.org/lessons/integer_float_numbers/)
- [Work through the same lesson one small step at a time](https://snakify.org/lessons/integer_float_numbers/steps/1/)

If you are still unsure, ask your teacher to help you understand the task.


## Try your program

Use the tests below to check your program. You do not need to make up your own numbers.

1. Run your program.
2. Type the values in the middle column, one at a time. Press Enter after each line.
3. Compare your result with the last column. It should match.
4. If it matches, tick that test in your workbook. If it does not, check your code and try again.
5. Run your program again for the next test.

Where a table cell has several lines, keep the same line breaks when typing or comparing the result.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 28: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 28: test runs</caption>
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
        <td><code>10</code><br><code>15</code><br><code>2</code></td>
        <td><code>20 30</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>2</code><br><code>50</code><br><code>4</code></td>
        <td><code>10 0</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>3000</code><br><code>99</code><br><code>3000</code></td>
        <td><code>9002970 0</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>2029</code><br><code>34</code><br><code>1848</code></td>
        <td><code>3750220 32</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>1886</code><br><code>73</code><br><code>295</code></td>
        <td><code>556585 35</code></td>
      </tr>
    </tbody>
  </table>
</div>
