# DSA & Problem Solving Practice (Python) - HACKERRANK
-------------------------------------------------------------

This repository contains Data Structures and Problem Solving questions
implemented in Python.  
The focus is on understanding logic, loops, conditions, and array operations.

-------------------------------------------------------------
## 1. Problems Solution ( 4 Problems) 
-------------------------------------------------------------

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
## 2. Problem_solution ( 5 Problems) 
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

----------------------------------------------------------------------
## 3.Probem_Solution ( 3 problems)
----------------------------------------------------------------------

## 1️⃣ Time Conversion

Concept: Convert time from 12-hour AM/PM format to 24-hour format.

Main Topics:

String manipulation, Conditional statements, Slicing techniques ,Edge case handling (12 AM / 12 PM)

-----------------------------------------------------------------------
## 2️⃣ Grading Students

Concept: Apply rounding rules to student grades based on given conditions.

Main Topics: 
Integer division, Mathematical rounding logic, Conditional checks ,Looping over multiple inputs
----------------------------------------------------------------------------

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

------------------------------------------------------------------------------------
## 5. Problem_solution 
------------------------------------------------------------------------------------

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
### 11. Problem Solution
-------------------------------------------------------------------------

 # Bill Division (Bon Appétit) 

This problem focuses on fairly splitting a bill between two people when one item was not consumed by one of them.

📌 Problem Description --

- Two friends share a meal, and the bill consists of multiple items with individual costs.
- One person does not eat one specific item, yet the bill is split.
- The task is to determine whether the person was charged correctly.
- If the charged amount is correct, print "Bon Appetit"
- If the charged amount is incorrect, print the extra amount charged

🧠 Core Concepts Used

- Array / list handling
- Index-based exclusion
- Summation of array elements
- Integer division
- Conditional comparison
- Basic arithmetic logic

🔑 Key Insights

- The total bill includes all items, but one item must be excluded for fair sharing
- Only the remaining items should be split equally
- The actual share is compared with the charged amount
- The result depends on whether the charge matches the fair share

🎯 Purpose

- Practice array manipulation and indexing
- Understand real-life problem modeling in code
- Strengthen logical comparison skills
- Prepare for beginner-level competitive programming problems

----------------------------------------------------------------------
### 12. Problem Solution
----------------------------------------------------------------------
# Sale by Match (Sock Merchant) – 

This problem focuses on counting how many matching pairs of socks can be formed from a given collection.

📌 Problem Description

A list of integers is given where each integer represents the color of a sock.
Each sock has exactly one matching pair if another sock of the same color exists.

The task is to determine how many pairs of socks can be formed.

🧠 Core Concepts Used

- Arrays / Lists
- Frequency counting
- Hash maps / Dictionaries
- Integer division
- Aggregation of results
- Loop-based traversal

🔑 Key Insights

- Socks can only form a pair if they have the same color
- One pair requires exactly two socks
- Extra or unpaired socks are ignored 
- The number of pairs for a color is calculated using:
- frequency // 2
- The final answer is the sum of pairs across all colors

🎯 Purpose

- Practice frequency-based problem solving
- Understand grouping and pairing logic
- Improve counting techniques in arrays
- Strengthen fundamentals for competitive programming

---------------------------------------------------------------------------------
### 13. Problem Solution
----------------------------------------------------------------------------------

# Drawing Book - 

📌 Problem Description

A book has a fixed number of pages. Starting from either the front or the back of the book, pages can be turned to reach a specific target page. Each page turn reveals two pages at a time.

The task is to determine the minimum number of page turns required to reach the target page.

🧠 Core Concepts Used

- Integer division
- Mathematical simplification
- Comparison logic
- Minimum value selection
- Page pairing concept

🔑 Key Insights

- Each page turn moves two pages at once.
- The number of turns can be calculated independently from:
 the front of the book
 the back of the book
- The final answer is the minimum of these two values.
- This problem is best solved using math, not iteration.

🎯 Purpose

- Learn to replace loops with mathematical reasoning
- Practice optimization using simple arithmetic
- Improve understanding of bidirectional traversal problems

