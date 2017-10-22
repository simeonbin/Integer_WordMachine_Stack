Integer Word Machine Stack

Implements a Word Machine Stack with Integers as Operands and 
{+, -, *, DUP, POP} as Operators.

If you parse the input below, the Result would be 120.
 
{"5", "6","DUP", "5", "-", "POP", "DUP", "9", "*", "100", "20", "DUP", "POP", "+" }

If an Integer is parsed in the string, then you PUSH the number to the Stack.

If a {+, -, *} Operator is parsed, then you POP the two top numbers of the Stack 
and apply the (binary) Operator.

If a 'DUP' is parsed, then you peek at the top value in Stack, and you duplicate by PUSHing
it to the Stack.

If a 'POP' is parsed, then you POP the TOP value of the Stack.

When the End of the Input String arrives, you POP the TOP value of the Stack and Print it,
as the Result of the Parsing, if it is an Integer, or ERROR otherwise. 

If there is an ERROR in any of the above rules, you Print ERROR as a RESULT.






