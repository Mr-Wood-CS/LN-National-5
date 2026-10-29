# Guess the number: random target

## Your task

Extend Guess the number so the hidden number is randomly chosen from 1 through 100 at the start of each game. Keep it unchanged during that game and do not reveal it.

## What to enter

Whole-number guesses from 1 to 100, one per line, until the chosen number is guessed. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Use the same heading and feedback as Guess the number: `Guess the hidden number between 1 and 100.`, too-low or too-high messages for wrong guesses, then `Correct! Well done.`

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`random.randint()` — choose a random whole number.** Write `import random` first. `random.randint(2, 8)` can return any whole number from 2 through 8, including both ends.
- **`while` — repeat while a check stays true.** Use a colon and an indented block. Make sure something checked by the loop can change, such as reading a new attempt.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.

## Hint

??? tip "Show a hint"

    Choose the random target once before the guessing loop. Choosing it again after every guess would make the target move.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Random number help](https://docs.python.org/3/library/random.html#random.randint)
- [Character codes, lengths and rounding](https://docs.python.org/3/library/functions.html)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

For the test table only, temporarily use 52 as the hidden number. Restore random selection for the finished version.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 90: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 90: test runs</caption>
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
        <td><code>45</code><br><code>86</code><br><code>52</code></td>
        <td><code>Guess the hidden number between 1 and 100.</code><br><code>Your guess is too low. Try again.</code><br><code>Your guess is too high. Try again.</code><br><code>Correct! Well done.</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>52</code></td>
        <td><code>Guess the hidden number between 1 and 100.</code><br><code>Correct! Well done.</code></td>
      </tr>
    </tbody>
  </table>
</div>
