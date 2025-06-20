Quiz: Prompt Engineering for Large Language Models
Instructions:

This quiz consists of 30 multiple-choice questions.
Each question has four options (A, B, C, D), with only one correct answer.
The questions are designed to test your understanding of prompt engineering concepts, techniques, and best practices as discussed in the whitepaper by Lee Boonstra.
Some questions may include code snippets or require knowledge of specific configurations.
Take your time to read each question carefully before selecting your answer.


Questions:

What is the primary goal of prompt engineering as defined in the whitepaper?  

A) To train large language models more efficiently  
B) To design high-quality prompts that guide LLMs to produce accurate outputs  
C) To reduce the computational resources required for LLMs  
D) To automate the process of data labeling for machine learning  
Correct Answer: B


How does setting the temperature to 0 affect the output of an LLM?  

A) It makes the output more random and creative  
B) It ensures the output is deterministic, always selecting the highest probability token  
C) It limits the output to the top-K tokens  
D) It increases the output length  
Correct Answer: B


Which prompting technique involves providing multiple examples to the model to show a pattern it should follow?  

A) Zero-shot prompting  
B) One-shot prompting  
C) Few-shot prompting  
D) System prompting  
Correct Answer: C


In the context of LLM output configuration, what does top-P sampling control?  

A) The maximum number of tokens in the output  
B) The selection of tokens based on cumulative probability  
C) The degree of randomness in token selection  
D) The number of top tokens to consider for sampling  
Correct Answer: B


What is the main advantage of using chain of thought (CoT) prompting?  

A) It reduces the number of tokens required for a response  
B) It improves the reasoning capabilities of LLMs by generating intermediate steps  
C) It allows the model to generate code more efficiently  
D) It eliminates the need for few-shot examples  
Correct Answer: B


Consider the following prompt: "Write a Python function to reverse a string." Which of the following is a likely output from an LLM?  

A) def reverse_string(s): return s[::-1]  
B) def reverse_string(s): return s.reverse()  
C) def reverse_string(s): return ''.join(reversed(s))  
D) Both A and C  
Correct Answer: D


According to the whitepaper, what is a recommended practice when using few-shot prompting for classification tasks?  

A) Use examples that are all from the same class  
B) Mix up the possible response classes in the examples  
C) Keep the examples in a fixed order  
D) Use as few examples as possible to save tokens  
Correct Answer: B


What is the purpose of step-back prompting?  

A) To generate code snippets step by step  
B) To first consider a general question related to the task before addressing the specific problem  
C) To reduce the output length by summarizing the response  
D) To provide multiple examples in a single prompt  
Correct Answer: B


In self-consistency prompting, why is the same prompt provided to the LLM multiple times?  

A) To select the most creative response  
B) To choose the most consistent answer through majority voting  
C) To reduce the computational cost  
D) To increase the diversity of the output  
Correct Answer: B


Which of the following best describes role prompting?  

A) It provides specific details or background information relevant to the task  
B) It assigns a specific character or identity for the LLM to adopt  
C) It sets the overall context and purpose for the LLM  
D) It focuses on generating intermediate reasoning steps  
Correct Answer: B


What is a key benefit of returning LLM outputs in JSON format for data extraction tasks?  

A) It reduces the number of tokens used  
B) It allows for more creative and varied responses  
C) It forces the model to create a structured output, reducing hallucinations  
D) It enables the model to generate longer responses  
Correct Answer: C


In the context of prompt engineering, what does the term "repetition loop bug" refer to?  

A) A situation where the model generates the same response multiple times  
B) A common issue where the model gets stuck generating the same word or phrase repeatedly  
C) A bug that causes the model to repeat the input prompt in its output  
D) A scenario where the model loops through different reasoning paths without concluding  
Correct Answer: B


Which configuration setting is most appropriate for tasks that require a single correct answer, such as solving a math problem?  

A) High temperature and high top-P  
B) Low temperature and low top-K  
C) Temperature set to 0  
D) High top-K and low top-P  
Correct Answer: C


What is the main difference between top-K and top-P sampling?  

A) Top-K selects the top K most likely tokens, while top-P selects tokens until the cumulative probability reaches P  
B) Top-K controls randomness, while top-P controls output length  
C) Top-K is used for creative tasks, while top-P is for factual tasks  
D) Top-K is deterministic, while top-P is probabilistic  
Correct Answer: A


