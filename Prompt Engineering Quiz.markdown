# Prompt Engineering Quiz

**Instructions:**  
- Choose the best answer for each question.  
- Some questions may require analyzing code snippets or scenarios.  
- All questions are based on the content from the provided documentation.

---

### Section 1: Understanding Prompts

**Question 1:**  
What is the primary purpose of a prompt in the context of AI models, as outlined in the documentation?  
A) To fine-tune the model's parameters  
B) To provide an input that directs the AI to produce a specific output  
C) To debug the AI model's internal logic  
D) To reduce the computational load on the AI system  
**Correct Answer:** B  

**Question 2:**  
According to the documentation, what distinguishes a well-crafted prompt?  
A) Its length and complexity  
B) Its ability to confuse the AI to test robustness  
C) Its clarity, specificity, and alignment with the desired outcome  
D) Its use of technical jargon to challenge the model  
**Correct Answer:** C  

---

### Section 2: Prompt Types and Techniques

**Question 3:**  
What is "zero-shot prompting" as described in the documentation?  
A) Providing the AI with multiple examples to infer a task  
B) Asking the AI to perform a task without any prior examples  
C) Using a single example to guide the AI's response  
D) Chaining multiple prompts to solve a complex problem  
**Correct Answer:** B  

**Question 4:**  
Which of the following best exemplifies a "few-shot prompting" technique from the documentation?  
A) "Translate this sentence: 'Hello, world!'"  
B) "Here are examples: 'Hello -> Bonjour', 'Goodbye -> Au revoir'. Now translate: 'Thanks'"  
C) "Write a story about a dog."  
D) "Summarize this text in one sentence."  
**Correct Answer:** B  

**Question 5:**  
What does the documentation suggest about "chain-of-thought" prompting?  
A) It involves randomizing prompt order to test AI flexibility  
B) It breaks down complex tasks into sequential, logical steps  
C) It uses a single prompt to handle multiple unrelated tasks  
D) It avoids examples to prevent overfitting  
**Correct Answer:** B  

**Question 6:**  
In the documentation, what is the purpose of including examples in a prompt?  
A) To increase prompt length for better performance  
B) To demonstrate the expected format or pattern of the response  
C) To reduce the need for clear instructions  
D) To test the AI’s memory capacity  
**Correct Answer:** B  

---

### Section 3: Prompt Design Principles

**Question 7:**  
Based on the documentation, which of the following is a critical factor in designing prompts for code generation?  
A) Specifying the programming language and desired functionality  
B) Using vague instructions to encourage creativity  
C) Avoiding examples to prevent bias  
D) Minimizing context to reduce processing time  
**Correct Answer:** A  

**Question 8:**  
What is a key consideration when crafting prompts for JSON output, per the documentation?  
A) Using natural language without structure  
B) Providing a sample JSON structure to guide the AI  
C) Avoiding specificity to allow flexibility  
D) Including irrelevant details to test AI focus  
**Correct Answer:** B  

**Question 9:**  
Which prompt modification would align with the documentation’s emphasis on specificity?  
A) "Write something about animals." → "Write a 200-word essay on animal habitats."  
B) "Generate code." → "Generate random text."  
C) "Tell me about history." → "Tell me anything."  
D) "Summarize this." → "Summarize this with extra details."  
**Correct Answer:** A  

**Question 10:**  
What does the documentation imply about the role of context in prompts?  
A) Context is unnecessary and should be avoided  
B) Context helps the AI interpret the task and produce relevant outputs  
C) Context only applies to creative tasks  
D) Context increases computational overhead without benefits  
**Correct Answer:** B  

---

### Section 4: Code-Based Prompt Engineering

**Question 11:**  
Consider this code snippet from the documentation:  
```python  
prompt = "Write a Python function to calculate the factorial of a number."  
```  
What is the intended outcome of this prompt?  
A) A function that sums numbers  
B) A recursive or iterative function computing n!  
C) A random number generator  
D) A syntax error explanation  
**Correct Answer:** B  

