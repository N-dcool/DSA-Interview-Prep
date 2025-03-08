# 🚀 DSA & Interview Preparation Tracker

## 📌 Overview
This repository is for tracking our group's progress in **DSA, System Design, CS Fundamentals, and more** to prepare for product-based IT company interviews.

### 🔥 How We Use This Repo
1. 📅 **Daily Progress Logs** → Each member maintains their own folder.
2. ✅ **Task Management (GitHub Projects)** → Track tasks in the Kanban board.
3. 💬 **Doubt Discussions (Issues)** → Raise an issue if you're stuck.
4. 🎯 **Weekly Review (Pull Requests)** → Summarize weekly progress via PRs.

---

## 📁 Folder Structure
```
📂 DSA-Interview-Prep   # Common Repo (Main Repository)
 ├── 📂 Amit   -> (Submodule: Amit's Repo)
 ├── 📂 Rohit  -> (Submodule: Rohit's Repo)
 ├── 📂 Hitesh -> (Submodule: Hitesh's Repo)
 ├── 📂 Naresh -> (Submodule: My Repo)
 ├── 📜 README.md  # Guidelines & Instructions

```


Each member creates their own **folder** with their name inside `DSA-Interview-Prep/`. Inside their folder, they can create:
- `DSA/` → Stores their **daily DSA solutions**.
- `CS-Fundamentals/` → Stores **notes on OS, DBMS, CN, etc.**
- `progress.md` → Personal progress log.
- Any other folders as needed for additional topics.

---

## 🏆 How to Contribute
### 1️⃣ Daily Progress Updates
Each member updates their own folder daily.

**Example for Amit (`DSA-Interview-Prep/Amit/DSA/day1.md`)**
```md
### 📅 March 4, 2025 - DSA Solutions
#### Problem 1: Two Sum
**Approach:** Used HashMap for O(n) solution.
**Code:**
```python
class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        hashmap = {}
        for i, num in enumerate(nums):
            diff = target - num
            if diff in hashmap:
                return [hashmap[diff], i]
            hashmap[num] = i
```

---

## 📌 Topics to Cover
### Data Structures & Algorithms
- Arrays & Strings
- Linked List
- Stack & Queue
- Recursion & Backtracking
- Sorting & Searching
- Hashing & HashMaps
- Binary Trees & BST
- Heaps & Priority Queue
- Graphs (BFS, DFS, Dijkstra, Floyd-Warshall)
- Dynamic Programming (Knapsack, LIS, LCS, Coin Change)
- Bit Manipulation

### CS Fundamentals
- Operating Systems (Processes, Threads, Synchronization, Deadlocks)
- Database Management System (Normalization, Joins, Indexing, Transactions)
- Computer Networks (TCP/IP, HTTP, DNS, Load Balancing, CDN)
- System Design (Scalability, Caching, Microservices, CAP Theorem)
- Object-Oriented Programming (SOLID, Design Patterns, Inheritance, Polymorphism)

---

## 📚 Useful Study Resources
### DSA Resources
- [NeetCode](https://neetcode.io/)
- [Striver’s SDE Sheet](https://takeuforward.org/interviews/strivers-sde-sheet-top-coding-interview-problems/)
- [Leetcode Patterns](https://leetcode.com/discuss/general-discussion/460599/blind-75-leetcode-questions)
- [Codeforces](https://codeforces.com/)

### CS Fundamentals
- **Operating Systems:** Galvin Book, [MIT OS Course](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-828-operating-system-engineering-fall-2012/)
- **DBMS:** Korth, [DBMS Playlist](https://www.youtube.com/playlist?list=PL7D-cg0GBpDkWcujU3TjBtzotir23cFjC)
- **Computer Networks:** Tanenbaum, [CN Lectures](https://www.youtube.com/playlist?list=PLRuqvIo14SeT0HsznB0vuYavzz1eFsGMG)
- **System Design:** [Grokking System Design](https://www.educative.io/courses/grokking-the-system-design-interview), Designing Data-Intensive Applications

### Mock Interviews
- [Pramp](https://www.pramp.com/)
- [InterviewBit](https://www.interviewbit.com/)
- [Leetcode Contests](https://leetcode.com/contest/)

---

## ❓ Doubt Discussion Format
If you are stuck on a problem, raise an issue using this format:
```md
### ❓ Problem/Doubt
**Topic:** Dynamic Programming
**Problem:** Struggling with Memoization vs Tabulation
**What I Tried:** Used recursion, but getting TLE
**Need Help From:** Anyone who understands DP optimization
```

---

## 👥 Team Members
- Amit (@amit)
- Rohit (@rohit)
- Hitesh (@hitesh)

🚀 **Let's stay consistent & crack product-based interviews together!** 🎯
