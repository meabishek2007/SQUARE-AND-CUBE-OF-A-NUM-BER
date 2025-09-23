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
MOV DPTR,#4500H
MOVX A,@DPTR  
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```

## OUTPUT
<img width="1192" height="675" alt="image" src="https://github.com/user-attachments/assets/92ac7f88-1eea-483e-a0f0-c8a21af34c1c" />
<img width="960" height="492" alt="image" src="https://github.com/user-attachments/assets/fb99d87e-7696-42f5-a04c-e7c147a3aa98" />

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
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
MOV B,A
MOVX A,@DPTR
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```
## OUTPUT
<img width="940" height="412" alt="image" src="https://github.com/user-attachments/assets/26a987e3-954a-4189-ab46-02066d0c1372" />
<img width="812" height="463" alt="Screenshot 2025-09-23 211547" src="https://github.com/user-attachments/assets/d4eaad50-8dac-4454-9f20-07b0bf66fa1c" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
