# Prompt Engineering Quiz Questions

Below are 30 multiple-choice questions designed to test your understanding of prompt engineering concepts, techniques, and best practices for large language models (LLMs). Each question has four options (A, B, C, D), with only one correct answer.

---

1. **What is the primary goal of prompt engineering as defined in the whitepaper?**  
   A) To train large language models more efficiently  
   B) To design high-quality prompts that guide LLMs to produce accurate outputs  
   C) To reduce the computational resources required for LLMs  
   D) To automate the process of data labeling for machine learning  

2. **How does setting the temperature to 0 affect the output of an LLM?**  
   A) It makes the output more random and creative  
   B) It ensures the output is deterministic, always selecting the highest probability token  
   C) It limits the output to the top-K tokens  
   D) It increases the output length  

3. **Which prompting technique involves providing multiple examples to the model to show a pattern it should follow?**  
   A) Zero-shot prompting  
   B) One-shot prompting  
   C) Few-shot prompting  
   D) System prompting  

4. **In the context of LLM output configuration, what does top-P sampling control?**  
   A) The maximum number of tokens in the output  
   B) The selection of tokens based on cumulative probability  
   C) The degree of randomness in token selection  
   D) The number of top tokens to consider for sampling  

5. **What is the main advantage of using chain of thought (CoT) prompting?**  
   A) It reduces the number of tokens required for a response  
   B) It improves the reasoning capabilities of LLMs by generating intermediate steps  
   C) It allows the model to generate code more efficiently  
   D) It eliminates the need for few-shot examples  

6. **Consider the following prompt: "Write a Python function to reverse a string." Which of the following is a likely output from an LLM?**  
   A) `def reverse_string(s): return s[::-1]`  
   B) `def reverse_string(s): return s.reverse()`  
   C) `def reverse_string(s): return ''.join(reversed(s))`  
   D) Both A and C  

7. **According to the whitepaper, what is a recommended practice when using few-shot prompting for classification tasks?**  
   A) Use examples that are all from the same class  
   B) Mix up the possible response classes in the examples  
   C) Keep the examples in a fixed order  
   D) Use as few examples as possible to save tokens  

8. **What is the purpose of step-back prompting?**  
   A) To generate code snippets step by step  
   B) To first consider a general question related to the task before addressing the specific problem  
   C) To reduce the output length by summarizing the response  
   D) To provide multiple examples in a single prompt  

9. **In self-consistency prompting, why is the same prompt provided to the LLM multiple times?**  
   A) To select the most creative response  
   B) To choose the most consistent answer through majority voting  
   C) To reduce the computational cost  
   D) To increase the diversity of the output  

10. **Which of the following best describes role prompting?**  
    A) It provides specific details or background information relevant to the task  
    B) It assigns a specific character or identity for the LLM to adopt  
    C) It sets the overall context and purpose for the LLM  
    D) It focuses on generating intermediate reasoning steps  

11. **What is a key benefit of returning LLM outputs in JSON format for data extraction tasks?**  
    A) It reduces the number of tokens used  
    B) It allows for more creative and varied responses  
    C) It forces the model to create a structured output, reducing hallucinations  
    D) It enables the model to generate longer responses  

12. **In the context of prompt engineering, what does the term "repetition loop bug" refer to?**  
    A) A situation where the model generates the same response multiple times  
    B) A common issue where the model gets stuck generating the same word or phrase repeatedly  
    C) A bug that causes the model to repeat the input prompt in its output  
    D) A scenario where the model loops through different reasoning paths without concluding  

13. **Which configuration setting is most appropriate for tasks that require a single correct answer, such as solving a math problem?**  
    A) High temperature and high top-P  
    B) Low temperature and low top-K  
    C) Temperature set to 0  
    D) High top-K and low top-P  

14. **What is the main difference between top-K and top-P sampling?**  
    A) Top-K selects the top K most likely tokens, while top-P selects tokens until the cumulative probability reaches P  
    B) Top-K controls randomness, while top-P controls output length  
    C) Top-K is used for creative tasks, while top-P is for factual tasks  
    D) Top-K is deterministic, while top-P is probabilistic  

15. **In chain of thought prompting, why is it important to set the temperature to 0?**  
    A) To ensure the model generates diverse reasoning paths  
    B) To make the output more creative  
    C) To ensure the model follows a single, correct reasoning path  
    D) To reduce the computational cost of generating the response  

16. **Which of the following is a best practice for designing prompts?**  
    A) Use complex language to challenge the model  
    B) Include as much information as possible to provide context  
    C) Be