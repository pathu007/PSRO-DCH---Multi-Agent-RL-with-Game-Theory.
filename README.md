### Follow [Open_spiel by DeepMind](https://github.com/deepmind/open_spiel) to Install OpenSpiel for research in general reinforcement learning and search/planning in games. 


# A Unified Game-Theoretic Approach to Multiagent Reinforcement Learning

### Abstract:

Recent advances in Game Theory have applications in Economics, Smart Power Grids,
Intelligent Transportation, Smart Cities, Self-Driving, Multi-agent Robotics, etc. As all of
these systems would require a multi-agent rational decision making to derive optimal outcomes. These procedure of achieving maximum payoff, would often lead towards competing or
cooperative strategy outcomes for an independent rational agent. One similar rational agent
is the learning agent using reinforcement learning to explore and exploit the environment,
in order to learn optimal policy. However, similar approach does not work as effectively for
multi-agent setting, where since all the agents have shared state-space, one agent’s learned
policy might over-fit to other agent’s policies or may fail to generalize during execution. One
reason is, reinforcement learning agent is an independent agent, which interacts only with
Markovian and static environment. But, These assumptions does not hold for Multi-agent
setting, where agent has to react dynamically based on other agent’s behaviours. To accommodate such issues and effectively learn best responses for each agent, authors in [2] introduces
new metric Joint-policy correlation and describes a meta-algorithm for general Multi-agent
Reinforcement Learning. Based on economic reasoning, this algorithm uses deep reinforcement learning to compute best responses to a distribution over polices and uses empirical
game-theoretic analysis to compute new meta-strategy from learned distributions. Approach
presented, rather than computing exact best response strategy, computes approximate best
response using reinforcement learning. Objective of project is to gain better understanding
of the new Joint-policy metric, model the hierarchical approach defined and replicate the experimental results presented of Meta-strategy learning algorithm.

### [click here, To access full report.](https://github.com/pathu007/PSRO-DCH---Multi-Agent-RL-with-Game-Theory./blob/main/PSRO_DCH_Multi-Agent_RL.pdf)

### References:

[1] D. Bloembergen, K. Tuyls, D. Hennes, and M. Kaisers. Evolutionary dynamics of multi-agent learning:
A survey. Journal of Artificial Intelligence Research, 53:659–697, 08 2015.
[2] M. Lanctot, V. Zambaldi, A. Gruslys, A. Lazaridou, K. Tuyls, J. Perolat, D. Silver, and T. Graepel.
A unified game-theoretic approach to multiagent reinforcement learning. In I. Guyon, U. V. Luxburg,
S. Bengio, H. Wallach, R. Fergus, S. Vishwanathan, and R. Garnett, editors, Advances in Neural Information Processing Systems, volume 30. Curran Associates, Inc., 2017.
[3] R. Sharma and M. Gopal. Synergizing reinforcement learning and game theory—a new direction for
control. Applied Soft Computing, 10(3):675–688, 2010.
[4] K. G. Vamvoudakis, H. Modares, B. Kiumarsi, and F. L. Lewis. Game theory-based control system
algorithms with real-time reinforcement learning: How to solve multiplayer games online. IEEE Control
Systems Magazine, 37(1):33–52, 2017.
[5] W. Walsh, R. Das, G. Tesauro, and J. Kephart. Analyzing complex strategic interactions in multi-agent
systems. 01 2002.
