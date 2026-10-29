# Atomic mass of an alkane

## Your task

An alkane contains carbon (C) and hydrogen (H). Its hydrogen count is twice its carbon count plus two. Its relative molecular mass is twelve times its carbon count plus its hydrogen count. Calculate both counts and the mass.

## What to enter

One positive whole number: the number of carbon atoms. Type each value on a separate line, pressing Enter after each one.

## What your program should show

One line in the format `The atomic mass of CcHh is m`, replacing c, h and m with the carbon count, hydrogen count and mass. Do not include spaces inside the chemical formula.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`*` — multiply numbers.** For example, `6 * 4` gives `24`. Python uses `*`, rather than the multiplication sign you may use on paper.
- **`+` — add numbers.** For example, `8 + 4` gives `12`. Make sure the values are numbers: joining text works differently.
- **Brackets — control which calculation happens first.** Python works out the part in brackets first: `(2 + 3) * 4` gives `20`.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    There are two linked calculations. Keep the hydrogen count in its own variable so that you can use it again when finding the mass.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 15: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 15: test runs</caption>
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
        <td><code>3</code></td>
        <td><code>The atomic mass of C3H8 is 44</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>1</code></td>
        <td><code>The atomic mass of C1H4 is 16</code></td>
      </tr>
    </tbody>
  </table>
</div>
