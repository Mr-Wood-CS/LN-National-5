# Name switch pattern

## Your task

Read a first name and surname. Use a loop to display three pairs of pattern lines, giving six lines altogether.

## What to enter

First name, then surname, as text. Type each value on a separate line, pressing Enter after each one.

## What your program should show

The first line of each pair is `first surname first surname`; the second is `surname first surname first`. Replace the placeholders with the entered names and separate names with one space.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **Text and `+` — join pieces of writing.** Text goes inside quotation marks. For example, `"Good" + " morning"` gives `Good morning`. Spaces must be included where you want them.

## Hint

??? tip "Show a hint"

    Treat the pattern as a pair of different lines. How many times does that whole pair need to repeat?

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 67: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 67: test runs</caption>
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
        <td><code>Bob</code><br><code>Tomlinson</code></td>
        <td><code>Bob Tomlinson Bob Tomlinson</code><br><code>Tomlinson Bob Tomlinson Bob</code><br><code>Bob Tomlinson Bob Tomlinson</code><br><code>Tomlinson Bob Tomlinson Bob</code><br><code>Bob Tomlinson Bob Tomlinson</code><br><code>Tomlinson Bob Tomlinson Bob</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>Jo</code><br><code>Li</code></td>
        <td><code>Jo Li Jo Li</code><br><code>Li Jo Li Jo</code><br><code>Jo Li Jo Li</code><br><code>Li Jo Li Jo</code><br><code>Jo Li Jo Li</code><br><code>Li Jo Li Jo</code></td>
      </tr>
    </tbody>
  </table>
</div>
