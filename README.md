# DSA & Problem Solving Practice (Python)
--------------------------------------------------------------

This repository contains Data Structures and Problem Solving questions
implemented in Python.  
The focus is on understanding logic, loops, conditions, and array operations.

------------------------------------------------------------
## 1. Problems Solution
------------------------------------------------------------

### 1️⃣ Compare the Triplets
- Compared two arrays element-wise.
- Assigned points based on greater, smaller, or equal values.
- Returned final scores for both participants.

**Concepts used:**  
Arrays, loops, conditional statements.

---------------------------------------------------------------

### 2️⃣ Array Sum
- Calculated the sum of all elements in an array.
- Worked with large integer values safely in Python.

**Concepts used:**  
Loops, accumulation, integers.

-----------------------------------------------------------------

### 3️⃣ Diagonal Difference (Matrix)
- Calculated the primary and secondary diagonal sums of a square matrix.
- Found the absolute difference between the two diagonals.

**Concepts used:**  
2D arrays (list of lists), indexing, absolute difference.

-----------------------------------------------------------------

### 4️⃣ Plus Minus
- Counted positive, negative, and zero values in an array.
- Printed their ratios by dividing with the total number of elements.

**Concepts used:**  
Counting, division, loops, conditional logic.

----------------------------------------------------------------
## 2. Problem_solution
----------------------------------------------------------------
 
## 1️⃣  Pyramid Pattern

**Description:**  
Prints a centered pyramid pattern using stars, where the number of stars increases
odd-wise in each row.

**Concepts Used:**  
Nested loops, spacing logic, arithmetic patterns.

----------------------------------------------------------------

 ## 2️⃣ Inverse Pattern

**Description:**  
Prints an inverted right-angle star pattern where the number of stars decreases
with each row.

**Concepts Used:**  
Loops, pattern logic.

----------------------------------------------------------------


## 3️⃣ Binary Centered Pattern

**Description:**  
Prints a centered pyramid pattern of alternating `0` and `1`.  
The starting value of each row depends on the row number.

**Concepts Used:**  
Nested loops, modulo operation, pattern observation.

-----------------------------------------------------------------

## 4️⃣ Mini-Max Sum

**Description:**  
Given an array of five integers, calculates the minimum and maximum sum obtained
by summing exactly four of the five elements.

**Concepts Used:**  
Arrays, loops, total sum, min/max logic.

------------------------------------------------------------------

## 5️⃣ Birthday Cake Candles

**Description:**  
Finds the tallest candle height in an array and counts how many times it appears.

**Concepts Used:**  
Maximum value, counting frequency, array traversal.

##  Purpose

- Strengthen DSA basics
- Improve logical thinking
- Practice competitive programming
- Maintain daily GitHub activity

-----------------------------------------------------------------------
## 3.Probem_Solution
-----------------------------------------------------------------------

## 1️⃣ Time Conversion

Concept: Convert time from 12-hour AM/PM format to 24-hour format.

Main Topics:

String manipulation, Conditional statements, Slicing techniques ,Edge case handling (12 AM / 12 PM)

## 2️⃣ Grading Students

Concept: Apply rounding rules to student grades based on given conditions.

Main Topics: 
Integer division, Mathematical rounding logic, Conditional checks ,Looping over multiple inputs

## 3️⃣ Apple and Orange

Concept: Count how many fruits fall within a given range on a number line.

Main Topics:

Arrays / Lists, Loop traversal, Coordinate line logic, Range validation, Separate counting logic

##  Learning Outcome
- Improved problem-solving skills
- Better understanding of arrays and loops
- Hands-on practice with HackerRank-style problems
- Clean and readable Python code

##  Status
✅ Completed basic array and logic problems  
📈 Continuing DSA practice

-----------------------------------------------------------------------------------------------
 ##  4. Problem Solution
-----------------------------------------------------------------------------------------------
   # Kangaroo – Number Line Jump 

This problem focuses on determining whether two kangaroos, starting at different positions on a number line and jumping at fixed rates, can land on the same position after the same number of jumps.

📌 Problem Description

Two kangaroos start at positions x1 and x2 on a number line.
Each kangaroo jumps forward with a constant speed v1 and v2 respectively.
Both kangaroos jump at the same time and move only in the positive direction.

The task is to decide whether there exists a point in time when both kangaroos land on the same position simultaneously.

Return:

YES → if they can meet
NO → if they never meet

# Core Concepts Used

- Number line movement
- Relative speed comparison
- Difference between starting positions
- Mathematical divisibility logic
- Modulus (%) operator
- Conditional decision making

Time-step synchronization (same number of jumps)

# Key Insight

- Both kangaroos always make the same number of jumps
- A meeting is possible only if:
- The kangaroo starting behind is faster
- The initial distance between them can be closed exactly after some number of jumps

---------------------------------------------------------------------------------------
## 5. Problem_solution 
---------------------------------------------------------------------------------------

🔢 Between Two Sets (HackerRank)

This problem focuses on finding integers that satisfy specific divisibility conditions between two given sets of numbers.

📌 Problem Description

Two arrays of integers are given:

A first array (A)
A second array (B)

- An integer is considered between the two sets if it satisfies both conditions:
- Every element of the first array is a factor of the integer.
- The integer is a factor of every element of the second array.
- The task is to determine how many such integers exist.

🧠 Core Concepts Involved

- Factors and multiples
- Divisibility rules
- Common multiples of a set
- Common factors of a set
- Logical filtering of numbers
- Range-based validation
- Mathematical reasoning (LCM & GCD intuition)

🔑 Key Insight

- The valid integers must be:
- Multiples of all elements in the first array
- Factors of all elements in the second array
- Only numbers that satisfy both conditions simultaneously are counted.

