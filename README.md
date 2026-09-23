# TickTackToe
TickTackToe for FSAB

Overview: My project runs TickTackToe using JavaScript and can be run using Node.js.

How to run it: Install Node.js dependencies with "npm install," then run "npm start"

Your contribution: My modification was the function where when someone wins, highlight the three squares that caused the win. Or, when no one wins, displaying a message about the result being a draw.

What you learned: One challenge I encountered was with the modification I made and how the calculateWinner function only who won instead of giving me the squares that were used to win. It was hard finding out how to make it so that which cases resulted in wins and how to know which case was used to win. I approached this problem by modifying the original calculateWinner(squares) function that showed the eight possible methods of winning. So, I checked which of these possible arrays of winning fit in a case to determine the threes squares used to win, and I returned a draw if it didn't fit any of these eight arrays.

References: (https://react.dev/learn/tutorial-tic-tac-toe) The tutorial provided by FSAB was very heavily referenced for making this project.