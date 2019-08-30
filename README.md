# "Paper - Rock - Scissors Game" using function, if, else and elif.
###################################################################

'''

** Game Description **
------------------------------------------------------------------
- Ask for player plays (using input), 
- Compare them with the random computer input, 
- Print out message of congratulations to the winner, and
- Ask if the players want to start a new game.
-------------------------------------------------------------------

** Game rules**
-------------------------------------------------------------------
Paper    beats  Rock     : Paper wins because paper covers rock.
Paper    beats  Scissors : Scissors win because scissors cut paper.
Scissors beats  Rock     : Rock wins because rock smashes scissors.
Everything else is a tie.
-------------------------------------------------------------------

** Game probabilities **
------------------------------------
p | p = p --> Tie, please try again.
r | r = r --> Tie, please try again.
s | s = s --> Tie, please try again.
----------------------------------------------------------------
p | r = p --> You win, paper covers rock, Good job!
p | S = s --> Computer win, scissors cut paper!
----------------------------------------------------------------
r | p = p --> Computer win, paper covers rock!
r | s = r --> You win, rock smashes scissors, Good job!
----------------------------------------------------------------
s | p = s --> You win, scissors cut paper, Good job!
s | r = r --> Computer win, rock smashes scissors!
----------------------------------------------------------------

-- >   if the player enter wrong choice or any number else like "3, 5 or 100 ..etc."  
       this msg'll be printed --> "Wrong Choice, please try again."
       
'''

