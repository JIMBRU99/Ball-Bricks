# Ball-Bricks

BALL BRICKS 

While working on this program I found many parts of the questions partially defined ,therfore I made some assumptions which is present in assumption section. Please go through it before running the program.

C++ was used to develop this standalone program.

A C++ and txt file of the program is included within the file.

 

Game rules:

1)Rows and columns of square matrix should be odd and between 3 to 99

2)You cannont input values in first and last two rows and coloumns.

3)First row and column is wall and ground while second one is left blank. 

4)You can enter any number between 1 to 9, which will be the bricks strength.

5)There are three power bricks:

		DS - Breaks surrounding bricks
		
		DE - Breaks all bricks in that row
		
		 B - Extend the base to one directon each time.
		 
6)When a ball hits the brick its strength is decremented by 1.

7)Ball travels down right after hitting a brick so every brick under it is also decremented by one strength.

8)If any power brick is faced while traveling down then the power is activated.

9)If another power brick comes with in a power brick then both power bricks are activated after the ball hits.

		for eg: if ball hits DE and DS is present in same row it means DS is also activated.  
		
10)Ball travels in three directions right daiognal, left daigonal and stright. 

	Keys are:	
	
		ST/st - Straight
		
		LD/ld - Left Daigonal
		
		RD/rd - Right Daigonal
		
11)When ball hits a wall after moving in RD or LD then it goes in opposite direction perpendicular to the wall.

12)If ball hits two walls continuosly then ball count is decremented .

13)Ball is shot from 'o' and is placed at the centre initially.

14)'o' changes its position straight down to the brick it last hits.

15)Ball count is decremented if the ball does not return to 'o'.
0
16)If ball falls to ground then the ball count is decremented by one.

17)Inorder to win you should break all walls before your balls run out.


Assumptions:


1)No of rows and columns are always taken odd since the ball base is always placed centre and is not possible for even number of rows and columns.


2)Second and second last rows are left blank since when ball base extends explanation is not provided after the ball base is adjacent to wall. Moreover second and second last rows are completly avoided in examples given in questions.


3)It is mentioned that the ball travels straight down after it hits any wall, but it is not mentioned whether the ball traveling down will affect the bricks in its path. So I have considered a situation where the ball affects all those bricks on its way down.


4)It is not mentioned that what will happen when a power brick is situated within the range of another power brick, therfore I assumed that these power bricks activate other power brickes within its range (example at rule 9).



SINCE THIS IS A STANDALONE PROGRAM , THIS PROGRAM WILL RUN IN ANY C++ COMPILER



This program is devoloped by Vipinraj K.





