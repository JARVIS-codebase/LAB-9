# LAB-9

**Exploitation - Exploration in simple n-arm bandit reinforcement learning | Epsilon-Greedy Algorithm**

An example of a classic reinforcement learning issue is the "n-arm bandit problem," which involves a collection of n slot machines or "one-armed bandits" with various payoff probabilities. By playing the machines frequently and taking lessons from the results, the objective is to identify the machine with the largest expected payoff.
Choosing the machine with the largest estimated payoff based on the available information is known as exploiting. The goal of exploration, on the other hand, is to select machines with lower anticipated rewards in order to learn more about their actual reward possibilities. 
A straightforward technique that balances exploitation and exploration is the epsilon-greedy algorithm. With a probability of 1-epsilon, the algorithm chooses the machine with the largest estimated payoff, and with an epsilon probability, it chooses a machine at random.

A straightforward but significant problem in reinforcement learning is the n-arm bandit problem. This issue can be resolved and the balance between exploitation and exploration balanced using the epsilon greedy algorithm. The n-arm bandit problem can be solved using the epsilon greedy method using the basic framework provided by this implementation.
