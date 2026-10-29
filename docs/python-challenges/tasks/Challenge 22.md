# Last two digits

## Your task

Write a Python program for this task.

Display the final two digits of a positive whole number.

## What to enter

One whole number greater than or equal to 10. Type each number on a new line, pressing Enter after each one.

## What your program should show

Exactly two digits on one line. Keep a zero at the start if needed, including `00` if both final digits are zero.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`%` — remainder, also called modulo.** It tells you what is left after division. For example, `17 % 5` gives `2`.
- **Number formatting — keep a zero at the start.** In an f-string, `:02d` shows a whole number using at least two digits. For example, `f"{7:02d}"` gives the text `07`.

## Hint

??? tip "Show a hint"

    Underline just the final two digits of the number. The earlier digits should not affect your result. Think separately about finding those digits and showing both of them when one is zero.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 22: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 22: test runs</caption>
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
        <td><code>1234</code></td>
        <td><code>34</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>567</code></td>
        <td><code>67</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>64</code></td>
        <td><code>64</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>82649</code></td>
        <td><code>49</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>182310</code></td>
        <td><code>10</code></td>
      </tr>
    </tbody>
  </table>
</div>
