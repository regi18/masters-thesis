# Robust Control for an Avian-Inspired Drone

Master’s thesis conducted at **EPFL** – Laboratory of Intelligent Systems (**LIS**).

- Title: **L1-Adaptive augmentation for robust morphing-wing drone flight control**
- Supervisors: Wanner Julius, Jeger Simon, Averta Giuseppe, Floreano Dario

<!-- ## 📌 Overview
Agile flight presents significant control challenges, especially for morphing drones subject to complex and uncertain aerodynamic effects. While Reinforcement Learning (RL) enables highly agile behaviors, direct low-level control through RL policies often lacks robustness when faced with model mismatches and disturbances. This project investigates how to stabilize and enhance RL-based controllers using adaptive control techniques. -->




# Summary

A 3 page summary is available here [Masters_Thesis_CARLETTI__Summary.pdf](Masters_Thesis_CARLETTI__Summary.pdf)

<a href="Masters_Thesis_CARLETTI__Summary" target="_blank">
  <img src="https://github.com/user-attachments/assets/f413e4de-2c32-4357-b743-8e3cd7af936e" alt="thesis-thumbnail" width="900" />
</a>


# Abstract

Agile flight in cluttered environments presents unique control challenges, particularly for morphing drones subject to complex aerodynamic interactions. While Reinforcement Learning (RL) has emerged as a powerful tool for generating agile control policies, direct actuator control via RL often suffers from a lack of robustness due to model discrepancies, wind disturbances, and ground effects.

This work addresses these limitations by investigating robust control strategies that augment or stabilize RL-based policies. Drawing on techniques proven in quadrotors and fighter aircrafts, we explore the implementation of Model Reference Adaptive Control (MRAC) methods, specifically L1-Adaptive Control (L1AC), to compensate for model discrepancies in real time.

We show that L1 effectively compensates model mismatches, thereby enforcing a consistent dynamic behavior that aligns with the nominal model. We also evaluate how L1 adds to Domain Randomization (DR), specifically investigating whether the combination of offline robust training (via DR) and online adaptation (via L1) outperforms either method individually.

Simulation and experimental results are obtained on morphing drone prototypes developed at EPFL’s Laboratory of Intelligent Systems (LIS), demonstrating the effectiveness of the proposed approach in realistic flight conditions.

<br>

**Keywords**: *Adaptive Control, Reinforcement Learning, L1 AC, Sim-to-Real, Morphing Drone*
