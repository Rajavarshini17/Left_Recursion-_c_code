# Left_Recursion-_c_code
"A C program demonstrating left recursion in context-free grammar and its elimination."
# Overview
Left recursion in grammars can cause infinite recursion in top-down parsers, making them unable to parse left-recursive rules correctly. This program eliminates left recursion in context-free grammar rules to make the grammar suitable for top-down parsers.
# What is Left Recursion?
In grammar, **left recursion** occurs when a non-terminal appears as the leftmost symbol in its own production rule. 
A → Aα | β
Where `A` is the non-terminal, `α` is a string of symbols, and `β` is a string that does not start with `A`.
This can lead to infinite loops in parsers, so left recursion must be eliminated for proper parsing.
