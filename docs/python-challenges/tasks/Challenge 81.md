# Average temperature: check each reading

## Your task

Read seven accepted temperatures. Reject readings below -40°C or above 55°C and ask again for the same day. Calculate the mean and round it to the nearest whole degree using Python's round function.

## What to enter

Numeric temperature attempts, in day order. A rejected attempt does not count as one of the seven readings. Values at -40 and 55 are accepted. Type each value on a separate line, pressing Enter after each one.

## What your program should show

For each rejected reading show `Please enter a temperature between -40 and 55.` Finally show `This week's average, rounded to 0 decimal places was:` then the rounded average followed by ` degrees centigrade`. For an exact half, use Python's round-to-even rule.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`float()` — turn text into a number that can have a decimal part.** For example, `float("2.5")` gives the number `2.5`.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **`while` — repeat while a check stays true.** Use a colon and an indented block. Make sure something checked by the loop can change, such as reading a new attempt.
- **`or` — allow either check to be true.** For example, `choice == "A" or choice == "B"` accepts either of those letters.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **A running total — add each new amount to what is already stored.** Start it at zero before the loop. `total = total + amount` updates it without losing the earlier amounts.
- **`/` — divide, keeping the decimal part.** For example, `7 / 2` gives `3.5`.
- **`round()` — round a number.** `round(3.7)` gives `4`. With no second argument it returns a whole number. An exact half goes to the nearest even whole number, so `round(2.5)` is `2` and `round(3.5)` is `4`.

## Hint

??? tip "Show a hint"

    Put the retry inside the seven-day loop. Do not add rejected readings to the total, and round only after calculating the average.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 81: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 81: test runs</caption>
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
        <td><code>12</code><br><code>14</code><br><code>7</code><br><code>95</code><br><code>6</code><br><code>7</code><br><code>11</code><br><code>11</code></td>
        <td><code>Please enter a temperature between -40 and 55.</code><br><code>This week&#x27;s average, rounded to 0 decimal places was:</code><br><code>10 degrees centigrade</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>-40</code><br><code>55</code><br><code>0</code><br><code>0</code><br><code>0</code><br><code>0</code><br><code>-1</code></td>
        <td><code>This week&#x27;s average, rounded to 0 decimal places was:</code><br><code>2 degrees centigrade</code></td>
      </tr>
    </tbody>
  </table>
</div>
