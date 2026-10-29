# Who is going?

## Your task

Store the ten guest names below in a list. Read whether each person is attending and store the answers as True or False in a matching list. After all answers are entered, display only the people who are going.

## What to enter

Ten capital-letter responses, Y or N, in this guest order: Mellisa, Evelyn, Emmy, Karen, Margaret, Norma, Agnes, Billy, Robert, Arthur. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `Party List:` then the names of those attending on separate lines, preserving guest order. If no one is attending, show `No guests are attending.` after the heading.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **Lists — store several related values together.** For example, `colours = ["red", "blue"]` stores two text values in order. In these tasks, a Python list is used as an array.
- **`.append()` — add one value to a list.** `colours.append("green")` adds a new item at the end. Start with `[]` if the list is empty.
- **`True` and `False` — store yes/no information.** A comparison such as `answer == "Y"` produces one of these Boolean values. The non-empty text `"N"` is not automatically False.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **`len()` — count items or characters.** `len("Hello")` is `5`; for a list it counts the stored items. Spaces count as characters in text.
- **Square brackets — read a stored position.** For example, `colours[0]` reads the first item. Python list positions start at zero, not one.
- **`if` — do something only when a check is true.** End the heading with a colon and indent the action underneath it. If the check is false, that action is skipped.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.

## Hint

??? tip "Show a hint"

    A guest's name and attendance answer must share the same position. Converting text directly with bool does not distinguish Y from N; compare the response instead.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Read the lesson on storing values in lists](https://snakify.org/lessons/lists/)
- [Work through the lesson one small step at a time](https://snakify.org/lessons/lists/steps/1/)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 89: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 89: test runs</caption>
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
        <td><code>Y</code><br><code>Y</code><br><code>N</code><br><code>N</code><br><code>Y</code><br><code>Y</code><br><code>N</code><br><code>Y</code><br><code>N</code><br><code>Y</code></td>
        <td><code>Party List:</code><br><code>Mellisa</code><br><code>Evelyn</code><br><code>Margaret</code><br><code>Norma</code><br><code>Billy</code><br><code>Arthur</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>N</code><br><code>N</code><br><code>N</code><br><code>N</code><br><code>N</code><br><code>N</code><br><code>N</code><br><code>N</code><br><code>N</code><br><code>N</code></td>
        <td><code>Party List:</code><br><code>No guests are attending.</code></td>
      </tr>
    </tbody>
  </table>
</div>
