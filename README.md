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
<img width="1919" height="1024" alt="image" src="https://github.com/user-attachments/assets/7bcec4a1-b080-4ab1-b89f-615d6c007761" />

<img width="240" height="205" alt="image" src="https://github.com/user-attachments/assets/1c4decec-ca06-497e-861c-c8c00dcb4aa6" />

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
<img width="1919" height="993" alt="image" src="https://github.com/user-attachments/assets/996c7e6d-5920-47a6-ac2e-10e58fddfe8c" />

<img width="228" height="156" alt="image" src="https://github.com/user-attachments/assets/863e59de-a511-4814-b18a-4fb4ddf04417" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
