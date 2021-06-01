# First-And-Follow
To find the first and follow for a given grammar<br />
Sample INPUT and OUTPUT-<br />
Enter no. of terminals: 2<br />
Enter the terminals :<br />
c<br />
x<br />
Enter no. of non terminals: 4<br />
Enter the non terminals :<br />
A<br />
S<br />
B<br />
D<br />
Enter the starting symbol: A<br />
Enter no of productions: 4<br />
Enter the productions:<br />
A->S|ε|c<br />
S->BDx|ε<br />
B->ε<br />
D->ε<br />
   Non Terminals           First               Follow  <br />     
         A            {'c', 'ε', 'x'}          {'$'}  <br />      
         S               {'ε', 'x'}            {'$'}  <br />      
         B                 {'ε'}               {'x'}   <br />     
         D                 {'ε'}               {'x'}   <br />
			
![sample](https://user-images.githubusercontent.com/70994706/120287501-ed9cc500-c2dc-11eb-829f-e17d9541c395.jpg)

