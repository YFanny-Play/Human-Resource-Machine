-- HUMAN RESOURCE MACHINE PROGRAM --

    JUMP     b
a:
    ADD      0
    OUTBOX  
b:
c:
    INBOX   
    COPYTO   0
    INBOX   
    SUB      0
    JUMPZ    a
    JUMP     c


