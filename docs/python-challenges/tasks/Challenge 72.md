# Pailwater darts tournament

## Your task

Two players each take three turns. Each entered score is the total for one three-dart turn, not one individual dart. Use loops to find both totals, then announce the winner or a draw.

## What to enter

Six whole-number turn scores from 0 to 180: all three scores for player one, then all three for player two. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `Player one scored: t1`, then `Player two scored: t2`, then `Player one wins!!`, `Player two wins!!` or `It is a draw.` Each message is on its own line.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **A running total — add each new amount to what is already stored.** Start it at zero before the loop. `total = total + amount` updates it without losing the earlier amounts.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    Keep separate totals for the two players. Do not compare their scores until all turns have been entered.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Read the lesson on fixed-count loops](https://snakify.org/lessons/for_loop_range/)
- [Work through the lesson one small step at a time](https://snakify.org/lessons/for_loop_range/steps/1/)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 72: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 72: test runs</caption>
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
        <td><code>34</code><br><code>60</code><br><code>100</code><br><code>45</code><br><code>36</code><br><code>24</code></td>
        <td><code>Player one scored: 194</code><br><code>Player two scored: 105</code><br><code>Player one wins!!</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>10</code><br><code>20</code><br><code>30</code><br><code>30</code><br><code>20</code><br><code>10</code></td>
        <td><code>Player one scored: 60</code><br><code>Player two scored: 60</code><br><code>It is a draw.</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>0</code><br><code>0</code><br><code>0</code><br><code>1</code><br><code>2</code><br><code>3</code></td>
        <td><code>Player one scored: 0</code><br><code>Player two scored: 6</code><br><code>Player two wins!!</code></td>
      </tr>
    </tbody>
  </table>
</div>
