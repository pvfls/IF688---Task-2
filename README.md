# Task 2

An evolution from Task 1 (github.com/pvfls/IF688-Task-1) to add Token Scanning.

It is suposed to return an error code if it reads something that is nor number nor symbol.

Input Example(Sucess):

10
10
+

Expected Output:

Token [type=NUM, lexeme=10]
Token [type=NUM, lexeme=10]
Token [type=PLUS, lexeme=+]
20

Input Example(Error):

10
a
+

Expected Output:

Error: Unexpected character: a
