---
title: Quiz
date: 2025-06-30
author: Your Name
cell_count: 16
score: 15
---

```python
# Quiz data as a list of dictionaries
quiz = [
    {"question": "What is the capital of France?", "options": ["Paris", "London", "Berlin", "Rome"], "answer": "Paris"},
    {"question": "Which planet is known as the Red Planet?", "options": ["Earth", "Mars", "Venus", "Jupiter"], "answer": "Mars"},
    {"question": "Who wrote '1984'?", "options": ["George Orwell", "Mark Twain", "J.K. Rowling", "Ernest Hemingway"], "answer": "George Orwell"},
    {"question": "What is the square root of 64?", "options": ["6", "8", "10", "7"], "answer": "8"},
    {"question": "Which element has the chemical symbol 'O'?", "options": ["Oxygen", "Gold", "Iron", "Hydrogen"], "answer": "Oxygen"}
]

```


```python
import random
import time

```


```python
random.shuffle(quiz)

```


```python
start_time = time.time()

```


```python
score = 0
responses = []

```


```python
def ask_question(q_data, index):
    print(f"\nQ{index + 1}: {q_data['question']}")
    for i, option in enumerate(q_data["options"], 1):
        print(f"{i}. {option}")
    return input("Enter the option number: ")

```


```python
for i, q in enumerate(quiz):
    user_input = ask_question(q, i)
    try:
        selected = q["options"][int(user_input) - 1]
    except (IndexError, ValueError):
        selected = "Invalid"
    
    correct = selected == q["answer"]
    responses.append((q["question"], selected, q["answer"], correct))
    if correct:
        print("✅ Correct!")
        score += 1
    else:
        print(f"❌ Incorrect! The correct answer was: {q['answer']}")

```

    
    Q1: What is the square root of 64?
    1. 6
    2. 8
    3. 10
    4. 7
    

    Enter the option number:  2
    

    ✅ Correct!
    
    Q2: Who wrote '1984'?
    1. George Orwell
    2. Mark Twain
    3. J.K. Rowling
    4. Ernest Hemingway
    

    Enter the option number:  1
    

    ✅ Correct!
    
    Q3: Which element has the chemical symbol 'O'?
    1. Oxygen
    2. Gold
    3. Iron
    4. Hydrogen
    

    Enter the option number:  1
    

    ✅ Correct!
    
    Q4: What is the capital of France?
    1. Paris
    2. London
    3. Berlin
    4. Rome
    

    Enter the option number:  1
    

    ✅ Correct!
    
    Q5: Which planet is known as the Red Planet?
    1. Earth
    2. Mars
    3. Venus
    4. Jupiter
    

    Enter the option number:  2
    

    ✅ Correct!
    


```python
end_time = time.time()
total_time = round(end_time - start_time, 2)

```


```python
print("\n📊 Quiz Summary:")
print(f"Total Questions: {len(quiz)}")
print(f"Correct Answers: {score}")
print(f"Wrong Answers: {len(quiz) - score}")
print(f"Time Taken: {total_time} seconds")

```

    
    📊 Quiz Summary:
    Total Questions: 5
    Correct Answers: 5
    Wrong Answers: 0
    Time Taken: 39.25 seconds
    


```python
for q, user_ans, correct_ans, result in responses:
    print(f"\nQuestion: {q}")
    print(f"Your Answer: {user_ans}")
    print(f"Correct Answer: {correct_ans}")
    print("✅" if result else "❌")

```

    
    Question: What is the square root of 64?
    Your Answer: 8
    Correct Answer: 8
    ✅
    
    Question: Who wrote '1984'?
    Your Answer: George Orwell
    Correct Answer: George Orwell
    ✅
    
    Question: Which element has the chemical symbol 'O'?
    Your Answer: Oxygen
    Correct Answer: Oxygen
    ✅
    
    Question: What is the capital of France?
    Your Answer: Paris
    Correct Answer: Paris
    ✅
    
    Question: Which planet is known as the Red Planet?
    Your Answer: Mars
    Correct Answer: Mars
    ✅
    


```python
percentage = (score / len(quiz)) * 100
print(f"\nYour Score Percentage: {percentage:.2f}%")

```

    
    Your Score Percentage: 100.00%
    


```python
if percentage >= 90:
    feedback = "🌟 Excellent performance!"
elif percentage >= 70:
    feedback = "👍 Good job!"
elif percentage >= 50:
    feedback = "🙂 Fair effort, keep practicing!"
else:
    feedback = "😓 Needs improvement."
print(feedback)

```

    🌟 Excellent performance!
    


```python
with open("quiz_results.txt", "w", encoding="utf-8") as file:
    for q, u, c, r in responses:
        file.write(f"Q: {q}\nYour Answer: {u}\nCorrect Answer: {c}\n{'Correct' if r else 'Wrong'}\n\n")
    file.write(f"Score: {score}/{len(quiz)}\nPercentage: {percentage:.2f}%\nFeedback: {feedback}")

```


```python
with open("quiz_results.txt", "r") as file:
    print("\n📁 Saved Result File:\n")
    print(file.read())

```

    
    📁 Saved Result File:
    
    Q: What is the square root of 64?
    Your Answer: 8
    Correct Answer: 8
    Correct
    
    Q: Who wrote '1984'?
    Your Answer: George Orwell
    Correct Answer: George Orwell
    Correct
    
    Q: Which element has the chemical symbol 'O'?
    Your Answer: Oxygen
    Correct Answer: Oxygen
    Correct
    
    Q: What is the capital of France?
    Your Answer: Paris
    Correct Answer: Paris
    Correct
    
    Q: Which planet is known as the Red Planet?
    Your Answer: Mars
    Correct Answer: Mars
    Correct
    
    Score: 5/5
    Percentage: 100.00%
    Feedback: ðŸŒŸ Excellent performance!
    


```python
new_q = {
    "question": "What language is this quiz written in?",
    "options": ["Java", "C++", "Python", "Go"],
    "answer": "Python"
}
quiz.append(new_q)

```


```python

```


---
**Score: 15**