# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
MOV A,P0
 MOV R0,A
MOV B,R0
MUL AB
 MOV P2,A
 END





```

## OUTPUT

<img width="1600" height="1052" alt="WhatsApp Image 2026-05-27 at 11 07 04 AM" src="https://github.com/user-attachments/assets/824a5bba-e577-4051-b4c0-a3b732d328d6" />



## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END







```


## OUTPUT

<img width="1600" height="1073" alt="WhatsApp Image 2026-05-27 at 11 06 25 AM" src="https://github.com/user-attachments/assets/bc9e14c6-a8eb-4c5f-9024-4267c6023303" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


