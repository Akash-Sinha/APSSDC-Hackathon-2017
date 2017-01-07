#Diagonal Difference

Given a square matrix of size , calculate the absolute difference between the sums of its diagonals.

##Input Format

The first line contains a single integer, . The next  lines denote the matrix's rows, with each line containing space-separated integers describing the columns.

##Output Format

Print the absolute difference between the two sums of the matrix's diagonals as a single integer.

##Sample Input

3

1 2 3

4 5 6

7 8 -9

##Sample Output

15

##Explanation

The primary diagonal is: 
1
      5
            -9

Sum across the primary diagonal: 1 + 5 - 9 = -3

The secondary diagonal is:
            3
      5
7
Sum across the secondary diagonal: 3 + 5 + 7 = 15 
Difference: |-3 + 15| = 12
