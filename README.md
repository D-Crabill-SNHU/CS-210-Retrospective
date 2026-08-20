>Summarize the project and what problem it was solving.
The first project was based around a program simulating the functionality of a clock. The user would enter a time in hours, minutes, and seconds
which would then be set. The user would be presented with two clock models, one in standard time and the other in military time. The user would
be allowed to increment the hours, minutes, and seconds as desired, and the options would loop until the user voluntarily quit. Keeping track of
time is essential for people to function in their day to day lives, and this program mirrors some of the functionality that would go into a
>program centered around tracking time such as an alarm clock.


>What did you do particularly well?
I think one thing that I did well was ensuring that the program was properly modularized. Breaking a program down into smaller pieces helps
not just with readability but also with isolating problems. One large function would make it more difficult to parse areas for problems, but
having separate regions of code can help more effectively track down errors. The same principle for debugging can apply to maintaining or
expanding the code. Rather than having to modify an entire function for a few minor changes, disparate functions allows for easier
implementation and testing of changes.


>Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
I think that one area for improvement is with input verification. Adding a try catch block when a integer is to be entered by the user
would prevent problems with incorrect submissions and improve program reliability.


>Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your
  support network?
While the project didn't cause too much trouble, one process that required particular notes were the loops, especially when cycling through
vectors. Because of their iterative nature, they are more abstract than other operations and thus require more consideration. Ensuring that
loops terminated at the end of the relevant vectors without falling short or going over required thought as to the exact number of loops to
be entered.


>What skills from this project will be particularly transferable to other projects or course work?
While the general practice is always helpful for coding going forward, I think that one key area is with user interaction loops. I can sometimes
get tripped up with ensuring the interactions with users can get jumbled, notably forgetting to clear the scanner when necessary. Building on
my understanding now will help build the reliability of my skills for the future.


>How did you make this program maintainable, readable, and adaptable?
Through a combination of modularity and in-code comments, along with recognizable variable/function names should help a programmer assessing the
code understand what does what and how the code flows. 
