# Assembly code explanation:
### general:
global is where the code starts
extern announce the extern functions that are used

### registers:
rdi is the register for the first argument of a function
rsi is the register for the second argument of a function
rdx is the register for the third argument of a function
rax is the register that stores te return value

in this code, the registers r8b and r9b are used to temporaly hold a value
all registers can be used to temporaly hold a value

### jumps:
jmp: jump to the mentioned function
je: jump to the mentioned function, if it is equal to the mentioned value
jne: jump to the mentioned function, if it is not equal to the mentioned value
jc: jump to the mentioned function it the condition is met

jumps are usually used in combination with cmp, which compares two regisers/values

### push pop:
push: pushes the mentioned register on the stack
pop: pops the newest register back from the stack, and puts it in the mentioned register

### others:
ret returns the code
inc increments the value in the register by one
mov copies one register in the other register
sub substracts the values of two registers