------------------------------------------------------------------------------
## 6. Problem solution
-----------------------------------------------------------------------------

 # Breaking the Records 

This problem is about tracking how often a player breaks their performance records over a sequence of games.

📌 Problem Description

- A list of scores is given, where each score represents the points scored by a player in consecutive games.
- The first score establishes both the initial highest and lowest records.
- As the season progresses, each new score is compared against the current records.
- The objective is to determine:
- How many times the highest score record is broken
- How many times the lowest score record is broken

🧠 Core Concepts

- Array / list traversal
- Running maximum tracking
- Running minimum tracking
- Conditional comparisons
- Counter variables
- Single-pass iteration

🔑 Key Insights

- The first score acts as the baseline for both records
- Highest and lowest records must be tracked independently
- A record is broken only when a score is strictly greater or strictly smaller
- Equal scores do not affect record counts

🎯 Purpose

- Strengthen array traversal skills
- Improve logical comparison techniques
- Understand state tracking in iterative problems
- Practice interview-style problem solving

🛠️ Technologies Used

Python 3
Basic mathematics
Data Structures & Algorithms fundamentals

-----------------------------------------------------------------------------
## 7. Problem Solution 
----------------------------------------------------------------------------

# Birthday Chocolate (Subarray Division)

This problem focuses on identifying contiguous segments within an array that satisfy specific length and sum conditions.

📌 Problem Description

A chocolate bar is divided into squares, where each square contains an integer value.
Lily wants to share a contiguous segment of the chocolate based on two conditions:

- The length of the segment must be equal to Ron’s birth month.
- The sum of the values in the segment must be equal to Ron’s birth day.
- The task is to determine how many such valid segments exist in the chocolate bar.

🧠 Core Concepts Used

- Arrays / Lists
- Contiguous subarrays
- Fixed-length window traversal
- Sum comparison logic
- Loop-based iteration
- Counting valid conditions

🔑 Key Insights

- Only consecutive elements can form a valid segment.
- Each segment must have an exact fixed length.
- Every possible segment of that length must be checked.
- A segment is valid only if its sum exactly matches the required value.
- The result is the count of all valid segments, not the segments themselves.

🎯 Purpose

- Practice subarray traversal techniques
- Understand fixed-size window logic
- Improve problem decomposition skills
- Build confidence in array-based DSA problems

-----------------------------------------------------------------------------
## 8. Problem Solution
-----------------------------------------------------------------------------
# Migratory Birds 

This problem focuses on identifying the most frequently sighted bird type from a given list, with a specific rule for handling ties.

📌 Problem Description

- A list of integers is given, where each integer represents the type ID of a migratory bird sighted.
- The task is to determine which bird type appears the most frequently in the list.
- If multiple bird types have the same highest frequency, the bird with the smallest numerical ID must be selected.

🧠 Core Concepts Used

- Frequency counting
- Arrays / Lists
- Hash maps / Dictionaries
- Comparison logic
- Tie-breaking conditions
- Single-pass data processing

🔑 Key Insights

- Each bird type must be counted independently.
- The bird with the maximum occurrence is the primary candidate.

In case of a tie:

- The bird type with the lowest ID is chosen.
- The order of sightings does not matter; only frequency matters.

🎯 Purpose

- Practice frequency-based problem solving
- Learn how to handle tie-breaking rules
- Improve logical comparison skills
- Build confidence with array and counting problems
  
---------------------------------------------------------------------------------
### 9. Problem Solution 
---------------------------------------------------------------------------------

# Divisible Sum Pairs (HackerRank)

This problem focuses on counting valid pairs in an array whose sum satisfies a given divisibility condition.

📌 Problem Description

- An array of integers is given along with an integer k.
- The task is to determine the number of pairs (i, j) such that:
i < j
- The sum of the elements at indices i and j is divisible by k
- A pair is considered valid only if both conditions are satisfied.

🧠 Core Concepts Used

- Arrays / Lists
- Nested iteration
- Pair generation logic
- Modulus (%) operator
- Index-based comparison (i < j)
- Counting valid conditions

🔑 Key Insights

- Each element must be paired only with elements that come after it to avoid duplicate pairs.
- Divisibility is checked using the modulus operator.
- Only pairs whose sum is exactly divisible by k are counted.
- The order of elements in a pair does not matter; index order does.

🎯 Purpose

- Strengthen understanding of pair-based array problems
- Practice conditional counting
- Learn to apply mathematical constraints in loops
- Prepare for beginner-level competitive programming questions

------------------------------------------------------------------------------
### 10. Problem Solution 
------------------------------------------------------------------------------

# Day of the Programmer 

This problem focuses on determining the exact date of the 256th day of the year, known as the Day of the Programmer, under different calendar systems.

📌 Problem Description

Given a year, the task is to identify the date of the 256th day of that year.
The challenge arises because different calendar systems were used historically, and one specific year has a special adjustment.

🧠 Core Concepts Used

- Calendar-based conditional logic
- Leap year rules
- Handling historical exceptions
- Date calculation reasoning
- Conditional branching (if / elif / else)

🔑 Key Insights

- Julian Calendar applies to years before 1918
- Leap year if the year is divisible by 4
- Gregorian Calendar applies to years after 1918
- Leap year if divisible by 400, or divisible by 4 but not by 100
- Year 1918 is a special case due to a calendar transition
- Several days were skipped, shifting the Day of the Programmer
- The result is always a specific fixed date format based on these rules

🎯 Purpose

- Practice conditional logic with real-world constraints
- Understand calendar transitions and edge cases
- Strengthen problem-solving skills involving historical data
- Prepare for logic-heavy competitive programming questions

--------------------------------------------------------------------------
