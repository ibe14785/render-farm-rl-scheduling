# Reinforcement Learning-Based Scheduling for Heterogeneous Animation Render Farms

This repository contains the source code, experiment configurations, supplementary data, statistical-analysis outputs, figures, training histories, and trained model checkpoints associated with the paper:

**“Reinforcement Learning-Based Scheduling for Heterogeneous Animation Render Farms.”**

The study evaluates reinforcement learning-based schedulers in an online, discrete-event, and non-preemptive heterogeneous animation render-farm environment. Three reinforcement learning methods—Tabular Q-Learning, Deep Q-Network (DQN), and Proximal Policy Optimization (PPO)—are compared with six heuristic schedulers: Random, Round Robin, Least Loaded, Fastest Node, Earliest Finish Time, and Balanced Earliest Finish Time.

The experimental evaluation covers 3,780 paired workload scenarios and 34,020 scheduler observations. The scenarios include:

- 4, 8, and 16 render nodes;
- 250 and 1,000 rendering jobs;
- batch, Poisson, and burst arrival patterns;
- homogeneous, moderate, and high node heterogeneity;
- different system-load factors;
- 30 paired evaluation-workload seeds.

The repository supports reproducibility by providing the simulator implementation, fixed evaluation seeds, algorithm configurations, raw results, statistical tests, performance tables, visualization scripts, and trained reinforcement learning models.

The evaluated performance metrics include makespan, average waiting time, turnaround time, resource utilization, load imbalance, deadline violation rate, estimated active-processing energy, throughput, and scheduling-decision overhead.

Statistical validation includes the Friedman test, Wilcoxon signed-rank tests with Holm correction, rank-biserial effect size, algorithm ranking, and paired win-rate analysis.
