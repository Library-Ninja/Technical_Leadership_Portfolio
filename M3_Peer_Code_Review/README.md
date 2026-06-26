# M3: Peer Code Review

*Formally review code submitted by a peer.*

**Target Skills: Code Review, Feedback Delivery**

## Task

Submit a review of a peer’s code by using GitHub’s review interface to leave inline comments. Also add a summary of what worked well in the code and areas to prioritize in the future.

## Process

For this review, I learned about a helpful framework for delivering feedback that is meaningful, direct, and kind. This practice gave me experience reviewing the code instead of the coder, asking guiding questions, and prioritizing the most important bugs rather than nitpicking small issues the author is likely to fix themselves. The “I noticed,” “I wonder,” “I would try” framework helps feedback stay helpful, relevant, and kind, leading to efficient problem solving.

## Deliverable

[Code Review (GitHub)](https://github.com/booknut123/study_tracker/pull/1)

Screenshots showing review comments:

![Review Summary: I am so impressed by this program! I really enjoyed reading through it and I think it was a great idea to practice by making a program that many people would find really relevant! I found that the README and comments were detailed and super helpful for understanding the purpose of the program and functions, and I also noticed that the input validation was really strong throughout the program. Something I might prioritize for reducing repetition in future expansion is creating helper functions when needed, and considering whether it would be worthwhile to return a value for certain functions rather than printing a formatted string, particularly for functions whose values might be needed elsewhere in the program (more details in code review). I am curious how you plan to use this program in the future and its scale because it might impact data persistence and hydration in future implementation.](image.png)

![Line 101 Comment: I see that each function prints out the relevant piece of information properly formatted. I also notice that in average_study_time(), the calculation of total_minutes is the same as the implementation of the total_study_time() function. In order to reduce repetition, I wonder if there is a way to take advantage of the total_study_time() result whenever that value is needed in the rest of the program? For example, maybe total_study_time() could be modified to return the total value instead of printing the result and that function could be called whenever the total number of minutes is required? I realize that changing the structure of this function would require moving the printing and formatting to main() for this and possibly other functions, so it might be important to consider whether this change would be worth it in your plans for expanding.](image%201.png)

![Line 120 Comment: I notice there are multiple times in the program where there is a loop to display the information about each session. I am wondering if it would be beneficial for future additions to create a helper function that prints all sessions formatted in the intended way, that can be called whenever all sessions need to be printed out? I believe this would be helpful if more properties are ever added to each session because only the new print function would need to be updated.](image%202.png)

![Line 70 Comment: I notice that one of the future goals for the program is saving sessions to a file. I think this is a great idea! I’ve done a project in Java that similarly saves information to a text file and restores it. I might create two new functions. One for writing data about each session to a file and printing out the name of the created file to the user. The other for reading such a file, which would update the sessions variable with the information found in the file associated with the user-inputted file name. I have not done this process in Python yet, so I am sure there will be more considerations about specific implementation here, but hopefully the overall structure can be helpful!](image%203.png)

## Reflection

What was the hardest feedback to write? What would you change if you did it again? 

This code review gave me experience leaving thoughtful and meaningful comments on real code. This was a difficult program to review because it was very organized, clean, and logical. I found that my meaningful suggestions were related to making the program more efficient for future expansion. The most difficult feedback was related to the author’s plans for saving sessions to a file because I have not worked through the problem in that language before. If I were to do this review again, I would like to spend even more time working with the code so that I could provide specific implementation suggestions in addition to broad patterns.