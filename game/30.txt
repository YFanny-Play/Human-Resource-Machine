-- HUMAN RESOURCE MACHINE PROGRAM --

a:
    INBOX   
    COPYTO   24
b:
    COPYFROM [24]
    JUMPZ    a
    OUTBOX  
    BUMPUP   24
    JUMP     b


