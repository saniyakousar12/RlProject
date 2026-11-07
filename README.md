# Self-Driving Lab Simulator - RL Homework 2 (Unit 5, Project 7)

**Name:** Saniya Kousar | **Branch:** Computer Science Engineering | **Roll No:** 100523733092

A Q-learning agent learns to choose the temperature and concentration of a simulated chemical reaction to maximise yield within 25 experiments, while avoiding an unsafe temperature zone.

## Learning curve vs baselines

![Learning curve: Q-learning vs random and hill-climb baselines](images/fig2_learning_curve.png)

The green line is the greedy Q-learning policy evaluated during training (mean +/- SD over 5 seeds). The dashed lines are the random baseline and the hill-climbing heuristic. The dotted line is the best possible yield (95%).

| Method | Avg yield per experiment (%) | Final-experiment yield (%) | Best yield found (%) | Unsafe experiments (%) |
|---|---|---|---|---|
| Random | 15.5 | 15.4 | 49.7 | 20.1 |
| Hill-climb heuristic | 27.0 | 31.6 | 70.0 | 11.5 |
| **Q-learning (RL)** | **78.5** | **85.8** | **95.0** | **0.4** |

![RL vs baselines](images/fig3_comparison.png)

## Files
- `RL_Homework2_SelfDrivingLab.ipynb` - full Google Colab implementation
- `RL_Homework2_Presentation.pptx` - presentation slides
- `RL_Homework2_Manual.docx` - project manual (formulation, code, outputs)
