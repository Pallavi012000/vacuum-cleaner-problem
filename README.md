# vacuum-cleaner-problem
Real World Problem – Vacuum cleaner problem, dirt with two rooms 

Problem statement :
In this problem, our vacuum cleaner is our agent. It is a goal based agent, and the goal of this  agent, which is the vacuum cleaner, is to clean up the whole area. So, in the classical vacuum  cleaner problem, we have two rooms and one vacuum cleaner. There is dirt in both the  rooms, and it is to be cleaned. The vacuum cleaner is present in any one of these rooms. So,  we must reach a state in which both the rooms are clean and are dust free.

Algorithm :
1) Enter LOCATION A/B in captial letters where A and B are the two adjacent rooms respectively.
2) Enter Status O/1 accordingly where 0 means CLEAN and 1 means DIRTY.
3) Clean the starting room if status is 1 and add it to cost. Then check status of next room. If status is 1, then travel and then add it to cost.
4) If starting room has status of 0 then check the second room immediately. If the status of second room is 1, travel and clean and then add to cost. Else cost remains 0.
