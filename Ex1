MOV R0, #30H ; Move 30H into R0
MOV R1, #40H ; Move 30H into R0
MOV R3, #05H ; Set counter as 5
AGAIN: MOV A, @R0 ; Move content of R0 into A
MOV @R1, A
INC R0 ; Increment R0
INC R1 ; Increment R1
DJNZ R3, AGAIN
END
