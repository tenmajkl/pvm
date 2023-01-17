# PVM

parek virtual machine

As look mum no computer says: "procrastinate as long as it is productive."

## Assembly design

### Commands

- psh {number} - pushes to the stack
- pop - pops from the stack
- out - outputs number on top of stack as character (meaning that pvm has ascii table included!!!)
- jmp {command_id} - jumps to command with given id
- add - adds 2 numbers on the stack
- sub - subtracts 2 numbers on the stack 
- mul - multiplies 2 numers on the stack
- div - divides 2 numbers on the stack
- edg - executes next command only if there is 1 on the top of the stack
- set {pointer} - sets popped value to given pointer
- get {pointer} - pushes value on given pointer 
- iot - outputs popped value as int
- and thats all for now

## PISP

I want to create lisp thhat would compile to pasm. I started but it won't be that simple, so I should go back to socka and if I have time I would work on it ig.
