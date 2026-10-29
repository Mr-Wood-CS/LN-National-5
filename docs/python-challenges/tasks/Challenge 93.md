# Postcode formatter: capital letters

## Your task

Extend Postcode formatter so all letters in the finished postcode are capital letters, even if typed in lower case.

## What to enter

Four text parts: first letters, first number part, second number part, final letters. Keep zeros in the number parts. Type each value on a separate line, pressing Enter after each one.

## What your program should show

One correctly spaced postcode, with all letters in upper case.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **Text and `+` — join pieces of writing.** Text goes inside quotation marks. For example, `"Good" + " morning"` gives `Good morning`. Spaces must be included where you want them.
- **`.upper()` — make text upper case.** `"Hello".upper()` gives `HELLO`. Store the returned text if you need to use it again.

## Hint

??? tip "Show a hint"

    Build the two postcode groups as before. Think about whether converting case should change any spaces or digits.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 93: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 93: test runs</caption>
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
        <td><code>ky</code><br><code>8</code><br><code>1</code><br><code>hl</code></td>
        <td><code>KY8 1HL</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>eH</code><br><code>12</code><br><code>5</code><br><code>aB</code></td>
        <td><code>EH12 5AB</code></td>
      </tr>
    </tbody>
  </table>
</div>
