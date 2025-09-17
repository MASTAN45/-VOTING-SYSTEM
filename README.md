# Mini Voting System

A simple **C program** simulating a mini voting system for student elections. Users can vote for candidates, and the program calculates and displays the winner along with the vote margin.

---

## Table of Contents

* [Overview](#overview)
* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)
* [Candidates](#candidates)
* [Voting Rules](#voting-rules)
* [License](#license)

---

## Overview

This project is a **console-based voting system** implemented in **C**. It allows eligible voters to cast their votes for one of five candidates and displays election results showing the winner and vote differences.

---

## Features

* Allows multiple voters to cast votes for candidates
* Ensures only eligible voters (age ≥ 18) can vote
* Calculates and displays total votes for each candidate
* Shows which candidate won and the margin of votes
* Handles tie scenarios gracefully

---

## Installation

1. Copy the code into a C file, e.g., `voting_system.c`
2. Open in **Visual Studio** or any C compiler
3. Compile and run the program

---

## Usage

1. Run the program in your console/IDE
2. Enter your **age** to verify eligibility
3. Enter your **voter ID**
4. Choose a candidate by pressing:

   * `1` for Santhosh ⚽
   * `2` for Surya 🎯
   * `3` for Kalesha 💡
   * `4` for Mastan ✂
   * `5` for Somanadh ⏳
5. Press `6` to display election results

---

## Candidates

| Number | Candidate  |
| ------ | ---------- |
| 1      | Santhosh ⚽ |
| 2      | Surya 🎯   |
| 3      | Kalesha 💡 |
| 4      | Mastan ✂   |
| 5      | Somanadh ⏳ |

---

## Voting Rules

* Only voters **18 years or older** are allowed
* Voters can vote only once in a single run of the program
* Election results show:

  * Total votes for each candidate
  * Winner of the election
  * Margin of victory against each other candidate
* If all candidates receive the same votes, it declares a tie

---

## Example Output

```
*MINI VOTING SYSTEM*

WELCOME to STUDENT ELECTION

Enter your age: 20
Your are eligible for vote
Enter your voter ID: 101
Press 1 to vote SANTHOSH⚽
Press 2 to vote SURYA🎯
Press 3 to vote KALESHA💡
Press 4 to vote MASTAN✂
Press 5 to vote SOMANADH⏳
Press 6 to show election result
Please choose: 1

*santhosh won the election*

Total vote of santhosh: 1
santhosh won by 1 votes to surya
...
```
