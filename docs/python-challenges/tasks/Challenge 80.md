# Pailwater darts: check each score

## Your task

Extend Pailwater darts tournament so an invalid turn score is rejected and entered again. Each accepted score must be from 0 through 180. Accept three turns for each player.

## What to enter

Scores for player one followed by player two. Invalid attempts do not count as turns; enter another score for the same turn. All inputs are whole numbers. Type each value on a separate line, pressing Enter after each one.

## What your program should show

For each invalid score show `Invalid score! Enter again please:`. After six accepted turns, show the totals and winner using the same three-line format as Pailwater darts tournament.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **`while` — repeat while a check stays true.** Use a colon and an indented block. Make sure something checked by the loop can change, such as reading a new attempt.
- **`or` — allow either check to be true.** For example, `choice == "A" or choice == "B"` accepts either of those letters.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **A running total — add each new amount to what is already stored.** Start it at zero before the loop. `total = total + amount` updates it without losing the earlier amounts.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.

## Hint

??? tip "Show a hint"

    The retry belongs inside the turn loop. Add a score to the total only after it passes the check.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 80: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 80: test runs</caption>
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
        <td><code>34</code><br><code>204</code><br><code>60</code><br><code>100</code><br><code>45</code><br><code>36</code><br><code>24</code></td>
        <td><code>Invalid score! Enter again please:</code><br><code>Player one scored: 194</code><br><code>Player two scored: 105</code><br><code>Player one wins!!</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>-1</code><br><code>0</code><br><code>0</code><br><code>0</code><br><code>180</code><br><code>180</code><br><code>180</code></td>
        <td><code>Invalid score! Enter again please:</code><br><code>Player one scored: 0</code><br><code>Player two scored: 540</code><br><code>Player two wins!!</code></td>
      </tr>
    </tbody>
  </table>
</div>
