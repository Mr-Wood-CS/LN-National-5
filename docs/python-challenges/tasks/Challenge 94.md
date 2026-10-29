# Postcode formatter: check the length

## Your task

Extend Postcode formatter: capital letters to check that the complete postcode, including its single middle space, is no longer than eight characters. This is a length check only, not a full check of real postcode rules.

## What to enter

Four text parts in the same order as the earlier postcode tasks. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Always display the joined, upper-case postcode. If it has more than eight characters, also display `Sorry - Postcode is longer than 8 characters` on the next line. Do not display an error for exactly eight.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **Text and `+` — join pieces of writing.** Text goes inside quotation marks. For example, `"Good" + " morning"` gives `Good morning`. Spaces must be included where you want them.
- **`.upper()` — make text upper case.** `"Hello".upper()` gives `HELLO`. Store the returned text if you need to use it again.
- **`len()` — count items or characters.** `len("Hello")` is `5`; for a list it counts the stored items. Spaces count as characters in text.
- **`if` — do something only when a check is true.** End the heading with a colon and indent the action underneath it. If the check is false, that action is skipped.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.

## Hint

??? tip "Show a hint"

    Count the completed text, rather than adding up only the letters. The space is a character too.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 94: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 94: test runs</caption>
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
        <td><code>kyv</code><br><code>82</code><br><code>15</code><br><code>hlb</code></td>
        <td><code>KYV82 15HLB</code><br><code>Sorry - Postcode is longer than 8 characters</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>eh</code><br><code>12</code><br><code>5</code><br><code>ab</code></td>
        <td><code>EH12 5AB</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>ab</code><br><code>12</code><br><code>3</code><br><code>cde</code></td>
        <td><code>AB12 3CDE</code><br><code>Sorry - Postcode is longer than 8 characters</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>ab</code><br><code>12</code><br><code>3</code><br><code>cd</code></td>
        <td><code>AB12 3CD</code></td>
      </tr>
    </tbody>
  </table>
</div>
