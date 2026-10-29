# Previous and next numbers

## Your task

Write a Python program for this task.

Report the whole numbers immediately after and before an entered whole number.

## What to enter

One whole number; negative numbers and zero are allowed. Type each number on a new line, pressing Enter after each one.

## What your program should show

Two lines in this order: `The next number for the number N is NEXT` and `The previous number for the number N is PREVIOUS`. Replace the placeholders with correct numbers; do not add punctuation.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`+` — add numbers.** For example, `8 + 4` gives `12`. Make sure the values are numbers: joining text works differently.
- **`-` — subtract one number from another.** For example, `9 - 4` gives `5`. The order of the numbers matters.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    Mark the entered number on a number line. Which number is immediately before it, and which is immediately after it? Check the order of the two sentences the task asks you to display.

## Need a hand?

If you are stuck, try one of these help pages, then come back to your program.

- [Read the lesson on entering information and showing results](https://snakify.org/lessons/print_input_numbers/)
- [Work through the same lesson one small step at a time](https://snakify.org/lessons/print_input_numbers/steps/1/)

If you are still unsure, ask your teacher to help you understand the task.


## Try your program

Use the tests below to check your program. You do not need to make up your own numbers.

1. Run your program.
2. Type the values in the middle column, one at a time. Press Enter after each line.
3. Compare your result with the last column. It should match.
4. If it matches, tick that test in your workbook. If it does not, check your code and try again.
5. Run your program again for the next test.

Where a table cell has several lines, keep the same line breaks when typing or comparing the result.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 12: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 12: test runs</caption>
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
        <td><code>179</code></td>
        <td><code>The next number for the number 179 is 180</code><br><code>The previous number for the number 179 is 178</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>0</code></td>
        <td><code>The next number for the number 0 is 1</code><br><code>The previous number for the number 0 is -1</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>1234</code></td>
        <td><code>The next number for the number 1234 is 1235</code><br><code>The previous number for the number 1234 is 1233</code></td>
      </tr>
    </tbody>
  </table>
</div>
