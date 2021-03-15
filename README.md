1.  How many bugs did you find in the unit testing?  What were they?
	1.  Mostly just the trouble it was to get the 'Size' of bag, I had to make a short method in DiceBag that could use the .size method of ArrayLists.
2.  Did you find any bugs when using the debugger?  What were they?
	1.  In OrderDie.java the 'toString' returns super.toString rather than the variable 'd' which adds the color data.
	2.  Changed player2 color to Purple (so both character's aren't red.)
	3.  private int maxNumDice is not used in Player.java, added check on 'addToken' to not add a token past 'MaxNumDice' which defaults to 20. (Stops crazy overflow on bad method calls.)
	4.  DiceBag has crash/issue when last dice is drawn.
	5.  Player 1 and Player get assigned different numbers of dice in the dicebag.
3.  Provide link to code to your GitHub account.
	1.  https://github.com/TheGam1ngWizard/HW6
4.  Put the fixed code into your GitHub account.
	1.  Yes
5.  Are there any unit tests that could have found the bugs you found in the debugger?  Describe one of those tests.
	1.  Make sure the right number of players are initilized each with their own set of dice.
6.  Propose 1 extra credit question for the exam.
	1.  Describe how JunitTesting can help identify issues in your code.

Self Assessment (worth 1 point):

Answer the following:

1,) **Evaluate the outcomes of your week-long work committed to the assignment.** Functionally resolved the code to work with multipul Jtests and send testcases to other classes. I think I have a general understanding of JunitTesting and how to evaluate (and write) code that can utilize them.

2.) **Describe how collaboration and communication with peers, team members (if work was done in teams or pairs), and instructor affected the outcomes of your work.** Worked with Eric, Elijah, and Carlo for ideas and some direction on what to try once I got stuck.

3.) **How many hours did you spend on the assignment?**  _A fuzzy characterization, such as “a lot” or “not so much” is not OK. A number is absolutely required._ About 12-14 hours, i got stuck with the direction to go with the initial question (and J testing it)

4.)  **What challenges did you face with this assignment’s activities and how did you address them?**   _“No challenge” or “nothing to say” is not ok. If there are no challenges to report on, then describe what required most of your attention or time and why._ The hardest part of this assignment was the first question with the fuzzier string/response output. It was hard then expected to initially wrap my head around what I needed to code to get it working.

5.)  **What lessons have you learned from this assignment’s activities?**  _“No lesson” is not OK. There must be outcomes from your learning that you can use on an interview or can help on an IT project,_ _for example. What are they?_ I learned how to write Jtests and Evaluate code to see what I need to do to setup for testing.

6.)  **Did your assignment earn 1, 2 or 3 points?**  _"Not graded yet." or "I don't know" are not acceptable.  Evaluate your homework assignment as if you had to assign credit._
3, as I completed all the requirements and even went ahead with most of the bugfixes required for the graduate level of this course.