# ECE Pulse Software Competition

## Algorithms Competition

### Level 1

Given a stream of numbers from STDIN, print out the largest 10 when requested. You may assume you will be given more than 10 numbers. A skeletal file has been provided in C, however you may use another language provided it works in the same manner.

### Level 2

Find the largest fibbonacci number less than 4990909023387507173. We will look at your algorithm for runtime efficiency(And simply printing the number will give you no points!)

### Level 3

You are given a sudoku puzzle in a 9x9 array, where 0's represent empty spaces. You must solve the puzzle in an efficient manner.

You are given C skeletal code, where your solution goes in level3.h. If you decide to use another language, you may do so.

### Level 4

You are a local judge asked to solve a debt issue between many people. It has been found that multiple people owe each other money, and are looking for you to assign a bill to each person. You find you are able to simplify some of the charges due to some of the circular debt(Ex: Person A owes person B who owes person C who owes person A). You are given the array of initial charges in the following form

          Owes A   Owes B   Owes C
          
 Person A    0       1        -1
 
 Person B    -1      0        1
 
 Person C    1       -1       0

You should reduce it as such

          Owes A   Owes B   Owes C
          
 Person A    0       0        0
 
 Person B    0       0        0
 
 Person C    0       0        0
 
 You are given skeletal C codes to assist you. Your code goes in level4.h where int parties in the number of people in your case, and int* solve is a parties^2 size array you need to simplify. The end result must have the sum of the absolute value of all array values as small as possible without someone giving or witholding money that is owned.
