# Roads

Problem Description:

In another parallel universe, there are N cities and M bi-directional roads in the ADA kingdom, where the i-th road connects the city ui and the city vi with length wi. Next month, people are coming to join a party held in the ADA city.
Due to some accidents, all roads were broken. So now, you, a person living in the ada city (different from the ADA city) is worried about how to attend the party next month.
In order to restore the transportation among cities as soon as possible, the government of the ADA kingdom dispatch many teams to find the solution. To save time, each team independently proposes a set of roads to be repaired such that after repairing every city can reach each other and the total length of the repaired roads is minimized.
You realize that there may exist many possible road sets that satisfy the requirement. You are now wondering: what is the shortest path between the ada city S and the ADA city T such that each edge on that path belongs to some of the potential road sets. Note that the edges can be in different road sets.


Input:

The first line contains four space-separated integers N,M, S and T, which represent the number of cities, the number of roads, the ada city number, and the ADA city number respectively.
Each of the following M lines contains three space-separated integers ui,vi, and wi, indicating there is a road connecting the city ui and city vi with length wi.
It is guaranteed that if you repair all roads, every city can reach each other.

• 1 ≤ N, M ≤ 3 × 10^5 
• 1≤ui,vi ≤N
• ui ̸= vi
• 0≤wi ≤10^9


Output:

The output should contain one integer as the answer to this problem.
