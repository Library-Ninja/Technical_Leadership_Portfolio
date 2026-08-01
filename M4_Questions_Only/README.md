# M4: Questions Only

*Help a friend debug a problem by only asking questions.*

**Target Skills: Constructive Inquiry, Verbal Precision, Accessible Communication**

07/12/26

## Task

During a Kode With Klossy camp, I was asked by a scholar to help debug her code. The exercise was in JavaScript, and the error was a syntax error in a couple of console.log() statements. The scholar used curly braces instead of parenthesis surrounding the content to be printed to the console and did not use a semicolon at the end of each line.

## Process

The following guiding questions helped the scholar resolve the issue on her own:

1. What do you think this error message is saying?
2. What do you think those words are trying to tell us about the code? (referring to the vocabulary of the error message)
3. Referring back to the code-along example above the current practice code, do you notice any difference between the console.log() statements?
4. To guide her, I pointed out that the color coding in the IDE looked different between the example and the practice code. What do you think is causing the difference in the color coding of those characters?
5. Before reloading the code, I asked: Walk me through what you think will happen when these lines of code run?

## Deliverable

Below are the responses I received from the scholar after each question was asked:

1. What do you think this error message is saying?
    1. The scholar responded in an unintended way by reading out the exact wording of the error message (unexpected token). I gave some context that a token in this case might represent a character in the code.
2. What do you think those words are trying to tell us about the code? (referring to the vocabulary of the error message)
    1. The scholar responded that there is something unexpected about the character. I extended this thought process by explaining that the code sees a character that it’s not expecting, and there is likely a syntax error or typo somewhere in the code. I then showed her where in the error message to find the character that is causing the error.
3. Referring back to the code-along example above the current practice code, do you notice any difference between the console.log() statements?
    1. The scholar noticed that the semicolons were missing, added the semicolons, and saw that the code still did not work. I congratulated her on solving one of the bugs by validating that adding the semicolons was a necessary step.
4. To guide her, I pointed out that the color coding in the IDE looked different between the example and the practice code. What do you think is causing the difference in the color coding of those characters?
    1. She noticed that the code included curly braces instead of parenthesis and fixed the issue. I confirmed that was a good edit.
5. Before reloading the code, I asked: Walk me through what you think will happen when these lines of code run?
    1. She verified her understanding of string interpolation (the content inside of the console.log() statements) by reading out the correct sentences with the correct variable values inside before seeing the code run successfully.

## Reflection

The question that moved the scholar the furthest was asking them to explain the precise meaning of the error message (question 2) because it not only helped the scholar solve the bug this time, but learn how to read error messages for future debugging. I felt the greatest pull to hand over the answer when I didn’t get the responses I expected from the scholar or only a partial solution (such as questions 1 and 3). It is important to ask a follow up question instead in these cases to give the scholar enough time to understand and discover the solution on their own. Next time, I will choose to validate the scholar's changes after we run the code and test to avoid handing over the answer. I will also improve my responses by not being afraid to ask follow up questions if one of my questions doesn’t get the expected response.
