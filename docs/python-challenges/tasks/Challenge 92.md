# Advice please: upper or lower case

## Your task

Extend Advice please: keep asking so either upper- or lower-case Y and N are recognised. Convert each response to upper case before deciding what it means.

## What to enter

One response per line until y or Y is entered. Other responses may contain any text. Type each value on a separate line, pressing Enter after each one.

## What your program should show

For n or N show `You might find some advice helpful!`. For other responses except y/Y show `Please enter Y or N only.` Finish with `Always know where your towel is.`

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`.upper()` — make text upper case.** `"Hello".upper()` gives `HELLO`. Store the returned text if you need to use it again.
- **`while` — repeat while a check stays true.** Use a colon and an indented block. Make sure something checked by the loop can change, such as reading a new attempt.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.

## Hint

??? tip "Show a hint"

    Remember to convert every new attempt, not only the first one. Otherwise a later lower-case response could still be rejected.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 92: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 92: test runs</caption>
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
        <td><code>n</code><br><code>y</code></td>
        <td><code>You might find some advice helpful!</code><br><code>Always know where your towel is.</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>?</code><br><code>Y</code></td>
        <td><code>Please enter Y or N only.</code><br><code>Always know where your towel is.</code></td>
      </tr>
    </tbody>
  </table>
</div>
