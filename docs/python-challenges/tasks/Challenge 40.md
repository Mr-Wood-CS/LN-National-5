# Challenge 40: Next calendar day

## Your task

Write a Python program for this task.

Find the day after a valid date in 2017. January, March, May, July, August, October and December have 31 days; April, June, September and November have 30; February has 28. After 31 December comes 1 January of the following year.

## What to enter

Two whole numbers: month (1–12), then day. The date is guaranteed valid in 2017. Type each number on a new line, pressing Enter after each one.

## What your program should show

Next date's month number on the first line and day number on the second line. Do not display the year.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

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

| Test | Type these values<br>one per line | You should see |
| --- | --- | --- |
| 1 | <code>3</code><br><code>30</code> | <code>3</code><br><code>31</code> |
| 2 | <code>3</code><br><code>31</code> | <code>4</code><br><code>1</code> |
| 3 | <code>5</code><br><code>15</code> | <code>5</code><br><code>16</code> |
| 4 | <code>7</code><br><code>22</code> | <code>7</code><br><code>23</code> |
| 5 | <code>2</code><br><code>8</code> | <code>2</code><br><code>9</code> |
| 6 | <code>1</code><br><code>30</code> | <code>1</code><br><code>31</code> |
| 7 | <code>1</code><br><code>31</code> | <code>2</code><br><code>1</code> |
| 8 | <code>2</code><br><code>27</code> | <code>2</code><br><code>28</code> |
| 9 | <code>2</code><br><code>28</code> | <code>3</code><br><code>1</code> |
| 10 | <code>3</code><br><code>1</code> | <code>3</code><br><code>2</code> |
| 11 | <code>4</code><br><code>29</code> | <code>4</code><br><code>30</code> |
| 12 | <code>4</code><br><code>30</code> | <code>5</code><br><code>1</code> |
| 13 | <code>5</code><br><code>30</code> | <code>5</code><br><code>31</code> |
| 14 | <code>5</code><br><code>31</code> | <code>6</code><br><code>1</code> |
| 15 | <code>6</code><br><code>29</code> | <code>6</code><br><code>30</code> |
| 16 | <code>6</code><br><code>30</code> | <code>7</code><br><code>1</code> |
| 17 | <code>7</code><br><code>30</code> | <code>7</code><br><code>31</code> |
| 18 | <code>7</code><br><code>31</code> | <code>8</code><br><code>1</code> |
| 19 | <code>8</code><br><code>30</code> | <code>8</code><br><code>31</code> |
| 20 | <code>8</code><br><code>31</code> | <code>9</code><br><code>1</code> |
| 21 | <code>9</code><br><code>29</code> | <code>9</code><br><code>30</code> |
| 22 | <code>9</code><br><code>30</code> | <code>10</code><br><code>1</code> |
| 23 | <code>10</code><br><code>30</code> | <code>10</code><br><code>31</code> |
| 24 | <code>10</code><br><code>31</code> | <code>11</code><br><code>1</code> |
| 25 | <code>11</code><br><code>29</code> | <code>11</code><br><code>30</code> |
| 26 | <code>11</code><br><code>30</code> | <code>12</code><br><code>1</code> |
| 27 | <code>12</code><br><code>30</code> | <code>12</code><br><code>31</code> |
| 28 | <code>12</code><br><code>31</code> | <code>1</code><br><code>1</code> |
