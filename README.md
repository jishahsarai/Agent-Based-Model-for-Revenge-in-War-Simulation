# Agent Based Model for Revenge in War Simulation
This was the final project I completed for the class "Computational Analysis of Social Complexity," where we explored several fascinating topics: Graphs - Network Science, Game Theory, Blockchain, and Agent-Based Models (ABM).

In this project, I decided to combine concepts from Graphs and ABM. The original idea was to imagine two communities in conflict, starting with a minor incident where a friend of yours gets hurt. Would you seek revenge and attack the other group? What if you have friends in the other community? What if you are not strong enough to take revenge or are not a violent person?

Several factors were considered for each individual, such as velocity, health, nationality, residency, propensity for violence, strength, and desire for revenge. Each person belonged to a social network structure and had several friends represented by links, which influenced their decision to attack or not attack the opposing community.


![image](https://github.com/user-attachments/assets/14300fb9-34cc-4a7c-865b-92d7441c0984)

**Fig. 1** In this image, each point represents a person. The color of the point indicates their nationality, and the position represents the community to which they belong. As you can see, there are "foreigners," people who live in a place different from their nationality.

At the end, several statistics were collected for the ABM model by changing the parameters. There was a strong relationship between the escalation of conflict and the attributes of violence and revenge in individuals.

## Repository Guidance:
Inside the repository, you will find a Jupyter Notebook written in Julia and a video demonstrating the model's development. In the video, the color representation of the agents is as follows: Blue for agents with nationality A, Orange for agents with nationality B, Red for wounded agents, and Black for agents who have been killed.

## Learning Outcomes:
- Improved technical skills in Julia programming Language and using relevant package tools for simulation and data analysis such as Agents, Graphs, CairoMakie, and Plots.
- Gained a comprehensive understanding of how to apply concepts from Network Science and Agent-Based Models to simulate and analyze social dynamics and conflicts.
- Communicate findings through visualizations and written explanations, as demonstrated in the project report and video.
- Improved critical thinking and problem-solving skills by considering multiple factors and scenarios in the simulation, such as nationality, residency, and personal attributes like violence and revenge, that contributed to the global outcome.
