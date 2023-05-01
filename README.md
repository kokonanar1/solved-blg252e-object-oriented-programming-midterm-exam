Download Link: https://assignmentchef.com/product/solved-blg252e-object-oriented-programming-midterm-exam
<br>
<strong>Question #1 </strong>

Design and develop a program to produce different player types for a game. Your code should run with the main function given below and produce the given output. You are not allowed to use get/set functions, and you have to use the inheritance rules. The properties of the classes should not be public.

Create Player who has a name and a game score.  ExpertPlayer is also a player with additional “skills” (string) such as “time” and “space”.  You need to  print these features of different kinds of players as given in the output. You have to call the functions of base class whenever available (such as print).

Upload your program as <strong>question1.cpp</strong> to Ninova system.

Attention STL is <strong>allowed. (HINT: only </strong>String class)

<strong>Getting help</strong> from any other person, or from internet is <strong>not allowed</strong>.

Your program should run with the following main function and produce the sample output:

// —– Main Function —–

int main()

{

ExpertPlayer e1 = ExpertPlayer(“ExpertPlayer 1”, 10, “time”);

ExpertPlayer e2 = ExpertPlayer(“ExpertPlayer 2”, 30, “space”);

const Player p1 = Player(“player 1”, 40);

e1.print();

e2.print();

p1.print();

int sum = e1 + e2;

cout &lt;&lt; sum &lt;&lt; endl;




return 0;

}

Output:

constructor of player

constructor of expert player

constructor of player

constructor of expert player

constructor of player

Name: ExpertPlayer 1 score: 10

skill: time

Name: ExpertPlayer 2 score: 30

skill: space

Name: player 1 score: 40

40