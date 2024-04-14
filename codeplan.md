         
A represents the far left of the board. B represents the middle of the board and C represents the end of the board. Numbers 1,2,3,4, represents the rings from 1 being the smallest to 4 being the largest.

AB&C has arrays and our goal is to move the numbers between the arrays.

PrintStacks is the results behind moving the pieces.

movePiece to move from one stack to another stack.
example to access 'a' stack in stacks: stacks.a OR stacks[a]
take piece off end of start array (pop)   add piece to end of end array (push)


isLegal letting you know if you have made the correct move or not.
correct move will be putting a small ring ontop of a larger ring.
if it's empty you can use any ring but if it has a ring you would have to stack with a smaller ring.

checkForWin will be determined if all numbers are stacked from the largest to the smaller ring.
moving rings from stack A to either B or C from largest ring to smallest ring.


towersOfHanoi is being called in getPrompt, which is what askes the user for their input.
it has 2 arguments startstack and endstack.
startStack represents where the ring starts and endStack represents where the ring is being placed.

startStack and endStack are going to be either a, b, or c





if startStack is lesser than endStack move is true