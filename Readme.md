# 👋 Welcome to Vision CSE  

This repository is for the **15 Days of Code Challenge** organized by **Vision CSE** 🚀  

## 📌 About the Challenge
- Duration: **15 Days**
- Goal: Code every day and build consistency  
- Task: Fork this repository, and update your progress here!  

## ✅ How to Participate
1. **Fork** this repository.  
2. **Edit this README** file in your fork.  
3. Document your progress daily:  
   - Add a short note on what you did  
   - Attach screenshots or  
   - Add links to your code submissions/projects  

4. Keep pushing your changes every day!  

**DAY 1 = 13 /10/2025**

q1 - leetcode 1976 : number of ways to arrive at a destination 
[https://leetcode.com/submissions/detail/1800319958/] 
explanation - in this we find all the paths with minimum distance by keeping the track of a counter parameter and then update it every time , then applied djikstra's algorithm 

q2 - leetcode 743 : network delay time 
https://leetcode.com/submissions/detail/1799909871/
explanation - in this question we find the minimum time for all the nodes to be reached from the source , store them in an array and then find the maximum of all the nodes , as in that time all the nodes will be covered  

q3 - leetcode 1091 : shortest path in a binary matrix 
https://leetcode.com/submissions/detail/1799891775/
explanation -  in this we did not require any priority queue because weighted graph is not given , hence we can simple form two vectors for adjacency lists of 8 direction of columns and rows . also make a distance array for storing all the distances calculated at different coordinates , now push the element in the queue if the distance already present at that coordinates is greater then the new estimated distance .

gfg - bellman ford 
https://www.geeksforgeeks.org/problems/distance-from-the-source-bellman-ford-algorithm/1
explanation - helps to detect negative cycle that we cannot do by djikstra's algorithm , we iterate over the adjacency list n-1 times and stores the minimum distance in an array and update it in every loop , if at nth loop we can find a minimum distance then there is a negative loop cycle    

gfg -  Minimum steps to reach end from start by performing multiplication and mod operations with array elements
https://www.geeksforgeeks.org/problems/minimum-multiplications-to-reach-end/1
explanation - used djikstra in this question , multiplied the numbers and used a queue to keep a track of all the nodes , in this we compare on the basis of steps needed for the target , made a distance array to keep the track of the distance at each node 
