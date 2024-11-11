# turing-codilty-task
#TURING Problem 1 Python 3 
Frog Feast There Are Several Frogs On A Line, Each With An Integer Coordinate And A Specific Tongue Size. More Precisely, The i th Frog Is On The Coordinate X i And Its Tongue Has Size S i . Additionally, There Are Flies, Also Positioned On Integer Coordinates. The i th Fly Is Positioned On The Y i Coordinate. A Frog i Manages To Eat A Fly j If, And Only If: ( X i − Y j ) <= S i This Means That The Frog Can Eat The Fly If The Distance Between Them Is Less Than Or Equal To The Size Of The Frog's Tongue. Your Task Is To Determine, For Each Frog, How Many Flies It Can Eat. Input Format:

X Is A List Of Integers Where X [ i ] Represents The Position Of The i th Frog.
S Is A List Of Integers Where S [ i Represents The Size Of The Tongue Of The i th Frog.
Y Is A List Of Integers Where Y [ i ] Represents The Position Of The i th Fly. Output Format
The Function Should Return A List Of Integers Where The i th Integer Represents The Number Of Flies The i th Frog Can Eat. Examples:
Input X = [ 1 , 4 , 5 ] , S = [ 2 , 3 , 5 ] , Y = [ 2 , 3 , 5 ] Output: [ 2 , 3 , 3 ]
Input X = [ 3 ] , S = [ 5 ] , Y = [ 7 , 1 , 2 , 6 , 4 , 5 , 3 , 0 , 8 ] Output [9] Constraints:
Positions X[I], S[I], And Y[I] Are Non-Negative Integers.
No Two Frogs Share The Same Position In The List X .
There May Be Cases Where There Are No Frogs And/Or No Flies
0>X,S,& Y<=10^5
To solve this problem, you can iterate through each frog and count how many flies it can eat based on the given condition. 

TURING Problem 2 
Reaching Permutation Given an array of N integers, your task is to transform this array into a permutation of the first N positive integers. A permutation of size N is an arrangement of numbers such that each number from 1 to N appears exactly once. In one operson, you can increase or decrease any element of the array by 1.

Examples

Input N-13, 2, 1, 4] Output 0 Explanation No operation needed already a permutation

Input N 14 14 2 Explanation Decrease one 4 to 3 to form the permutation [4

Input N-(2-34,51 Output 4 Explanation: 4 operations to decrease each element by 1 to reach permutation (1, 2.3. Note that this is one of the possible permutations, eg this can also be achieved by 4 operations to decrease the 5 to 1 to form the permutation (2, 3, 4, 1) Constraints: The integers in the array Ng will be equal or bigger than 1. The size of the array N can range from 1 to 10^5