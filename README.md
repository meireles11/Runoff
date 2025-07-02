# 🗳️ Runoff Voting Simulation (C)

This is a C program that simulates a ranked-choice (instant-runoff) voting system.  
It was developed as part of the CS50x course to practice algorithmic thinking, array manipulation, and state-based logic control.

---

## 🧠 What It Does

The program allows a user to input a list of candidates and a number of voters.  
Each voter ranks the candidates in order of preference. The election then proceeds in rounds:

1. Votes are tabulated based on each voter's highest-ranked non-eliminated candidate.
2. If a candidate has more than 50% of the votes, they win.
3. If no one wins, the candidate(s) with the fewest votes are eliminated.
4. Votes are redistributed according to voter preferences.
5. Steps repeat until a winner is found or a tie occurs.

---

## 💡 Concepts Used

- Arrays and multi-dimensional arrays  
- Custom data structures (`struct`)  
- Vote counting and logic branching  
- Elimination rounds and vote redistribution  
- String comparison and input validation  