**Question 12:**  
Analyze this prompt code:  
```python  
prompt = "Generate a JSON object with fields 'name' and 'age' based on: name: Alice, age: 25"  
```  
What might improve its effectiveness?  
A) Adding a sample JSON output: "{'name': 'example', 'age': 30}"  
B) Shortening it to "Generate JSON."  
C) Removing the specific data to test AI creativity  
D) Using ambiguous terms like "data" instead of "JSON"  
**Correct Answer:** A  

**Question 13:**  
What does this code-based prompt from the documentation achieve?  
```python  
prompt = "Act as a Python expert and write code to reverse a string."  
```  
A) It generates a string concatenation function  
B) It produces code like `return s[::-1]` or a loop-based solution  
C) It outputs a random string  
D) It explains string theory  
**Correct Answer:** B  

**Question 14:**  
Which of the following prompts aligns with the documentation’s code generation examples?  
A) "Write code."  
B) "Create a Python script to sort a list of integers in ascending order."  
C) "Generate something technical."  
D) "Explain coding."  
**Correct Answer:** B  

---

### Section 5: Evaluating and Refining Prompts

**Question 15:**  
How does the documentation suggest evaluating prompt effectiveness?  
A) By measuring prompt length  
B) By assessing the accuracy and relevance of the AI’s output  
C) By counting API calls  
D) By analyzing hardware usage  
**Correct Answer:** B  

**Question 16:**  
What is a common pitfall in prompt design, inferred from the documentation’s examples?  
A) Being overly specific  
B) Using vague or incomplete instructions  
C) Including too many examples  
D) Specifying output format  
**Correct Answer:** B  

**Distance 17:**  
What refinement strategy is implicit in the documentation’s iterative examples?  
A) Changing the entire prompt randomly  
B) Adjusting prompts incrementally based on output quality  
C) Using shorter prompts each time  
D) Avoiding examples to simplify testing  
**Correct Answer:** B  

---

### Section 6: Advanced Applications

**Question 18:**  
Based on the documentation, what is a benefit of role-based prompting (e.g., "Act as a historian")?  
A) It reduces prompt length  
B) It aligns the AI’s tone and expertise with the task  
C) It increases randomness in responses  
D) It eliminates the need for examples  
**Correct Answer:** B  

**Question 19:**  
What is the purpose of the prompt "Convert this table to JSON" with a sample table, per the documentation?  
A) To test the AI’s memory  
B) To guide the AI in structuring tabular data as key-value pairs  
C) To generate a random JSON object  
D) To summarize the table in text  
**Correct Answer:** B  

**Question 20:**  
Which prompt best reflects the documentation’s approach to handling complex tasks?  
A) "Do something complicated."  
B) "Step-by-step, explain how to build a binary search tree in Python."  
C) "Write code quickly."  
D) "Generate text."  
**Correct Answer:** B  

---

### Section 7: Practical Scenarios

**Question 21:**  
A prompt yields inconsistent translations. What fix aligns with the documentation?  
A) Shorten the prompt  
B) Add few-shot examples like "Hello -> Bonjour"  
C) Remove all context  
D) Use more ambiguous language  
**Correct Answer:** B  

**Question 22:**  
What might cause a prompt like "Write a story" to fail, based on the documentation?  
A) Too many examples  
B) Lack of specific details (e.g., genre, length)  
C) Excessive context  
D) Clear instructions  
**Correct Answer:** B  

**Question 23:**  
For a prompt generating incorrect code syntax, what does the documentation suggest?  
A) Increase prompt complexity  
B) Provide a correct code example in the prompt  
C) Reduce prompt length  
D) Avoid specifying the language  
**Correct Answer:** B  

**Question 24:**  
Which prompt would likely produce a structured response, per the documentation?  
A) "Tell me about planets."  
B) "List the planets in our solar system with their diameters in a table."  
C) "Write something scientific."  
D) "Explain space."  
**Correct Answer:** B  

**Question 25:**  
What does the documentation imply about handling ambiguous tasks?  
A) Ambiguity is beneficial for creativity  
B) Explicit instructions and examples clarify intent  
C) Short prompts resolve ambiguity  
D) Context should be minimized  
**Correct Answer:** B