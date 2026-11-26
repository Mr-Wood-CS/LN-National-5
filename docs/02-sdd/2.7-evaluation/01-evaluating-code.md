# Evaluating a Program

!!! info "What you need to know"

    Evaluate a solution for fitness for purpose, robustness, efficient use of coding constructs and readability. Support each judgement with evidence from tests or from the code.

Testing records what the program does. **Evaluation** uses that evidence to judge whether the result meets a requirement or shows a strength or weakness in the solution.

## Fitness for purpose

Compare the program's behaviour with its stated requirements. Start with the requirement, then give a specific test input and explain how the actual result compares with the expected result.

| Requirement | Test evidence | Judgement |
| --- | --- | --- |
| Accept whole-number scores from 0 to 20 inclusive. | The program accepts `0` but rejects `20`. | It fails the requirement because `20` is a valid score. |
| Display the total of five scores. | Entering `1`, `2`, `3`, `4` and `5` displays `15`. | The total is correct for these inputs. The score-entry requirement still fails at the upper boundary. |

!!! example "Evidence-based evaluation"

    The program fails the score-entry requirement because it rejects 20, even though the specified range includes it. The upper-bound comparison should include 20.

## Robustness

Robustness is how well the program handles invalid inputs or other unexpected situations. Use [exceptional test data](../2.5-testing/01.md) to check whether the program responds appropriately and can continue.

| Exceptional input | Observed behaviour | What it shows |
| --- | --- | --- |
| `21` | The program displays an error and asks for another score. | It handles a whole number above the valid range. |
| `hello` | The program raises a `ValueError` when it tries to convert the input with `int()`. | It cannot recover from text entered in the score field. |

A range check only runs once the input has been converted successfully. In this example, handling text input would require the program to detect or handle a failed conversion and ask again. The two test results support separate judgements about the same program.

## Evidence from the source code

Testing tells you what users experience. Reading the source code lets you assess whether constructs fit the task and whether another programmer can follow the solution. For example, five identical input operations are a candidate for a fixed loop, and an identifier such as `total_score` helps the reader understand what is being accumulated. [Evaluating Code Quality](02-evaluating-code-quality.md)

[National 5 Computing Science course specification, page 5](https://www.sqa.org.uk/sqa/files_ccc/n5-course-spec-computing-science.pdf#page=6)
