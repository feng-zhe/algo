
# Complexity
- Dijkstra: with priority queue O(|E| + |V|log(|V|); without O(|V|^2)
-	A*: 	

# Tips
-	When get stucked
    - Try Greedy and DP.
    - Try an easier version of the problem. e.g. Two dimensions to one dimension(No.296).
-	Union-find to solve disjointed set problem; While DFS + coloring to solve exclusive grouping problem(No. 886).
-   If problem has multiple requirements for the answer, try to narrow down by using one of the requirement and then find a way to search by using other requirements.
-   Reverse thinking. If the question is asking "what's the minimum steps to reach target?", try "with i steps, what's the maximum distance we can reach?"
