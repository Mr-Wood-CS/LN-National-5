# Guess the number

## Your task

Use a fixed hidden number of 52 for this first version. Keep accepting guesses and give a too-low, too-high or correct message. Stop when the number is guessed.

## What to enter

One whole-number guess from 1 to 100 per line. A correct guess will eventually be entered. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `Guess the hidden number between 1 and 100.` once. For wrong guesses show `Your guess is too low. Try again.` or `Your guess is too high. Try again.` For the correct guess show `Correct! Well done.`

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`while` — repeat while a check stays true.** Use a colon and an indented block. Make sure something checked by the loop can change, such as reading a new attempt.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.

## Hint

??? tip "Show a hint"

    The hidden number stays the same throughout a game. A wrong guess should produce feedback and another input, not end the game.

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

Optional extra: count every guess, including the correct one, and display the count after the final message. The test table checks the main task without this extra line.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 82: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 82: test runs</caption>
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
        <td><code>45</code><br><code>86</code><br><code>67</code><br><code>50</code><br><code>54</code><br><code>52</code></td>
        <td><code>Guess the hidden number between 1 and 100.</code><br><code>Your guess is too low. Try again.</code><br><code>Your guess is too high. Try again.</code><br><code>Your guess is too high. Try again.</code><br><code>Your guess is too low. Try again.</code><br><code>Your guess is too high. Try again.</code><br><code>Correct! Well done.</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>52</code></td>
        <td><code>Guess the hidden number between 1 and 100.</code><br><code>Correct! Well done.</code></td>
      </tr>
    </tbody>
  </table>
</div>
