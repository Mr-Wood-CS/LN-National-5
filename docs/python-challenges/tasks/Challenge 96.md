# The ASCII game

## Your task

Generate one random ASCII code from 97 to 122, the codes for lower-case a to z. Display the code and keep asking for a letter until the correct one is entered. For wrong letters show the code they actually represent.

## What to enter

One lower-case letter from a to z per attempt. A correct letter will eventually be entered. Type each value on a separate line, pressing Enter after each one.

## What your program should show

First show `Guess the letter for ASCII code c.` For each wrong guess show `Sorry, letter would be code`. For the correct guess show `Correct, letter = c`. Replace the placeholders with the actual characters and codes.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`random.randint()` — choose a random whole number.** Write `import random` first. `random.randint(2, 8)` can return any whole number from 2 through 8, including both ends.
- **`ord()` — find a character code.** `ord("b")` gives `98`. Give it one character, rather than a whole word.
- **`chr()` — turn a character code into a character.** `chr(66)` gives `B`. Upper- and lower-case letters have different codes.
- **`while` — repeat while a check stays true.** Use a colon and an indented block. Make sure something checked by the loop can change, such as reading a new attempt.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    The random code stays fixed for the whole game. Use the character-conversion tools to compare the entered letter and to explain a wrong guess.

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

For the test table only, temporarily use ASCII code 113. Restore random selection in the finished game.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 96: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 96: test runs</caption>
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
        <td><code>f</code><br><code>r</code><br><code>q</code></td>
        <td><code>Guess the letter for ASCII code 113.</code><br><code>Sorry, f would be 102</code><br><code>Sorry, r would be 114</code><br><code>Correct, q = 113</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>q</code></td>
        <td><code>Guess the letter for ASCII code 113.</code><br><code>Correct, q = 113</code></td>
      </tr>
    </tbody>
  </table>
</div>
