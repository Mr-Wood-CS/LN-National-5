# Advice please: keep asking

## Your task

Keep reading responses until the user enters capital Y. Capital N receives an encouraging message; any other response receives an error message. After Y, give advice and stop.

## What to enter

One response per line. Capital Y will eventually be entered. Type each value on a separate line, pressing Enter after each one.

## What your program should show

For N: `You might find some advice helpful!` For other responses except Y: `Please enter Y or N only.` For Y: `Always know where your towel is.`

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`while` — repeat while a check stays true.** Use a colon and an indented block. Make sure something checked by the loop can change, such as reading a new attempt.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.

## Hint

??? tip "Show a hint"

    Use the loop to keep asking and a decision inside it to choose the retry message. The advice should appear only when the loop is finished.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 77: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 77: test runs</caption>
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
        <td><code>H</code><br><code>N</code><br><code>Y</code></td>
        <td><code>Please enter Y or N only.</code><br><code>You might find some advice helpful!</code><br><code>Always know where your towel is.</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>Y</code></td>
        <td><code>Always know where your towel is.</code></td>
      </tr>
    </tbody>
  </table>
</div>
