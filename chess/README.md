# GA_Chess_AI



2022/08/18

15:00-15:05: basic research

Choices made:

Language: Python External tool: tensorflow

15:05-17:18: fucking installing all the bullshit that is tensorflow + dependencies while trying to troubleshoot the absolutely archaic prompts and guides i have to follow

17:25-17:58: figure out how to get graphics to display in python. Pygame vs Graphics.py

2022/08/21

13:15-14:45: successfully create chessboard in python using pygame.

14:45-15:35: import transparent chess pieces

15:35-15:42: fen vs pgn

2022/09/23

15:55-16:29

PAIN PAIN PAIN PAIN

CURSOR DOES NOT FOLLOW PLAYER MOUSE POSITION

PAIN PAIN PAIN

2022/10/14

ca 2 hours

rewrite all previous code in js

2022/10/19

ca 1.5 hours

try to figure out how phaser and importing phaser works

2022/11/06

17:58 - 21:32

figuring out how phaser works

go through the tutorial

define board, loading images, importing assets

2022/11/10

16:21-18:06

desperately try to figure out how to use the classes mentioned, no major success

2022/12/4

ca 4 hours
give up, restart everything from scratch, successfully import (after spending 4 hours troubleshooting and crying) the rules for chess.

09/12/2022 -> 10/12/2022 

21:10ish -> 01:57

get chessboard and images to work, collaborate chesssboard and chess rules, implement into coherent package. Currently: chess works, with rules implemented, but no AI integration.

TODO: ai integration / evaluate function


ca 01:00 to 7:06

evaluate time it takes for total move at depth.

17:00 to 21:22

rewrite chess.js API functions to prevent string conversions during move function


OLD times:

D1: 20 positions @ 0.010999917984008789 seconds

D2: 400 positions @ 0.1099998950958252 seconds

D3: 8902 positions @ 2.921999931335449 seconds

D4: 197281 positions @ 66.81599998474121 seconds

D5: 4865609 positions @ 384.95700001716614 seconds


New Times:

D1: 20 positions @ 0.004000186920166016 seconds

D2: 400 positions @ 0.031999826431274414 seconds

D3: 8902 positions @ 0.693000078201294 seconds

D4: 197281 positions @ 15.08299994468689 seconds

D5: 4865609 positions @ 2027.7460000514984 seconds


https://en.wikipedia.org/wiki/Shannon_number

position count correct

07/01/2023
06:42-07:21

gave myself 0.5 sec to count pieces

pre optimization counted pieces: 2 000

post optimization counted pieces: 1 250 000

optimization base: use better native JS functions and skip redundant calculations


25/03/2023

21:17-03:49

Reworking the algorithm to properly use negamax

18:30ish-00:21 (1 hr food break somewhere inbetween)

realising that the negamax function was not properly working, fixing it and then implementing the alpha-beta pruning

new times:

d1
it took a total of 0.009999990463256836 seconds

d2
it took a total of 0.029000043869018555 seconds

d3
it took a total of 0.1640000343322754 seconds

d4
it took a total of 0.47699999809265137 seconds

d5
it took a total of 4.466000080108643 seconds

d6
it took a total of 13.740000009536743 seconds


30/03/2023

17:20-00:44

writing report

31/03/2023

16:30-00:26

writing the rest of the report