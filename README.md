# JeopardyBoard
I took the standard (intern-developed, half-assed) Jeopardy board template from JeopardyLabs.com and made some improvements.

My nine-year-old son had to do a Jeopardy board for his math class.  Since the online templates available only had five columns, students using the template were required to submit supplemental cards for a sixth column.  Since I'm an unrepentant computer nerd, I found the situation unacceptable and decided to make improvements to the template.

* A sixth column was added to make it the same width as the board on TV

* An object was created at the top of the JavaScript &lt;script&gt; section to hold the clues and responses.  This makes it easier for someone to modify than going into the HTML for the board's &lt;table&gt; element

* A clue's score can only be applied ONCE (either adding or taking away).  The old template allowed a score to be added and subtracted to any or all teams.

* A clue's cell is blank after the clue has been used.  The clue will not show up again.  This is the same as the game on TV

* The Daily Double's position is randomly determined.  It will be somewhere in the bottom three rows of the board.

* The team can decide how much they want to wager on the daily double - in accordance to the rules of the game on TV.

Reading the original template, it is obvious that it was developed by at least two different interns (or teams of interns), and then not improved any more than that.
