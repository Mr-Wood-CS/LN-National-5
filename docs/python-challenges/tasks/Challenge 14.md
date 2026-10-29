# Number generator: three digits

## Your task

Extend the two-digit number generator to build a number from three individual digits. Use a calculation and store the result in `total`.

## What to enter

Three whole numbers from 0 to 9: hundreds digit, tens digit, then units digit. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show the completed number as a whole number. Do not keep zeros at the start.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`*` — multiply numbers.** For example, `6 * 4` gives `24`. Python uses `*`, rather than the multiplication sign you may use on paper.
- **`+` — add numbers.** For example, `8 + 4` gives `12`. Make sure the values are numbers: joining text works differently.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.

## Hint

??? tip "Show a hint"

    Add a hundreds column to your place-value chart. Think about the value of each entered digit in its new position.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Read the lesson on entering and displaying information](https://snakify.org/lessons/print_input_numbers/)
- [Work through the lesson one small step at a time](https://snakify.org/lessons/print_input_numbers/steps/1/)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 14: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 14: test runs</caption>
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
        <td><code>3</code><br><code>5</code><br><code>7</code></td>
        <td><code>357</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>0</code><br><code>4</code><br><code>2</code></td>
        <td><code>42</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>8</code><br><code>0</code><br><code>0</code></td>
        <td><code>800</code></td>
      </tr>
    </tbody>
  </table>
</div>
