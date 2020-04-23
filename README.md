# Java Lexical Analyser

The lexical analyzer is built in java for Java programs. The lexer reads input from a file, and writes output to a file and/or stdout. The language used for implementing is java and it scans the entire source code of the program. It helps to identify tokens in the symbol table. A character sequence which is not possible to scan into any valid token will be a lexical error. 


the lexer skips whitespaces and comments while creating these tokens. If any error is present, then Lexical analyzer will correlate that error with the source file and line number.



# Execution :
javac Lexer.java
java Lexer



# Output:

    4      1 Identifier         phoenix_number
    4     16 Op_assign
    4     18 Integer           142857
    4     24 Semicolon
    5      1 Keyword_print
    5      6 LeftParen
    5      7 Identifier        phoenix_number
    5     21 Comma
    5     23 String            "\n"
    5     27 RightParen
    5     28 Semicolon
    6      1 End_of_input




