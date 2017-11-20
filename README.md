# Moving-Computer

Moving Computer

Description

Assurance Company of Moving (ACM) is a company of moving things for people. Recently, some schools want to move their computers to another place. So they ask ACM to help them. One school reserves K trucks for moving, and it has N computers to move. In order not to waste the trucks, the school ask ACM to use all the trucks. That is to say, there must be some computers in each truck, and there are no empty trucks. ACM wants to know how many partition shemes exists with moving N computers by K trucks, the ACM ask you to compute the number of different shemes with given N and K. 
You needn't care with the order. For example N=7,K=3, the the following 3 partition instances are regarded as the same one and should be counted as one sheme. 
1 1 5 
1 5 1 
5 1 1 

Each truck can carry 200 computers at most. 

Input

Each line of the input contains two postisive integer N (1<=N<=200) and K(1<=K<=N).Input is terminated by a line with N=K=0.

Output

For each line, output the number of different partition sheme . The result may be larger than 2^32, so you should care with the precision.

Sample Input

1 1
7 3
0 0

Sample Output

1
4

Hint

The four partition shemes of the second sample are: 
1 1 5 
1 2 4 
1 3 3 
2 2 3 
