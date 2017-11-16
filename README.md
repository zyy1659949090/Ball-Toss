# Ball-Toss

Ball Toss

Description

Classmates stand in a circle facing inward, each with the direction left or right in mind. One of the students has a ball and begins by tossing it to another student. (It doesn't really matter which one.)When one catches the ball and is thinking left, she throws it back across the circle one place to the left (from her perspective) of the person who threw her the ball. Then she switches from thinking left to thinking right. Similarly, if she is thinking right, she throws the ball to the right of the person who threw it to her and then switches from thinking right to thinking left.

There are two exceptions to this rule: If one catches the ball from the classmate to her immediate left and is also thinking left, she passes the ball to the classmate to her immediate right, and then switches to thinking right. Similarly, if she gets the ball from the classmate to her immediate right and is thinking right, she passes the ball to the classmate to her immediate left, and then switches to thinking left.(Note that these rules are given to avoid the problem of tossing the ball to oneself.)

No matter what the initial pattern of left and right thinking is and who first gets tossed the ball,everyone will get tossed the ball eventually! In this problem, you will figure out how long it takes.

You'll be given the initial directions of n classmates (numbered clockwise), and the classmate to whom classmate 1 initially tosses the ball. (Classmate 1 will always have the ball initially.)

Input

There will be multiple problem instances. Each problem instance will be of the form

n k t1 t2 t3 . . . tn

where n (2 <= n <= 30) is the number of classmates, numbered 1 through n clockwise around the circle,k (> 1) is the classmate to whom classmate 1 initially tosses the ball, and ti (i = 1, 2, . . . , n) are eacheither L or R, indicating the initial direction thought by classmate i. (n = 0 indicates end of input.)

Output

For each problem instance, you should generate one line of output of the form:

Classmate m got the ball last after t tosses.

where m and t are for you to determine. You may assume that t will be no larger than 100,000.
Note that classmate number 1 initially has the ball and tosses it to classmate k. Thus, number 1 has not yet been tossed the ball and so does not switch the direction he is thinking.

Sample Input

4 2 L L L L
4 3 R L L R
10 4 R R L R L L R R L R
0

Sample Output

Classmate 3 got the ball last after 4 tosses.
Classmate 2 got the ball last after 4 tosses.
Classmate 9 got the ball last after 69 tosses.
