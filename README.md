# SQUARE AND CUBE OF A NUMBER
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

ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
END







```

## OUTPUT

<img width="685" height="494" alt="Screenshot 2025-09-25 100129" src="https://github.com/user-attachments/assets/7e474c8c-199e-44bd-8a8f-18bda07b4a26" />

<img width="916" height="338" alt="Screenshot 2025-09-25 100135" src="https://github.com/user-attachments/assets/9337da3f-26b8-41b1-91a7-3e17c07a7016" />


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
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END







```


## OUTPUT

<img width="680" height="540" alt="Screenshot 2025-09-25 100226" src="https://github.com/user-attachments/assets/dd8df465-21d9-4f5e-accd-9de83a0feb0d" />


<img width="917" height="347" alt="Screenshot 2025-09-25 100232" src="https://github.com/user-attachments/assets/45410c12-5398-4e67-aafd-1ec723075c38" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
