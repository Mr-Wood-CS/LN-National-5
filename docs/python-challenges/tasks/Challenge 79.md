# No more presents

## Your task

You have £200 for presents. Keep accepting positive whole-pound prices and adding them to a running total. Stop as soon as the next price would take the total over £200. Exactly £200 is still allowed.

## What to enter

One positive whole-pound price per line. Eventually a price will take the running total over the limit. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `Limit exceeded.` then `You cannot include the £p present.`, replacing p with the price that first takes the total over £200.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`while` — repeat while a check stays true.** Use a colon and an indented block. Make sure something checked by the loop can change, such as reading a new attempt.
- **A running total — add each new amount to what is already stored.** Start it at zero before the loop. `total = total + amount` updates it without losing the earlier amounts.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    Keep the most recent price as well as the running total. The final message needs that price, rather than the total cost.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 79: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 79: test runs</caption>
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
        <td><code>35</code><br><code>100</code><br><code>50</code><br><code>45</code></td>
        <td><code>Limit exceeded.</code><br><code>You cannot include the £45 present.</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>100</code><br><code>100</code><br><code>1</code></td>
        <td><code>Limit exceeded.</code><br><code>You cannot include the £1 present.</code></td>
      </tr>
    </tbody>
  </table>
</div>
