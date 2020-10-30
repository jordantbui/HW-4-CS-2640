# Homework 4 Search Program(MIPS) - CS2640
10/30/2020<br>
Jordan Bui (BroncoID: 011821368)<br>
CPP Fall 2020<br>
CS 2640 Computer Organization and Assembly Programming

Homework 4 MIPS Code Implementation
-
Implementation for Search program. 
- Main declares an array of bytes with value "MIPS assemblt language!"
- Use search to find the "!" letter and output the location in the array
- Use search to find the "z" letter and output the location in the array
- MIPS file saved as search.s
- Tested using QTSpim program

Search.s
-
This program creates a search function that sequentially searches array x of N bytes for the relatinve location L of a value V.
  - Array x, number of bytes N, and value V are all passed into the function.
  - Location L is returned. (number from 1 to N)
  - Returns -1 for L if V is not found.
  
Required Output: *Output Must Be Exactly as Shown*
-
Search by F. Last<br><br>
MIPS assembly language!<br><br>
!:23<br>
z:-1
