
# Complexity
- Dijkstra: with priority queue O(|E| + |V|log(|V|); without O(|V|^2)
-	A*: Just Dijkstra with Heuristic values

# Tips
-	When get stucked
    - Try some examples
    - Try an easier version of the problem. e.g. Two dimensions to one dimension(No.296)
    - Try data structures you know
    - Think about some similar problems you have solved
    - Try Greedy and DP
-   After finishing the code, run some samples/edge cases to check the code.
-	Union-find to solve disjointed set problem; While DFS + coloring to solve exclusive grouping problem(No. 886).
-   If problem has multiple requirements for the answer, try to narrow down by using one of the requirement and then find a way to search by using other requirements.
-   Reverse thinking. If the question is asking "what's the minimum steps to reach target?", try "with i steps, what's the maximum distance we can reach?"
