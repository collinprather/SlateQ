Names: Collin Prather and Shishir Kumar

Finalized Research Question: 
Most practical recommender systems focus on estimating immediate user engagement without considering the long-term effects of recommendations on user behaviour. Reinforcement learning (RL) methods offer the potential to optimize recommendations for long-term user engagement. However, since users are often presented with slates
of multiple items—which may have interacting effects on user choice—methods are
required to deal with the combinatorics of the RL action space.
 
Google’s SlateQ algorithm addresses this challenge by decomposing the long-term value (LTV) of a slate into a tractable function of its component item-wise LTVs. For our project, we want to compare the efficiency of SlateQ to other RL methods like Q-learning that don’t decompose the LTV of a slate into its component-wise LTVs.

Repo has the following working code in GitHub:
    - A environment : We are working with RecSim's Interest Evolution environment.
    - An agent that performs random actions in the environment: See notebooks/first_steps.ipynb
    - An agent that learns based on the environment: See notebooks/first_steps.ipynb

List of ideas to finish project:
1. comparing SlateQ's efficiency across environments with varying complexity
2. comparing SlateQ with other agents in the library.