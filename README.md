# Tic-Tac-Toe-Bot

play_tictactoe.py is given to run GUI using pygame for playing Tic-Tac-Toe on board 

Built the logic in strategies.py using minimax algorithm and stored the ideal play strategies for both "x" and "o" in policy_x.json and policy_o.json .

To run the game and play with any one of bot "x" or "o" use commands:-
Bot as "x":-(use python if python3 not working)
  python3 play_tictactoe.py --BotPlayer x --BotStrategyFile policy_x.json 
Bot as "o":-
  python3 play_tictactoe.py --BotPlayer o --BotStrategyFile policy_o.json
