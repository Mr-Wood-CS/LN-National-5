# Next calendar day

## Your task

Write a Python program for this task.

Find the day after a valid date in 2017. January, March, May, July, August, October and December have 31 days; April, June, September and November have 30; February has 28. After 31 December comes 1 January of the following year.

## What to enter

Two whole numbers: month (1–12), then day. The date is guaranteed valid in 2017. Type each number on a new line, pressing Enter after each one.

## What your program should show

Next date's month number on the first line and day number on the second line. Do not display the year.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.
- **`or` — allow either check to be true.** For example, `choice == "A" or choice == "B"` accepts either of those letters.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **`+` — add numbers.** For example, `8 + 4` gives `12`. Make sure the values are numbers: joining text works differently.

## Hint

??? tip "Show a hint"

    Most dates stay in the same month when you move forward a day. Think separately about the last day of a month and the last day of the year. The earlier days-in-a-month challenge may help you plan.

## Need a hand?

If you are stuck, try one of these help pages, then come back to your program.

- [Read the lesson on making decisions with if, elif and else](https://snakify.org/lessons/if_then_else_conditions/)
- [Work through the same lesson one small step at a time](https://snakify.org/lessons/if_then_else_conditions/steps/1/)

If you are still unsure, ask your teacher to help you understand the task.


## Try your program

Use the tests below to check your program. You do not need to make up your own numbers.

1. Run your program.
2. Type the values in the middle column, one at a time. Press Enter after each line.
3. Compare your result with the last column. It should match.
4. If it matches, tick that test in your workbook. If it does not, check your code and try again.
5. Run your program again for the next test.

Where a table cell has several lines, keep the same line breaks when typing or comparing the result.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 60: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 60: test runs</caption>
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
        <td><code>3</code><br><code>30</code></td>
        <td><code>3</code><br><code>31</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>3</code><br><code>31</code></td>
        <td><code>4</code><br><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>5</code><br><code>15</code></td>
        <td><code>5</code><br><code>16</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>7</code><br><code>22</code></td>
        <td><code>7</code><br><code>23</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>2</code><br><code>8</code></td>
        <td><code>2</code><br><code>9</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>1</code><br><code>30</code></td>
        <td><code>1</code><br><code>31</code></td>
      </tr>
      <tr>
        <th scope="row">7</th>
        <td><code>1</code><br><code>31</code></td>
        <td><code>2</code><br><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">8</th>
        <td><code>2</code><br><code>27</code></td>
        <td><code>2</code><br><code>28</code></td>
      </tr>
      <tr>
        <th scope="row">9</th>
        <td><code>2</code><br><code>28</code></td>
        <td><code>3</code><br><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">10</th>
        <td><code>3</code><br><code>1</code></td>
        <td><code>3</code><br><code>2</code></td>
      </tr>
      <tr>
        <th scope="row">11</th>
        <td><code>4</code><br><code>29</code></td>
        <td><code>4</code><br><code>30</code></td>
      </tr>
      <tr>
        <th scope="row">12</th>
        <td><code>4</code><br><code>30</code></td>
        <td><code>5</code><br><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">13</th>
        <td><code>5</code><br><code>30</code></td>
        <td><code>5</code><br><code>31</code></td>
      </tr>
      <tr>
        <th scope="row">14</th>
        <td><code>5</code><br><code>31</code></td>
        <td><code>6</code><br><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">15</th>
        <td><code>6</code><br><code>29</code></td>
        <td><code>6</code><br><code>30</code></td>
      </tr>
      <tr>
        <th scope="row">16</th>
        <td><code>6</code><br><code>30</code></td>
        <td><code>7</code><br><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">17</th>
        <td><code>7</code><br><code>30</code></td>
        <td><code>7</code><br><code>31</code></td>
      </tr>
      <tr>
        <th scope="row">18</th>
        <td><code>7</code><br><code>31</code></td>
        <td><code>8</code><br><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">19</th>
        <td><code>8</code><br><code>30</code></td>
        <td><code>8</code><br><code>31</code></td>
      </tr>
      <tr>
        <th scope="row">20</th>
        <td><code>8</code><br><code>31</code></td>
        <td><code>9</code><br><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">21</th>
        <td><code>9</code><br><code>29</code></td>
        <td><code>9</code><br><code>30</code></td>
      </tr>
      <tr>
        <th scope="row">22</th>
        <td><code>9</code><br><code>30</code></td>
        <td><code>10</code><br><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">23</th>
        <td><code>10</code><br><code>30</code></td>
        <td><code>10</code><br><code>31</code></td>
      </tr>
      <tr>
        <th scope="row">24</th>
        <td><code>10</code><br><code>31</code></td>
        <td><code>11</code><br><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">25</th>
        <td><code>11</code><br><code>29</code></td>
        <td><code>11</code><br><code>30</code></td>
      </tr>
      <tr>
        <th scope="row">26</th>
        <td><code>11</code><br><code>30</code></td>
        <td><code>12</code><br><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">27</th>
        <td><code>12</code><br><code>30</code></td>
        <td><code>12</code><br><code>31</code></td>
      </tr>
      <tr>
        <th scope="row">28</th>
        <td><code>12</code><br><code>31</code></td>
        <td><code>1</code><br><code>1</code></td>
      </tr>
    </tbody>
  </table>
</div>
