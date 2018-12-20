1) Name - Himanshu Kotbagi
   UTA ID - 1001581530


2) Programming language - Java

3) How the code is structured?
(i)The program takes three inputs from the command prompt which is wumpus_rules,additional informtion and statement. 
(ii)This program creates the tree for additional information and knowledge base.
(iii)The knowledge base, statement and addtional symbols are given as arguments to the CheckTrueFalse function.
(iv)This function checks if the knowledge base entails the given statement and returns true or false.
(v) If not, it checks if the knowledge base entails the negation of the statement and returns true or flase.
(vi)The TT_Check_All function is called less by using the information in the additional files.
(vii)A dicitonary is created using the model where the symbol is the key and the value is true or false.
(viii)The truth table represented by the model is checked row by row for true or false by PL_TRUE
(ix) The output is then written to a file called result.txt file
 
4) How to run the code?
Answer: Type the following command to execute from the command prompt:
javac *.java

java CheckTrueFalse wumpus_rules.txt [additional_knowledge_file] [statement_file]

for example: java CheckTrueFalse wumpus_rules.txt kb.txt statement.txt

Note to be considered:

Arguments are case sensitive.

Symbols used in the file are case sensitive and Connectives have to be specified in lower case.

Reference:

Code Referred from Github for TT_Entails, TT_Entails_Alpha,TT_Check_All ,entailment counter and Logical Expressions.
Code Referred from Stack Overflow
Code Referred from Stack Exchange, Google and Youtube.
 