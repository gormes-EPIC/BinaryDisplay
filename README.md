# Binary Display

https://github.com/user-attachments/assets/2be3eecb-3fd2-4ad7-b4ce-d6a10f310f07

## Objective
1. Create a recursive function to convert base 10(decimal) into base 2(binary)
2. Display binary numbers on a set of LEDs

## Materials
- 8 5mm LEDs
- 8 65 Ω(Ohm) resistors
- 16 M-M jumper wires
- Additonal breadboard(if needed)

## Part 1: Creating a recursive function

1. Create a new program `binary.txt` on your Pi. In the file define the new function `to_binary(n)` where `n` is a base 10 integer. This function will use **recursion** to convert `n` to its binary representation(a string of 1's and 0's).
2. Next, modify your program to take input from the user and print the binary value.

Here is a quick example of how to convert from decimal to binary: 

- To convert 10 to binary
- 10 % 2 = 0, continue with 10 / 2 = 5
- 5 % 2 = 1, continue with 5 / 2 = 2
- 2 % 2 = 0, continue with 2 / 2 = 1
- 1 % 2 = 1, stop as 1 / 2 = 0
- Reading remainders gives 1010 (binary).

## Part 2: Adding the lights
1. Now, wire your 8 lights to 8 different GPIO pins.
2. Set up your 8 LEDs in your code like you have in previous labs. You may want to use a list for this because 8 LED's can get messy pretty quickly.
3. Modify your program to light up the corresponding LEDs with the binary value. 1 is represented by a light that is on. 0 is represented by a light that is off.

   
## Deliverables
  - [ ] Uploaded a video and your final program to GitHub
  - [ ] Answers to the following questions
    - [ ] What is the maximum number your LED display can display? Why?
    - [ ] What is the **base case** and what is the **recursive case** in your function `to_binary()`?
    - [ ] How did you efficiently set up and mangage your lights? If your solution is not effecient, go back and edit it now.

Rubric
6 points - All required items are present.  
5 points - Task was completed, but supplementary materials are weak or missing.  
   - Code is complete, but poorly communicates necessary information
4 points - Task was attempted, but is missing major components.  
   - Missing comments, videos/photos, or reflection questions
3 points - Did not attempt or student should reattempt.
   - Inappropriate use of AI tools.
