# First-And-Follow
To find the first and follow for a given grammar 
Sample INPUT and OUTPUT-
Enter no. of terminals: 2
Enter the terminals :
c
x
Enter no. of non terminals: 4
Enter the non terminals :
A
S
B
D
Enter the starting symbol: A
Enter no of productions: 4
Enter the productions:
A->S|ε|c
S->BDx|ε
B->ε
D->ε
   Non Terminals           First               Follow       
         A            {'c', 'ε', 'x'}          {'$'}        
         S               {'ε', 'x'}            {'$'}        
         B                 {'ε'}               {'x'}        
         D                 {'ε'}               {'x'}        
