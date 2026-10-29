# Formatting telephone numbers

## Your task

Join an area code and local telephone code, keeping every digit as entered.

## What to enter

Area code, then local code, both as text. Keep zeros at the start. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `You have entered:` on one line, then the area code and local code separated by one space.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **Text and `+` — join pieces of writing.** Text goes inside quotation marks. For example, `"Good" + " morning"` gives `Good morning`. Spaces must be included where you want them.

## Hint

??? tip "Show a hint"

    Telephone digits are labels, not quantities. Converting them to numbers could lose information.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 7: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 7: test runs</caption>
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
        <td><code>01592</code><br><code>583403</code></td>
        <td><code>You have entered:</code><br><code>01592 583403</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>01397</code><br><code>001234</code></td>
        <td><code>You have entered:</code><br><code>01397 001234</code></td>
      </tr>
    </tbody>
  </table>
</div>
