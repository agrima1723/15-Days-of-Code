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

**DAY 2 = 14 / 10 / 2025**

1. leetcode - 1334. Find the City With the Smallest Number of Neighbors at a Threshold Distance
https://leetcode.com/submissions/detail/1801262180/

2. learnt about minimum spanning tree from striver video - https://youtu.be/ZSPjZuZWCME?si=bJwq7wC6KOJK_Msi
3. gfg prims algorithm question - https://www.geeksforgeeks.org/problems/minimum-spanning-tree/1
4. learnt about disjoint sets , union by rank and union by size from striver video - https://youtu.be/aBxjDBC4M1U?si=panbAX_u9kpvKA45
   
**DAY 3 = 15 / 10/2025**
1. Leetcode - 1319. Number of Operations to Make Network Connected
    https://leetcode.com/submissions/detail/1801985097/
2. Leetcode - 947. Most Stones Removed with Same Row or Column
    https://leetcode.com/submissions/detail/1802376109/
3. Solved 3 problems on codechef contest
4. Krushkal's algorithm using disjoint sets
   https://www.geeksforgeeks.org/problems/minimum-spanning-tree-kruskals-algorithm/1

  **DAY 4 = 17 / 10 / 2025**
  1. leetcode -721. Accounts Merge
   https://leetcode.com/submissions/detail/1803903444/
2. revised graph and tried more questions but didnt solved complete

   **DAY 5 = 18 / 10 / 2025**
 1. Watched stl videos by luv
   https://youtube.com/playlist?list=PLauivoElc3gh3RCiQA82MDI-gJfXQQVnn&si=p8xetRcucfaVlx0V
 2. learnt backened development : how to use postman for backened
   https://youtu.be/_u-WgSN5ymU?si=E-2vKqLkGnS_lqFa

   **DAY 6 = 19 / 10 / 2025**
   1. revised linked list
   2. reversing a linked list using recurrsion
   3. leetcode 328 : odd even linked list
      https://leetcode.com/problems/odd-even-linked-list/submissions/1806089129/
   4. leetcode 160 : Intersection of Two Linked Lists
      https://leetcode.com/submissions/detail/1806108603/

 ** DAY 7 = 21 / 10 / 2025** 
     1. leetcode - 1903. Largest Odd Number in String
     https://leetcode.com/submissions/detail/1807864778/
     2. leetcode - 151. Reverse Words in a String
     https://leetcode.com/submissions/detail/1807864778/

   **DAY 8 = 22 / 10 / 2025 **
   1. leetcode - 1021. Remove Outermost Parentheses
      https://leetcode.com/submissions/detail/1808285016/
   2. leetcode - 14. Longest Common Prefix
      https://leetcode.com/submissions/detail/1808340848/
   3. leetcode - 205. Isomorphic Strings
      https://leetcode.com/submissions/detail/1808722125/
   4. leetcode - 796. Rotate String
      https://leetcode.com/submissions/detail/1808812262/

   ** DAY 9 = 23 / 10 / 2025**
      1. leetcode - 451. Sort Characters By Frequency
         https://leetcode.com/submissions/detail/1809746270/
      2. leetcode -1614. Maximum Nesting Depth of the Parentheses
         https://leetcode.com/submissions/detail/1809730109/

   DAY 10 = 24 / 10 / 2025 
   1. leetcode - 1781. Sum of Beauty of All Substrings
      https://leetcode.com/submissions/detail/1810084243/
   2. leetcode - 13. Roman to Integer
      https://leetcode.com/submissions/detail/1810156209/
    TLE eleminator sheet questions
   3. problem 1 - https://codeforces.com/contest/1890/problem/A
      solution id - https://codeforces.com/contest/1890/submission/345498422
   4. problem 2 - https://codeforces.com/contest/1896/problem/A
      solution id - https://codeforces.com/contest/1896/submission/345486610
   5. problem 3 - https://codeforces.com/contest/1899/problem/A
      solution id - https://codeforces.com/contest/1899/submission/345474005
