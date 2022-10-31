# CS50's Introduction to Computer Science
## HarvardX - CS50x
### Week 2 Problem Set - Mario.c/More
<hr>


### Assignment and Requirements:
Write and execute the program that recreates Nintendo’s Super Mario Brothers' pyramids in C, using hashes (#) for bricks.\
Program should allow the user to decide how tall the pyramids should be by prompting them for a positive integer between 1 and 8, inclusive.\
\
Here’s how the program might work if the user inputs 8 when prompted:

```C
$ ./mario
Height: 8
       #  #
      ##  ##
     ###  ###
    ####  ####
   #####  #####
  ######  ######
 #######  #######
########  ########
```
\

If the user doesn’t input a positive integer between 1 and 8, inclusive, when prompted, the program should re-prompt the user until they cooperate:

```C
$ ./mario
Height: -1
Height: 0
Height: 42
Height: 50
Height: 4
   #  #
  ##  ##
 ###  ###
####  ####
```
