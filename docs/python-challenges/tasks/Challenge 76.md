# Password check

## Your task

Keep reading password attempts until the correct classroom password, `ornery`, is entered. Capital letters matter.

## What to enter

One password attempt per line. A correct attempt will eventually be entered. Type each value on a separate line, pressing Enter after each one.

## What your program should show

For each incorrect attempt show `Sorry, incorrect. Try again.` After the correct attempt, show `Entry gained!` once and stop.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`while` — repeat while a check stays true.** Use a colon and an indented block. Make sure something checked by the loop can change, such as reading a new attempt.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.

## Hint

??? tip "Show a hint"

    An incorrect attempt must lead to another input. Make sure the value used in the loop condition can change.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 76: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 76: test runs</caption>
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
        <td><code>snool</code><br><code>ornery</code></td>
        <td><code>Sorry, incorrect. Try again.</code><br><code>Entry gained!</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>ornery</code></td>
        <td><code>Entry gained!</code></td>
      </tr>
    </tbody>
  </table>
</div>
