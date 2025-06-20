# OpenAI Agents SDK Quiz

*Note: This quiz has been carefully designed to exclude topics related to the MCP Model Context Protocol and Voice Agents, focusing instead on other core and advanced aspects of the OpenAI Agents SDK.*

---

## Section 1: Conceptual Understanding

1. **What defines an AI agent in the context of the OpenAI Agents SDK?**  
   - A) A program that processes data without interaction  
   - B) An entity that perceives its environment and takes actions to achieve goals  
   - C) A static model for prediction  
   - D) A database management system  
   **Answer:** B

2. **How does an AI agent differ from traditional AI systems?**  
   - A) It relies solely on pre-trained models  
   - B) It actively interacts with an environment to make decisions  
   - C) It does not use machine learning  
   - D) It operates without goals  
   **Answer:** B

3. **What is the role of a utility function in an AI agent?**  
   - A) To install the SDK  
   - B) To measure the agent’s success in achieving its objectives  
   - C) To define the agent’s hardware requirements  
   - D) To log performance metrics  
   **Answer:** B

4. **What distinguishes a deliberative agent from a reactive agent?**  
   - A) A deliberative agent acts based on immediate stimuli, while a reactive agent plans ahead  
   - B) A reactive agent uses planning, while a deliberative agent responds instantly  
   - C) A deliberative agent reasons about its actions, while a reactive agent responds to the environment without planning  
   - D) Both are identical in functionality  
   **Answer:** C

---

## Section 2: SDK Basics

5. **What is the first step to start using the OpenAI Agents SDK?**  
   - A) Writing a goal function  
   - B) Installing the SDK using a package manager like pip  
   - C) Defining an environment class  
   - D) Training a model  
   **Answer:** B

6. **Which class is central to creating an agent in the OpenAI Agents SDK?**  
   - A) OpenAIAgent  
   - B) EnvironmentSimulator  
   - C) UtilityManager  
   - D) AgentCoordinator  
   **Answer:** A

7. **What are the core components of the OpenAI Agents SDK?**  
   - A) Agents, environments, and visualization tools  
   - B) Databases and APIs  
   - C) Pre-trained models only  
   - D) Hardware drivers  
   **Answer:** A

---

## Section 3: Building AI Agents

8. **How do you define a goal for an agent in the OpenAI Agents SDK?**  
   - A) By passing a goal parameter to the agent’s constructor  
   - B) By editing the SDK source code  
   - C) By defining it in a separate configuration file  
   - D) Goals are automatically assigned  
   **Answer:** A

9. **Write a code snippet to set and retrieve an agent’s goal in the OpenAI Agents SDK.**  
   ```python
   from openai_agents_sdk import OpenAIAgent

   agent = OpenAIAgent()
   agent.set_goal("maximize_reward")
   current_goal = agent.get_goal()
   print(f"Agent's goal: {current_goal}")
   ```  
   **Expected Output:** "Agent's goal: maximize_reward"

10. **What is the purpose of the `decideAction` method in the OpenAIAgent class?**  
    - A) To select the next action based on the current perception  
    - B) To decide which goal to pursue  
    - C) To determine the agent’s learning rate  
    - D) To initialize the agent  
    **Answer:** A

11. **Provide a code snippet demonstrating the perception-action cycle of an agent.**  
    ```python
    from openai_agents_sdk import OpenAIAgent, Environment

    env = Environment()
    agent = OpenAIAgent()
    perception = agent.perceive_environment(env)
    action = agent.decide_action(perception)
    env.apply_action(action)
    ```

12. **What is the primary function of the Environment class in the SDK?**  
    - A) To train the agent  
    - B) To simulate the world the agent interacts with  
    - C) To store agent data  
    - D) To visualize agent performance  
    **Answer:** B

---

## Section 4: Advanced Topics

13. **How do agents in the OpenAI Agents SDK communicate in a multi-agent system?**  
    - A) Through a centralized database  
    - B) By passing messages using a defined protocol  
    - C) Via hardware signals  
    - D) Agents do not communicate  
    **Answer:** B

14. **What is the role of the AgentCoordinator class?**  
    - A) To create individual agents  
    - B) To facilitate interaction and coordination among multiple agents  
    - C) To define agent goals  
    - D) To monitor hardware usage  
    **Answer:** B

15. **What characterizes cooperative agents in a multi-agent system?**  
    - A) They compete for individual rewards  
    - B) They work together toward a common goal  
    - C) They operate independently without interaction  
    - D) They share no resources  
    **Answer:** B

16. **Write a code snippet showing two agents exchanging messages.**  
    ```python
    from openai_agents_sdk import OpenAIAgent

    agent1 = OpenAIAgent()
    agent2 = OpenAIAgent()
    agent1.send_message(agent2, {"task": "collaborate", "data": [1, 2, 3]})
    response = agent2.receive_message()
    print(f"Agent 2 received: {response}")
    ```  
    **Expected Output:** "Agent 2 received: {'task': 'collaborate', 'data': [1, 2, 3]}"

17. **Which learning paradigm is supported by the OpenAI Agents SDK for agents to learn from experience?**  
    - A) Supervised learning only  
    - B) Reinforcement learning  
    - C) Unsupervised learning  
    - D) No learning is supported  
    **Answer:** B

18. **What is a common cause of agent failure in the SDK?**  
    - A) Incorrect goal specification  
    - B) Excessive memory usage  
    - C) Lack of environment simulation  
    - D) All of the above  
    **Answer:** D

19. **How does the AgentFactory class assist in agent development?**  
    - A) By providing a template for creating customized agents  
    - B) By automatically training agents  
    - C) By defining the environment  
    - D) By replacing the OpenAIAgent class  
    **Answer:** A

20. **Which of the following tasks can be performed by agents in the OpenAI Agents SDK?**  
    - A) Navigating a maze  
    - B) Optimizing a supply chain  
    - C) Playing a strategy game  
    - D) All of the above  
    **Answer:** D

---

This quiz provides a comprehensive assessment of the OpenAI Agents SDK while explicitly avoiding the excluded topics of MCP Model Context Protocol and Voice Agents.