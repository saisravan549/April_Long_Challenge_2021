# April_Long_Challenge_2021

April Long Challenge (ALC) is a global coding challenge hosted by Codechef during the month of April, every year. It consists of a set of challenging coding questions and a time frame of one month is given to solve these questions. The questions from ALC 2021 demanded indepth understanding of Datastructures and Algorithms.  

# Problem statements and my solutions

## Valid Pair:

Chef has three socks in his drawer. Each sock has one of 10 possible colours, which are represented by integers between 1 and 10 Specifically, the colours of the socks are A,B,and C. Chef has to wear two socks which have the same colour. Help Chef find out if that is possible or not.

Input/Output:

The first and only line of the input contains three space-separated integers A,B and C
Print a single line containing the string "YES" if it is possible for Chef to wear two socks with the same colour or "NO" if it is impossible (without quotes).
You may print each character of each string in uppercase or lowercase (for example, the strings "yEs", "yes", "Yes" and "YES" will all be treated as identical).

My Solution: https://www.codechef.com/viewsolution/44398707

## World Record

This news headline has been echoing in Chef's mind since 2009 when he started his career in sprinting. This time in the 2021 Tokyo Olympics he is determined to make a new world record. There are mainly 3 important factors that result in the variation in speed during practice and during competition. The first factor is a difference in track material which results in variation in the speed at competition with respect to practice by a factor of k1. The second factor is wind speed which results in variation in the speed at competition with respect to practice by a factor of k2. The final factor is the maximum speed achieved during practice. If the maximum speed during practice is v m/s then in competition it will be k3∗v m/s.
Given Chef's max speed v during practice and the factors k1,k2,k3 , find whether he will be able to create a new world record, i.e, can he complete 100m in less than 9.58 seconds?

Input/Output

First line will contain T, number of testcases. Then the testcases follow. Each testcase contains of a single line of input, four floats k1,k2,k3,v
Output in a single line, the answer, which should be "YES" if it's possible for Chef to create a new world record and "NO" if not.
You may print each character of the string in uppercase or lowercase (for example, the strings "yEs", "yes", "Yes" and "YES" will all be treated as identical).

My Solution: https://www.codechef.com/viewsolution/44399951

## Strong Language

A string is said to be using strong language if it contains at least K consecutive characters '*'.
You are given a string S with length N
. Determine whether it uses strong language or not.

Input/Output

The first line of the input contains a single integer T denoting the number of test cases. The description of T test cases follows.
The first line of each test case contains two space-separated integers N and K.
The second line contains a single string S with length N.

Print a single line containing the string "YES" if the string contains strong language or "NO" if it does not (without quotes).
You may print each character of each string in uppercase or lowercase (for example, the strings "yEs", "yes", "Yes" and "YES" will all be treated as identical).

My Solution: https://www.codechef.com/viewsolution/44403065

## Chef and Dice

Chef has N 6-sided standard dice. Each die has dimensions 1×1×1. Since Chef is bored during the quarantine, he decides to stack dice for fun.
First, Chef forms four vertical stacks of dice (not necessarily with the same height; empty stacks are allowed) on his table, which together make up a pile of dice with base area up to 2×2. Among all such structures, the total visible surface area of Chef's structure must be the smallest possible.
Then, Chef calculates the number of pips on the visible faces of all dice in the structure. A face of a die is visible if it does not touch the table or another die. Now, he is wondering: among all possible arrangements of dice, what is the maximum possible total number of visible pips? Since he is busy cooking, he is asking you to solve this.

Input/Output

The first line of the input contains a single integer T denoting the number of test cases. The description of T test cases follows.
The first and only line of each test case contains a single integer N.

For each test case, print a single line containing one integer ― the maximum possible number of visible pips.

My Solution: https://www.codechef.com/viewsolution/44438292

## Worthy Matrix

Chef found a matrix A with N rows (numbered 1 through N) and M columns (numbered 1through M), where for each row r and column c, the cell in row r and column (denoted by (r,c)) contains an integer Ar,c.
This matrix has two interesting properties:
The integers in each row form a non-decreasing sequence, i.e. for each valid i, Ai,1≤Ai,2≤…≤Ai,M.
The integers in each column also form a non-decreasing sequence, i.e. for each valid j, A1,j≤A2,j≤…≤AN,j. A K-worthy submatrix is a square submatrix of A, i.e. a submatrix with l rows and  columns, for any integer l, such that the average of all the integers in this submatrix is ≥K.
Chef wants you to find the number of K-worthy submatrices of A.

Input/Output

The first line of the input contains a single integer T denoting the number of test cases. The description of T test cases follows.
The first line of each test case contains three space-separated integers N, M and K. N lines follow. For each valid i, the i-th of these lines contains M
space-separated integers Ai,1,Ai,2,Ai,3,…,Ai,M.

For each test case, print a single line containing one integer ― the number of K-worthy submatrices of A.

My Solution: https://www.codechef.com/viewsolution/44602530

## Binary String MEX

You are given a binary string S. Chef defines MEX(S) as the smallest non-negative integer such that its binary representation (without leading '0'-s; in particular, the binary representation of 0 is "0") is not a subsequence of S.
Chef is asking you to find MEX(S). Since this integer could be very large, find its binary representation (without leading '0'-s).

Input/Output

The first line of the input contains a single integer T denoting the number of test cases. The description of T test cases follows.
The first and only line of each test case contains a single string S.

For each test case, print a single line containing one string: MEX(S) in binary representation.

My Solution: https://www.codechef.com/viewsolution/44764436