In chain of thought prompting, why is it important to set the temperature to 0?  

A) To ensure the model generates diverse reasoning paths  
B) To make the output more creative  
C) To ensure the model follows a single, correct reasoning path  
D) To reduce the computational cost of generating the response  
Correct Answer: C


Which of the following is a best practice for designing prompts?  

A) Use complex language to challenge the model  
B) Include as much information as possible to provide context  
C) Be concise, clear, and specific about the desired output  
D) Avoid using examples to save tokens  
Correct Answer: C


What is the purpose of using variables in prompts?  

A) To make prompts more dynamic and reusable for different inputs  
B) To reduce the token count of the prompt  
C) To confuse the model and test its robustness  
D) To enforce a specific output format  
Correct Answer: A


In the context of prompt engineering, what is "multimodal prompting"?  

A) Using multiple LLMs to generate a single response  
B) Combining different prompting techniques in one prompt  
C) Using multiple input formats, such as text and images, to guide the model  
D) Generating responses in multiple languages  
Correct Answer: C


Which prompting technique is most suitable for generating code snippets?  

A) Zero-shot prompting  
B) Few-shot prompting with code examples  
C) Role prompting as a software engineer  
D) Chain of thought prompting  
Correct Answer: B


What is a potential drawback of using JSON for LLM outputs?  

A) It increases the risk of hallucinations  
B) It requires more tokens, leading to higher costs and potential truncation  
C) It makes the output less structured and harder to parse  
D) It limits the model's ability to generate creative responses  
Correct Answer: B


In the whitepaper, what is emphasized as a crucial step in the prompt engineering process?  

A) Using the largest possible model for all tasks  
B) Documenting and iterating on prompt attempts  
C) Always using zero-shot prompting for simplicity  
D) Avoiding the use of examples to save tokens  
Correct Answer: B


Which of the following is NOT a benefit of using structured JSON output?  

A) Consistent output style  
B) Reduced chance of hallucinations  
C) Increased creativity in responses  
D) Ability to sort and filter data easily  
Correct Answer: C


In the context of code prompting, what is a key consideration when generating code with LLMs?  

A) LLMs can reason like humans, so no review is needed  
B) Always test and review the generated code, as LLMs may produce errors  
C) LLMs are perfect for generating code in any programming language  
D) Use high temperature settings to ensure diverse code outputs  
Correct Answer: B


What is the primary purpose of automatic prompt engineering?  

A) To manually design prompts for specific tasks  
B) To use LLMs to generate and optimize prompts automatically  
C) To eliminate the need for human input in prompt design  
D) To standardize prompts across different models  
Correct Answer: B


In tree of thoughts prompting, how does the model explore different reasoning paths?  

A) By generating a single chain of thought  
B) By creating a tree structure of possible thoughts and selecting the best path  
C) By using majority voting on multiple responses  
D) By stepping back to a general question before proceeding  
Correct Answer: B


Which of the following best describes the ReAct technique?  

A) It combines reasoning and acting by interleaving thought generation with actions  
B) It focuses solely on generating code for specific actions  
C) It uses reinforcement learning to optimize prompts  
D) It is a method for reducing token usage in prompts  
Correct Answer: A


When using few-shot prompting, how many examples are typically recommended as a starting point?  

A) 1-2  
B) 3-5  
C) 6-10  
D) As many as possible  
Correct Answer: B


In the context of prompt engineering, what is a "repetition loop bug"?  

A) A bug where the model repeats the input prompt  
B) A situation where the model generates the same word or phrase repeatedly due to inappropriate sampling settings  
C) A loop in the code generated by the model  
D) A scenario where the model fails to generate any output  
Correct Answer: B


Which of the following is a best practice for chain of thought prompting?  

A) Set the temperature to 1 for creative reasoning  
B) Use greedy decoding with temperature set to 0  
C) Include as many reasoning steps as possible  
D) Avoid providing examples to save tokens  
Correct Answer: B


In the whitepaper, what is suggested as a way to handle potential truncation issues with JSON outputs?  

A) Use a higher temperature to generate shorter responses  
B) Employ tools like the json-repair library to fix incomplete JSON  
C) Avoid using JSON for outputs altogether  
D) Increase the token limit to ensure complete responses  
Correct Answer: B




This markdown file provides a complete quiz with all questions and their correct answers, formatted for clarity and ease of use. You can use this file for self-assessment or to test your understanding of the concepts covered in the whitepaper.