--------------------------------------------------------------------
### 14. Problem Solution
-------------------------------------------------------------------

# Counting Valleys

📌 Problem Description

A hiker takes a sequence of steps represented by characters indicating upward and downward movement relative to sea level.
The task is to determine how many valleys the hiker walks through during the hike.

🧠 Core Concepts Used

- String traversal
- State tracking
- Incremental counters
- Conditional logic
- Event-based counting

🔑 Key Insights

- Sea level is treated as a reference point.
- A valley occurs when the hiker goes below sea level and then returns to sea level.
- The hiker’s current level must be tracked throughout the path.
- Valleys are counted only at the moment of returning to sea level from below.

🎯 Purpose

- Understand state-based problem solving
- Learn to detect patterns during traversal
- Practice logic that depends on transitions, not final values

-----------------------------------------------------------------------------------------------
### 15. Problem Solution
----------------------------------------------------------------------------------------------

# Electronic Shop 
📌 Problem Description

- Multiple budgets are given along with two lists representing the prices of keyboards and USB drives.
- For each budget, a customer can buy at most one keyboard and one USB drive.

- The task is to determine the maximum possible amount that can be spent without exceeding any of the given budgets.
- If no valid combination is possible for all budgets, the result should indicate failure.

🧠 Core Concepts Used

- Arrays / Lists
- Nested iteration
- Conditional comparison
- Maximum value tracking
- Accumulator (helper variables)
- Constraint-based selection

🔑 Key Insights

- Each budget is evaluated independently against all possible keyboard–USB combinations.
- Only combinations whose total cost is less than or equal to the budget are valid.
- For each budget, the best (maximum) valid sum is determined.
- Among all budgets, the overall maximum valid sum is selected as the final result.
- If no valid combination exists, a default value (such as -1) is used.

🎯 Purpose

- Practice working with multiple arrays simultaneously
- Learn how to track maximum values under constraints
- Understand accumulator patterns (current max, overall max)
- Strengthen logical reasoning for optimization problems

-----------------------------------------------------------------------------------
### 16. Problem Solution
-----------------------------------------------------------------------------------
# Cats and a Mouse --

📌 Problem Description

- Two cats and a mouse are positioned on a number line.
- Each cat moves at the same speed and tries to reach the mouse.
- For every given scenario, the task is to determine:
- which cat reaches the mouse first, or
- whether the mouse escapes if both cats reach at the same time.

🧠 Core Concepts Used

- Absolute difference (distance calculation)
- Comparison logic
- Conditional decision making
- Understanding input formats
- Multiple test case handling

🔑 Key Insights

- Distance between two positions is calculated using absolute difference.
- The cat with the smaller distance to the mouse reaches first.
- If both cats are at the same distance from the mouse, the mouse escapes.
- Each test case produces exactly one output.
- When multiple test cases are given, each case is evaluated independently.

🎯 Decision Rules

- Cat A closer → CAT A
- Cat B closer → CAT B
- Equal distance → MOUSE C

🧠 Important Understanding

- If the first input line contains a single number, it represents the number of test cases.
- Each subsequent line represents one independent scenario with positions of Cat A, Cat B, and Mouse.
- Outputs are printed line by line, one for each test case.


🎯 Purpose

- Practice distance-based comparisons
- Learn how to interpret structured input correctly
- Strengthen conditional logic skills
- Understand how problem statements map to real input/output behavior

--------------------------------------------------------------------------------------------
### 17. Problem Solution
--------------------------------------------------------------------------------------------

# Forming a Magic Square

📌 Problem Description

A magic square is a 3 × 3 matrix containing distinct integers from 1 to 9 such that the sum of each row, each column, and both diagonals is equal. This common sum is known as the magic constant.

Given a 3 × 3 matrix with values in the range 1 to 9, we can change any element to another value between 1 and 9.
The cost of changing a value is defined as the absolute difference between the original and the new value.

The objective is to find the minimum total cost required to convert the given matrix into a valid magic square.

