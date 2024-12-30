# HIM-24: Model-Based Game Difficulty Optimization
## Title : [Balancing the Impossible: Understanding Human Performance in Multitasking Challenges](https://github.com/hak3601/HIM-24/blob/main/paper.pdf)

## Overview

This project, **HIM-24**, focuses on optimizing task difficulty in a dual-task balancing game. Using concepts from the *Modeling Interaction* class, our team developed a predictive model to estimate player performance based on game difficulty, enabling personalized and enjoyable gaming experiences.


## Objectives

The primary goal is to ensure players enjoy the game by dynamically adjusting the difficulty level to maintain an appropriate level of challenge for each individual.


## Game Design

- A **3D balance-maintenance game** where players tilt a disc to keep a ball from falling off.
- Players control one disc at a time using:
  - **Arrow keys** for tilting.
  - **Tab key** to switch between discs.


## Predictive Model Development

Our predictive model dynamically adjusts game parameters (e.g., target size, speed) to ensure balanced performance across players. This enhances both fairness and engagement by aligning difficulty levels with individual capabilities.

### Development Guidelines

1. **Select a Game for Optimization**  
   Choose a simple game (e.g., Whack-a-Mole, rhythm games, brick-breaking games) for easier modeling.

2. **Identify Game Features**  
   Analyze game characteristics (e.g., 1-D or 2-D interaction, spatial or temporal targets).

3. **Define Performance Metrics**  
   Establish measurable dependent variables (e.g., score, completion time, accuracy).

4. **Set Independent Variables**  
   Identify adjustable in-game variables (e.g., target speed, size, spacing).

5. **Implement Data Collection**  
   Develop an interface to record independent variable data during gameplay.

6. **Collect Gameplay Data**  
   Gather data to analyze the relationship between variables and player performance.

7. **Build the Predictive Model**  
   Use collected data to create a model that adjusts difficulty dynamically for each player.


## Key Findings

- **Game Parameters**: Ball velocity and plate radius significantly affect task completion time.
- **Experimental Design**: A within-subject setup with six configurations combining two ball velocities (high, low) and three plate radii (small, medium, large).
- **Performance Metric**: Task completion time was analyzed using repeated measures ANOVA.
- **Model Performance**: The predictive model achieved:
  - **MSE**: 7.2992
  - **R² Score**: 0.7657


## Conclusion

The Dual-Task Balancing Game served as the principal platform for optimizing task difficulty. By integrating the proposed Index of Difficulty (ID), the predictive model reliably achieved performance durations within the 20–30 second range when using parameter settings recommended by the model.

Although determining an optimal target duration was challenging, user feedback indicated a preference for the widest disc configuration due to perceived excessive difficulty in other conditions. As a result, target durations were adjusted to align with participants’ comfort levels.

These findings underscore the efficacy of the predictive model in identifying and refining the game’s difficulty. The model facilitates more adaptable and user-centered gameplay experiences, enabling fair and engaging challenges for all players.

---
## Note

You can access the full paper [here](https://github.com/hak3601/HIM-24/blob/main/paper.pdf). Please note that this paper is a report formatted in ACM style, created as a learning exercise to gain experience in writing a formal research paper.

---

## Team 

Sumin Kim, *Htet Arkar*, Suho Moon, Yejin Jang

---
## Reference

Lingler, Alexander, et al. "Supporting Task Switching with Reinforcement Learning." *Proceedings of the CHI Conference on Human Factors in Computing Systems*. 2024.(https://dl.acm.org/doi/pdf/10.1145/3613904.3642063)

