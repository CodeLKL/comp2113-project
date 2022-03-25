# comp2113-project
# COMP2113 Group Project Group 122
# Spinx Game

_Group Number: 122_ <br/>
__Group Member: <br/>
Li Ka Lam (Andy) (3035767499) <br/>
Havin Chung (3035729772)__

## Game rules:
_Login in required and choices are given:_
1) Start new game
2) Load game
3) Leaderboard

> "You need to defeat the Boss monster by answering the questions."

_Boss have 25 HP and every time you answer correctly:_ <br/>
- HP: -5 & Score: +100 points

_Each boss would give you 5 questions based on specific field of study (Time limit: 1.5mins)_
1) Math
2) Comp
3) History
4) Physics

_4 Rounds in total:_

Round 1 -> Town -> Round 2 -> Town -> Round 3 -> Town -> Round 4

_HP system:_
- Start with 20 HP
- Wrong answer or Exceed time limits deduct 5 HP (Score: -20 points)
- If HP get to 0 start from town and redo the round you failed

_Items:_
1) Hints (Keys)
2) Skip question (replace one with another question)
3) Healing potion (Heal 5 HP)
4) Shield (Shield the damage from the boss)

_Every round you have two choices: (need to be done in 1.5 mins)_
1) Answer questions
2) Use item

_Town:_
1) Heal to 20 HP for Free
2) Buy item
3) Save progress

_Rewards:_
1) Well done trophy
2) Score

## File Content:
- cpp file for main menu and main game
- cpp file that contains functions for the game with questions and town part
- cpp file for leaderboard
- txt file save the progress (name, score, round, personal info)
- make file
- header file

## Code Requirement:
1) Random generation: choosing random questions from 20 questions per round
2) Gaming status: save progress in txt file use <fstream>
3) The score and user ID will be stored in leaderboard.cpp and store in linked list
4) Save to txt file, the progress round, no. of items in text, score, players id and pw
5) Three C++ programs, one txt file, one header file and one make file