🔑 Magic Constant

• For a 3 × 3 magic square, the magic constant is always 15
• Every row sums to 15
• Every column sums to 15
• Both diagonals also sum to 15

🧠 Core Concepts
• Limited Number of Valid Magic Squares

• A 3 × 3 magic square using numbers 1 to 9 has only 8 valid configurations
• These configurations are obtained through rotation and reflection
• No other valid arrangement exists outside these 8 forms

🔑 Cost Calculation

• The cost is computed as the sum of absolute differences
• Each cell of the input matrix is compared with the corresponding cell of a magic square
• Only the changed positions contribute to the total cost

 🔑 Optimization Strategy

• Compare the input matrix with each of the 8 valid magic squares
• Calculate the conversion cost for every comparison
• The minimum cost among them is the final answer

🎯 Why This Approach Works

• The matrix size is fixed (3 × 3)
• The number of target magic squares is constant (8)
• This allows a direct comparison without performance issues

📝 Key Takeaway

• The problem is solved by checking all possible valid magic squares and selecting the one with the minimum transformation cost

-------------------------------------------------------------------------------------------------------------------------------------
# 18. Problem Solution 
-------------------------------------------------------------------------------------------------------------------------------------

Picking Numbers
📌 Problem Description

The Picking Numbers problem focuses on finding the maximum length subset from a given list of integers such that the absolute difference between any two elements in the subset is at most 1.

The subset does not need to be contiguous, but all selected elements must satisfy the condition together.

🔑 Core Rule

• In a valid subset,
maximum value − minimum value ≤ 1

• This means a subset can contain:
– only one unique number
– or two consecutive numbers (like x and x+1)

• A subset containing three or more different values is invalid

🧠 Key Concepts

• Subset vs Adjacent Elements -

• The problem is about forming a subset, not comparing adjacent elements
• Elements can be chosen from anywhere in the array
• Order does not matter for the subset

🔑 Sorting Insight

• Sorting the array groups identical and close values together
• This makes it easier to evaluate which values can form a valid subset
• After sorting, valid subsets naturally appear as ranges

 🔑 Sliding Window Idea

• A window is defined using two pointers: start and end
• The window represents the current subset under consideration
• The window is adjusted to ensure the condition
(max − min ≤ 1) is always satisfied

🔑 Window Size (Count)

• The size of the current subset is calculated using:
end − start + 1
• This represents the number of elements in the inclusive range
• The maximum such size across all valid windows is the answer

🔑 Tracking the Maximum

• A variable is used to store the largest valid subset size found so far
• Each valid window is compared against this value
• The final result is the maximum subset size

🎯 Why This Approach Works

• The condition depends only on the minimum and maximum of the subset
• Sorting and window adjustment ensure the condition is never violated
• The method efficiently explores all valid subsets

📝 Key Takeaway

• Picking Numbers is about finding the largest group of numbers where all values differ by at most 1
• The problem is solved by carefully controlling which elements are included in the subset and tracking its size

----------------------------------------------------------
### 19. Problem Solution
----------------------------------------------------------

# Climbing Leaderboard --

🎯 Purpose

To find the player’s rank after each game using a leaderboard that follows dense ranking.

🔑 Key Insight

In dense ranking, duplicate scores do not create new ranks.
Therefore, ranking depends only on unique leaderboard scores.
Since leaderboard scores are descending and player scores are ascending, ranks can be updated efficiently without rechecking everything.

🧠 Concept

The problem is based on comparing the player’s score with the existing unique scores on the leaderboard.
As the player’s score increases over time, their rank can only improve or stay the same, never worsen.
This allows rank calculation by moving step-by-step through the leaderboard instead of starting over each time.

🧩 Core Concepts

• Dense Ranking: Same scores share the same rank
• Unique Scores: Duplicate leaderboard scores are ignored
• Score Comparison: Rank is decided by how many unique scores are higher
• Monotonic Movement: Player scores increase, ranks move upward
• Efficiency: Avoids repeated full scans of the leaderboard

-------------------------------------------------------------------------------------------------
