# persistent-priorityqueue-question
Ethan is the leader of a team with N members. He has assigned an error score to each member in his team based on the bugs that he has found in that particular team member's task. Because the error score has increased to a significantly large value, he wants to give all the team members a chance to improve their error scores, thereby improving their reputation in the organization. He introduces a new rule that whenever a team member completes a project successfully, the error score of that member decreases by a count P and the error score of all the other team members whose score is greater than zero decreases by a count Q.

Write an algorithm to help Ethan find the minimum number of projects that the team must complete in order to make the error score of all the team members zero.

input:
3
6 4 1
4
1

output:
3

explain:
1:  6 4 1
2:  3 2 0
3:  1 0 0
count =3
