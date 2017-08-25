# lamports-tic-tac-toe
An online game of tic tac toe that is hosted over Google Sheets, illustrating concepts about Lamport Clocks.

## how to host / join a game
Both players do the same thing to start a game -- replace the Google API client ID and Google Sheets spreadsheet ID in both of their versions of the html files. Next, both players should open terminal, navigate to the directory where the html file resides, and begin a simple HTTP server using Python by typing in the following command: `python -m SimpleHTTPServer 8000`. Next, both players should open the html file, and the game will begin automatically.
NOTE: Upon ending a gaming session, the http server should be ended, especially if more games are planned to take place. Do so by simply searching for the port number of the current http server (the second-to-left-most number after typing in the command `ps -fA | grep python`) and then killing this port number, using the command `kill [second-to-left most number goes here.]`.
