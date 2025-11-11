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
MOV B,A
MUL AB
INC R0
MOV @R0,A
END

```

## OUTPUT
<img width="1190" height="663" alt="image" src="https://github.com/user-attachments/assets/53bd9ec4-c3e1-4a57-9872-d945b233fcc8" />



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
MOV R0,#10H
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

<img width="1210" height="650" alt="image" src="https://github.com/user-attachments/assets/ca97881c-3abc-4ec1-b007-8607b10eacc1" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
