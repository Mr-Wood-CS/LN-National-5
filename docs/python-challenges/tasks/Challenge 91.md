# Which is bigger?

## Your task

Play ten rounds. Before each round, generate two random whole numbers from 1 to 1000, keeping them hidden until the player chooses number 1 or number 2. Reveal both numbers and award one point for choosing the larger. Equal numbers earn no point.

## What to enter

Ten choices, each the whole number 1 or 2. No retry checks are needed in this version. Type each value on a separate line, pressing Enter after each one.

## What your program should show

For each round show `Number 1 = a`, `Number 2 = b`, then `Correct!`, `Incorrect.` or `The numbers are equal. No point this round.` After ten rounds show `Your final score was s correct.`

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`random.randint()` — choose a random whole number.** Write `import random` first. `random.randint(2, 8)` can return any whole number from 2 through 8, including both ends.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **A running total — add each new amount to what is already stored.** Start it at zero before the loop. `total = total + amount` updates it without losing the earlier amounts.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.
- **`and` — require both checks to be true.** For example, `age >= 12 and age <= 16` checks whether an age is within that range, including the ends.
- **`or` — allow either check to be true.** For example, `choice == "A" or choice == "B"` accepts either of those letters.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    Keep the score outside the round loop. Reveal the numbers after reading the choice, so the choice is still a guess.

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

For this test only, use these pairs in order: 459 and 321; 10 and 20; 7 and 7; 1000 and 1; 2 and 3; 8 and 4; 11 and 90; 50 and 10; 6 and 9; 100 and 20. Restore random pairs afterwards. Other random pairs will give different results.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 91: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 91: test runs</caption>
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
        <td><code>1</code><br><code>2</code><br><code>1</code><br><code>2</code><br><code>1</code><br><code>1</code><br><code>2</code><br><code>2</code><br><code>2</code><br><code>1</code></td>
        <td><code>Number 1 = 459</code><br><code>Number 2 = 321</code><br><code>Correct!</code><br><code>Number 1 = 10</code><br><code>Number 2 = 20</code><br><code>Correct!</code><br><code>Number 1 = 7</code><br><code>Number 2 = 7</code><br><code>The numbers are equal. No point this round.</code><br><code>Number 1 = 1000</code><br><code>Number 2 = 1</code><br><code>Incorrect.</code><br><code>Number 1 = 2</code><br><code>Number 2 = 3</code><br><code>Incorrect.</code><br><code>Number 1 = 8</code><br><code>Number 2 = 4</code><br><code>Correct!</code><br><code>Number 1 = 11</code><br><code>Number 2 = 90</code><br><code>Correct!</code><br><code>Number 1 = 50</code><br><code>Number 2 = 10</code><br><code>Incorrect.</code><br><code>Number 1 = 6</code><br><code>Number 2 = 9</code><br><code>Correct!</code><br><code>Number 1 = 100</code><br><code>Number 2 = 20</code><br><code>Correct!</code><br><code>Your final score was 6 correct.</code></td>
      </tr>
    </tbody>
  </table>
</div>
