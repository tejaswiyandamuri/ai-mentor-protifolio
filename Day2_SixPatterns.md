# Day 2 — Six Pattern Drills

Student Question:
"Explain Big-O notation for a placement interview."

Prompt 1:
You are a senior placement coach at Aditya University. You have prepared 200 B.Tech CSE students for TCS, Infosys, and Cognizant placement interviews. A 3rd-year CSE student with 7.5 CGPA asks you about Big-O notation. Explain it the way you would in a 1-on-1 prep session — concrete, conversational, exam-relevant.

Output: Big-O notation tells us how the running time of an algorithm grows as the input size increases. For example, linear search takes O(n) time because it may need to check every element, while binary search takes O(log n) because it repeatedly divides the search space in half. 
Interviewers ask Big-O questions to evaluate your understanding of algorithm efficiency and problem-solving skills.

Prompt 2:
Here are example explanations from a placement coach:

Q: What is recursion?
A: A function calling itself with a smaller problem. Like Russian dolls — open one, find a smaller one inside. Stops at base case. Example: factorial.

Q: What is a stack?
A: LIFO data structure. Push to add, pop to remove. Like a stack of plates — you take from the top.

Q: What is Big-O notation?
A:Big-O notation describes how an algorithm's execution time grows as the input size increases. 
Think of it like measuring how much longer a task takes when the workload becomes bigger. For example, linear search is O(n), meaning the time increases proportionally with the number of elements.

Prompt3:
Explain Big-O notation to a placement interview candidate. Think step by step before answering.

Step 1: define Big-O in one sentence.
Step 2: give one concrete example with code.
Step 3: explain why interviewers ask about it.
Step 4: synthesise into a 3-sentence summary.

Output:
Step 1:
Big-O notation measures how an algorithm's running time grows with input size.
Step 2:
Linear search:
for i in arr:
    if i == target:
        return True

Time complexity: O(n)
Step 3:
Interviewers ask this to evaluate algorithmic thinking and efficiency awareness.
Step 4:
Big-O notation helps compare algorithms based on scalability. Efficient algorithms are important for handling large inputs. 
Understanding Big-O is essential for coding interviews.

Prompt 4:
Explain Big-O notation for a placement interview. Return ONLY valid JSON with this exact shape:
{
  "definition": "",
  "intuition": "",
  "code_example": "",
  "common_pitfall": "",
  "interview_test_question": ""
}
Output:
{
  "definition": "Big-O notation describes how an algorithm's running time grows with input size.",
  "intuition": "It helps compare algorithms based on efficiency.",
  "code_example": "Linear search is O(n), nested loops are O(n²).",
  "common_pitfall": "Ignoring the dominant term and constants.",
  "interview_test_question": "What is the time complexity of binary search?"
}

Prompt 5: You are a senior placement coach for B.Tech CSE students at an Indian engineering college. You prepare students for TCS / Infosys / Cognizant interviews. 
You explain technical concepts in 50-80 words max, conversationally, with one concrete code example.
Output:Big-O notation describes how an algorithm's running time changes as the input size grows. For example, linear search is O(n) because it may need to examine every element.
Companies like TCS and Infosys often ask Big-O questions to check whether you can analyze and optimize algorithms.

Prompt 6:List the 5 most important sub-concepts a B.Tech student must understand about Big-O notation. Just the list.
Output:Big-O notation describes how algorithm performance changes as input size increases. Common complexities include O(1), O(log n), O(n), and O(n²). It helps compare different approaches and understand trade-offs between time and space. 
Interviewers ask Big-O questions because efficient problem solving is crucial in software development.
