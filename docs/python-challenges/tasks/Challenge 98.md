# Scrabble letters

## Your task

Generate seven random upper-case letters A to Z and display each letter with its standard English Scrabble score from the supplied table. Repeated letters are allowed. This exercise chooses letters equally; it does not model a real bag of tiles.

## What to enter

No keyboard input is needed. Generate seven random ASCII codes from 65 to 90 and turn them into letters. 

## What your program should show

Show `Your letters are:` then seven lines in the format `letter - score`, preserving the order generated.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`random.randint()` — choose a random whole number.** Write `import random` first. `random.randint(2, 8)` can return any whole number from 2 through 8, including both ends.
- **`chr()` — turn a character code into a character.** `chr(66)` gives `B`. Upper- and lower-case letters have different codes.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **`in` and `not in` — check membership.** For example, `letter in "ABC"` checks whether the letter is one of those three. These checks work with lists too.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    Generating a letter and finding its score are separate jobs. The score table groups several letters together; check which group contains the current letter.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Random number help](https://docs.python.org/3/library/random.html#random.randint)
- [Character codes, lengths and rounding](https://docs.python.org/3/library/functions.html)


## Data to use

<div class="challenge-table-scroll" role="region" aria-label="Scrabble letters: supplied data" tabindex="0">
  <table class="challenge-table challenge-table--data">
    <caption>Scrabble letters: supplied data</caption>
    <thead>
      <tr>
        <th scope="col">Score</th>
        <th scope="col">Letters</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row">1</th>
        <td>AEILNORSTU</td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td>DG</td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td>BCMP</td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td>FHVWY</td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td>K</td>
      </tr>
      <tr>
        <th scope="row">8</th>
        <td>JX</td>
      </tr>
      <tr>
        <th scope="row">10</th>
        <td>QZ</td>
      </tr>
    </tbody>
  </table>
</div>

## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

For the test table only, temporarily use F, Z, E, S, U, C and H in that order. Restore random selection afterwards. The score table corrects the source example: U is worth 1 and C is worth 3.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 98: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 98: test runs</caption>
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
        <td><em>No input needed</em></td>
        <td><code>Your letters are:</code><br><code>F - 4</code><br><code>Z - 10</code><br><code>E - 1</code><br><code>S - 1</code><br><code>U - 1</code><br><code>C - 3</code><br><code>H - 4</code></td>
      </tr>
    </tbody>
  </table>
</div>
