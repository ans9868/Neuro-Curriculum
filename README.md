# Neuronal Dynamics Self-Study Curriculum

An 8-week self-guided study plan based on Wulfram Gerstner's **Neuronal Dynamics** course at EPFL.

---

## Resources

| Resource | Link |
|----------|------|
| **Video Lectures** | [MOOC All Lectures](https://lcnwww.epfl.ch/gerstner/NeuronalDynamics-MOOCall.html) |
| **Online Textbook** | [Neuronal Dynamics Online](https://neuronaldynamics.epfl.ch/online/) |
| **Python Exercises** | [Exercise Documentation](https://neuronaldynamics-exercises.readthedocs.io/) |
| **edX Course (Free Audit)** | [EPFL Neuronal Dynamics on edX](https://www.edx.org/learn/neuroscience/ecole-polytechnique-federale-de-lausanne-neuronal-dynamics) |
| **Teaching Materials** | [Lecture Slides & Materials](https://neuronaldynamics.epfl.ch/lectures.html) |

---

## Weekly Study Routine

| Day | Activity |
|-----|----------|
| Monday | Watch video lectures |
| Tuesday | Read textbook chapters |
| Wednesday | Generate NotebookLM podcast from Nicholls chapters |
| Thursday | Review notes, revisit difficult concepts |
| Friday | Complete Python exercises |

---

## Week 1: Introduction & The Leaky Integrate-and-Fire Model

**Estimated Time:** ~5 hours

### Video Lecture 1: A First Simple Neuron Model (83 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Neurons and Synapses: Overview | 10 min | [Watch](https://youtu.be/f_9UE5P3KCo) |
| 2 | The Passive Membrane | 21 min | [Watch](https://youtu.be/-XBMpgdYCZY) |
| Math | Linear Differential Equation | 22 min | [Watch](https://youtu.be/3YGbIQUoz7o) |
| 3 | Leaky Integrate-and-Fire Model | 8 min | [Watch](https://youtu.be/KGxVwJJC9zs) |
| 4 | Generalized Integrate-and-Fire Models | 17 min | [Watch](https://youtu.be/5wNNPv1eBFM) |
| 5 | Quality of Integrate-and-Fire Models | 5 min | [Watch](https://youtu.be/vHUUcPRqzCk) |

### Textbook Reading

- [Chapter 1: Introduction - Neurons and Mathematics](https://neuronaldynamics.epfl.ch/online/Ch1.html)
  - [1.1 Elements of Neuronal Systems](https://neuronaldynamics.epfl.ch/online/Ch1.S1.html)
  - [1.2 Elements of Neuronal Dynamics](https://neuronaldynamics.epfl.ch/online/Ch1.S2.html)
  - [1.3 Integrate-And-Fire Models](https://neuronaldynamics.epfl.ch/online/Ch1.S3.html)
  - [1.4 Limitations of the Leaky Integrate-and-Fire Model](https://neuronaldynamics.epfl.ch/online/Ch1.S4.html)
  - [1.5 What Can We Expect from Integrate-And-Fire Models?](https://neuronaldynamics.epfl.ch/online/Ch1.S5.html)

### Key Concepts
- Membrane potential and resting potential
- RC circuit analogy
- Leaky integrate-and-fire (LIF) neuron model
- Spike threshold and reset mechanism

---

## Week 2: The Hodgkin-Huxley Model

**Estimated Time:** ~5 hours

### Video Lecture 2: The Hodgkin-Huxley Model (77 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Biophysics of Neurons | 5 min | [Watch](https://youtu.be/VrDCb4ldjD0) |
| 2 | Reversal Potential and Nernst Equation | 11 min | [Watch](https://youtu.be/mqhlMOWl7NM) |
| 3 | Hodgkin-Huxley Model | 23 min | [Watch](https://youtu.be/ZX1skUJbBpc) |
| 4 | Threshold in the Hodgkin-Huxley Model | 26 min | [Watch](https://youtu.be/Y7qK7FTObp0) |
| 5 | Detailed Biophysical Models | 12 min | [Watch](https://youtu.be/fsYrmQAmApA) |

### Textbook Reading

- [Chapter 2: Ion Channels and the Hodgkin-Huxley Model](https://neuronaldynamics.epfl.ch/online/Ch2.html)
  - [2.1 Equilibrium Potential](https://neuronaldynamics.epfl.ch/online/Ch2.S1.html)
  - [2.2 Hodgkin-Huxley Model](https://neuronaldynamics.epfl.ch/online/Ch2.S2.html)
  - [2.3 The Zoo of Ion Channels](https://neuronaldynamics.epfl.ch/online/Ch2.S3.html)

### Key Concepts
- Nernst equation and reversal potentials
- Voltage-gated ion channels (Na⁺, K⁺)
- Gating variables (m, h, n)
- Action potential generation mechanism

---

## Week 3: Synapses, Dendrites, and the Cable Equation

**Estimated Time:** ~5 hours

### Video Lecture 3: Synapses, Dendrites and the Cable Equation (69 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Synapses | 15 min | [Watch](https://youtu.be/bHI92afcwzc) |
| 2 | Synaptic Short-Term Plasticity | 9 min | [Watch](https://youtu.be/a5XPQMAX3ak) |
| 3a | Dendrite as a Cable | 11 min | [Watch](https://youtu.be/u6D88OnxaNo) |
| 3b | Derivation of the Cable Equation | 10 min | [Watch](https://youtu.be/AEdFzpzW7d8) |
| 4 | Cable Equation | 10 min | [Watch](https://youtu.be/7HZLULwAAk0) |
| 5 | Compartmental Models | 14 min | [Watch](https://youtu.be/v1f1RShatNM) |

### Textbook Reading

- [Chapter 3: Dendrites and Synapses](https://neuronaldynamics.epfl.ch/online/Ch3.html)
  - [3.1 Synapses](https://neuronaldynamics.epfl.ch/online/Ch3.S1.html)
  - [3.2 Spatial Structure: The Dendritic Tree](https://neuronaldynamics.epfl.ch/online/Ch3.S2.html)
  - [3.3 Spatial Structure: Axons](https://neuronaldynamics.epfl.ch/online/Ch3.S3.html)
  - [3.4 Compartmental Models](https://neuronaldynamics.epfl.ch/online/Ch3.S4.html)

### Key Concepts
- Excitatory vs inhibitory synapses (AMPA, NMDA, GABA)
- Synaptic facilitation and depression
- Cable equation and electrotonic spread
- Multi-compartment neuron models

---

## Week 4: Phase Plane Analysis & Bifurcations

**Estimated Time:** ~6-7 hours

### Video Lecture 4: Two-Dimensional Models and Phase Plane Analysis (165 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | From Hodgkin-Huxley to 2D | 18 min | [Watch](https://youtu.be/R8iSyZya7UI) |
| Math 1 | Separation of Time Scales | 11 min | [Watch](https://youtu.be/CTT8dqDxwKY) |
| Math 2 | Exploiting Similarities | 16 min | [Watch](https://youtu.be/h00-7Etjbbc) |
| 2 | Phase Plane Analysis | 17 min | [Watch](https://youtu.be/_63Y2qiUqbI) |
| 3a | Analysis of a 2D Neuron Model - Pulse Input | 12 min | [Watch](https://youtu.be/Y2DDXL2piMs) |
| 3b | Analysis of a 2D Neuron Model - Constant Input | 9 min | [Watch](https://youtu.be/SCOJ8E3Sdr8) |
| Math 3 | Stability of Fixed Points | 19 min | [Watch](https://youtu.be/lKmkC6LX9so) |
| 4a | Type I and Type II Neuron Models | 16 min | [Watch](https://youtu.be/INoKDWDSWGE) |
| 4b | Firing Threshold in 2D Models | 21 min | [Watch](https://youtu.be/aa1VuFCvuW8) |
| 5 | Nonlinear Integrate-and-Fire Model | 16 min | [Watch](https://youtu.be/79SrvG2QdD4) |

### Textbook Reading

- [Chapter 4: Dimensionality Reduction and Phase Plane Analysis](https://neuronaldynamics.epfl.ch/online/Ch4.html)
  - [4.1 Threshold Effects](https://neuronaldynamics.epfl.ch/online/Ch4.S1.html)
  - [4.2 Reduction to Two Dimensions](https://neuronaldynamics.epfl.ch/online/Ch4.S2.html)
  - [4.3 Phase Plane Analysis](https://neuronaldynamics.epfl.ch/online/Ch4.S3.html)
  - [4.4 Type I and Type II Neuron Models](https://neuronaldynamics.epfl.ch/online/Ch4.S4.html)
  - [4.5 Threshold and Excitability](https://neuronaldynamics.epfl.ch/online/Ch4.S5.html)
- [Chapter 5: Nonlinear Integrate-and-Fire Models](https://neuronaldynamics.epfl.ch/online/Ch5.html)

### Key Concepts
- Nullclines and fixed points
- Saddle-node and Hopf bifurcations
- FitzHugh-Nagumo model
- Type I vs Type II neurons

---

## Week 5: Variability and Noise in Spike Trains

**Estimated Time:** ~6 hours

### Video Lecture 5: Variability of Spike Trains (96 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Variability of Spike Trains | 6 min | [Watch](https://youtu.be/j1fSsbTn6Dg) |
| 2 | Sources of Variability | 10 min | [Watch](https://youtu.be/QWJFdLhO7cA) |
| 3a | Three Definitions of Rate Code | 12 min | [Watch](https://youtu.be/mxWVwtQV3jg) |
| 3b | Poisson Model, Survivor Function, and Interval Distribution | 15 min | [Watch](https://youtu.be/66DsRqpPpfI) |
| Math | Poisson Process - A Modern Approach | 20 min | [Watch](https://youtu.be/uc71aoGcU_M) |
| 4a | Stochastic Spike Arrival | 15 min | [Watch](https://youtu.be/IN_tPV_5Qsk) |
| 4b | Membrane Potential Fluctuations | 13 min | [Watch](https://youtu.be/VOkgb7AVPac) |
| 5 | Stochastic Spike Firing in Integrate-and-Fire Models | 5 min | [Watch](https://youtu.be/UWRMK51TRwk) |

### Video Lecture 6: Noise Models (84 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Escape Noise | 15 min | [Watch](http://www.youtube.com/watch?v=xAwBbDAVtgw) |
| 2 | Interspike Intervals & Renewal Processes | 29 min | [Watch](http://www.youtube.com/watch?v=TEc428h0nxQ) |
| 3 | Likelihood of a Spike Train | 18 min | [Watch](http://www.youtube.com/watch?v=LT0KRaotIxo) |
| 4a | Comparison of Noise Models | 19 min | [Watch](http://www.youtube.com/watch?v=MLX0eH4mEcQ) |
| 4b | From Diffuse Noise to Escape Noise | 7 min | [Watch](http://www.youtube.com/watch?v=ArG4LFp_MXY) |
| 5 | Rate Codes versus Temporal Codes | 6 min | [Watch](http://www.youtube.com/watch?v=aSz3KRmago4) |

### Textbook Reading

- [Chapter 7: Variability of Spike Trains and Neural Codes](https://neuronaldynamics.epfl.ch/online/Ch7.html)
  - [7.1 Spike Train Variability](https://neuronaldynamics.epfl.ch/online/Ch7.S1.html)
  - [7.2 Mean Firing Rate](https://neuronaldynamics.epfl.ch/online/Ch7.S2.html)
  - [7.3 Interval Distribution and Coefficient of Variation](https://neuronaldynamics.epfl.ch/online/Ch7.S3.html)
  - [7.5 Renewal Statistics](https://neuronaldynamics.epfl.ch/online/Ch7.S5.html)
  - [7.6 The Problem of Neural Coding](https://neuronaldynamics.epfl.ch/online/Ch7.S6.html)
- [Chapter 8: Noisy Input Models](https://neuronaldynamics.epfl.ch/online/Ch8.html)
- [Chapter 9: Noisy Output - Escape Rate and Soft Threshold](https://neuronaldynamics.epfl.ch/online/Ch9.html)

### Key Concepts
- Poisson processes and spike train statistics
- Fano factor and coefficient of variation (CV)
- Rate codes vs temporal codes
- Input noise vs output noise models

---

## Week 6: Phenomenological Models, GLMs, and Decoding

**Estimated Time:** ~5 hours

### Video Lecture 7: Modern Phenomenological Neuron Models (94 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Models and Data | 11 min | [Watch](http://www.youtube.com/watch?v=deLI1c11edk) |
| 2a | AdEx: Adaptive Exponential Integrate-and-Fire | 11 min | [Watch](http://www.youtube.com/watch?v=u8qwboY-zA4) |
| 2b | Firing Patterns and Phase Plane Analysis | 10 min | [Watch](http://www.youtube.com/watch?v=GbXAf0iMvzs) |
| 3 | Spike Response Model (SRM) | 15 min | [Watch](http://www.youtube.com/watch?v=HfSZzKvDV5s) |
| 4 | Generalized Linear Model (GLM) | 7 min | [Watch](http://www.youtube.com/watch?v=NfY2xY4mMxk) |
| 5a | Parameter Estimation | 14 min | [Watch](http://www.youtube.com/watch?v=vcQmXzcyP_s) |
| 5b | Parameter Estimation for Spike Times | 7 min | [Watch](http://www.youtube.com/watch?v=cUe-O6hXFQs) |
| 6 | Modeling In Vitro Data | 8 min | [Watch](http://www.youtube.com/watch?v=uu8Il59moS4) |
| 7 | Helping Humans (BCI applications) | 11 min | [Watch](http://www.youtube.com/watch?v=8QvJy0pCnUw) |

### Textbook Reading

- [Chapter 6: Adaptation and Firing Patterns](https://neuronaldynamics.epfl.ch/online/Ch6.html)
  - [6.1 Adaptive Exponential Integrate-and-Fire](https://neuronaldynamics.epfl.ch/online/Ch6.S1.html)
  - [6.2 Firing Patterns](https://neuronaldynamics.epfl.ch/online/Ch6.S2.html)
  - [6.4 Spike Response Model (SRM)](https://neuronaldynamics.epfl.ch/online/Ch6.S4.html)
- [Chapter 10: Estimating Parameters of Probabilistic Neuron Models](https://neuronaldynamics.epfl.ch/online/Ch10.html)
- [Chapter 11: Encoding and Decoding with Stochastic Neuron Models](https://neuronaldynamics.epfl.ch/online/Ch11.html)
  - [11.3 Decoding](https://neuronaldynamics.epfl.ch/online/Ch11.S3.html) ← **Key for BCI applications**

### Key Concepts
- Adaptive exponential integrate-and-fire (AdEx) model
- Generalized Linear Models (GLMs)
- Maximum likelihood parameter estimation
- Neural encoding and decoding for BCIs

---

## Week 7: Networks and Population Activity

**Estimated Time:** ~6 hours

### Video Lecture 8: Neuronal Populations (85 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Population Activity | 9 min | [Watch](https://youtu.be/SHHBnwhe8G0) |
| 2 | Cortical Populations: Columns and Receptive Fields | 7 min | [Watch](https://youtu.be/RsobjAGj3MM) |
| 3 | Connectivity - In Cortex and In Models | 11 min | [Watch](https://youtu.be/U-i-yFprinU) |
| 4a | Asynchronous State | 13 min | [Watch](https://youtu.be/M_CZgL4gs_o) |
| 4b | Mean-Field Argument | 10 min | [Watch](https://youtu.be/YwwW793IwbM) |
| 5 | Stationary Mean-Field and Asynchronous State | 16 min | [Watch](https://youtu.be/XFGDKC3GZJU) |
| 6 | Random Networks and Balanced State | 21 min | [Watch](https://youtu.be/unry1tVPxtQ) |

### Video Lecture 9: Fokker-Planck Equation (77 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Integrate-and-Fire Neurons Driven by Stochastic Spike Arrival | 6 min | [Watch](https://youtu.be/MlnkJRSXQgQ) |
| 2 | Continuity Equation/Transport Equation | 15 min | [Watch](https://youtu.be/fvCLTvXi-hU) |
| 3 | The Flux of Membrane Potential Trajectories | 7 min | [Watch](https://youtu.be/jc11i7crets) |
| 4 | Derivation of the Fokker-Planck Equation | 16 min | [Watch](https://youtu.be/vPrDNKEJRM8) |
| 5 | Fokker-Planck Equation with Threshold | 15 min | [Watch](https://youtu.be/WWrWjyURCtw) |
| 5B | Quiz on Fokker-Planck Equation | 6 min | [Watch](https://youtu.be/_6JXlVu-VmY) |
| 6 | Random Network of Integrate-and-Fire Neurons | 12 min | [Watch](https://youtu.be/VUJgMZAhe-Q) |

### Textbook Reading

- [Chapter 12: Neuronal Populations](https://neuronaldynamics.epfl.ch/online/Ch12.html)
  - [12.1 Columnar Organization](https://neuronaldynamics.epfl.ch/online/Ch12.S1.html)
  - [12.2 Identical Neurons: A Mathematical Abstraction](https://neuronaldynamics.epfl.ch/online/Ch12.S2.html)
  - [12.3 Connectivity Schemes](https://neuronaldynamics.epfl.ch/online/Ch12.S3.html)
  - [12.4 From Microscopic to Macroscopic](https://neuronaldynamics.epfl.ch/online/Ch12.S4.html)
- [Chapter 13: Continuity Equation and the Fokker-Planck Approach](https://neuronaldynamics.epfl.ch/online/Ch13.html)

### Key Concepts
- Population activity and mean-field theory
- Balanced excitation/inhibition networks
- Asynchronous irregular (AI) state
- Fokker-Planck equation for neuronal populations

---

## Week 8: Plasticity, Memory, and Decision Making

**Estimated Time:** ~7 hours

### Video Lecture 10: Associative Memory (57 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Introduction: Human Memory and Networks of Neurons | 4 min | [Watch](https://youtu.be/mcKSjxpM5rw) |
| 2 | Classification by Similarity | 5 min | [Watch](https://youtu.be/VWCGQX8HiKw) |
| 3 | Detour: Magnetic Materials | 9 min | [Watch](https://youtu.be/W45Z-BDmDs0) |
| 4 | Hopfield Model | 15 min | [Watch](https://youtu.be/Xld6cw3y5q8) |
| 5 | Learning of Associations | 9 min | [Watch](https://youtu.be/zTOaBMsG_0s) |
| 6 | Storage Capacity | 15 min | [Watch](https://youtu.be/yCnl8eNsfYY) |

### Video Lecture 11: Attractor Networks (62 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Attractor Networks | 8 min | [Watch](https://youtu.be/9LjFqc2JRk4) |
| 2 | Stochastic Hopfield Model | 18 min | [Watch](https://youtu.be/3xyVZ3wGUZE) |
| 3 | Energy Landscape | 14 min | [Watch](https://youtu.be/crfvN52dsr0) |
| 4 | Toward Biology 1: Low-Activity Patterns | 6 min | [Watch](https://youtu.be/-zwwVqzZjPs) |
| 5 | Toward Biology 2: Spiking Neurons | 16 min | [Watch](https://youtu.be/zR3Bq8ysOsg) |

### Video Lecture 14: Synaptic Plasticity and Learning (85 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Synaptic Plasticity: Motivation and Aims | 6 min | [Watch](https://youtu.be/YM3eUm36cIA) |
| 2 | Classification of Plasticity | 17 min | [Watch](https://youtu.be/MuNw-ZlS6_4) |
| 3 | Model of Short-Term Plasticity | 1 min | [Watch](https://youtu.be/Vn-qpKT6sGQ) |
| 3B | Synaptic Short-Term Plasticity (Earlier MOOC) | 9 min | [Watch](https://youtu.be/a5XPQMAX3ak) |
| 4 | Models of Long-Term Plasticity: Hebbian Learning & BCM Rule | 17 min | [Watch](https://youtu.be/IQUtzeotabc) |
| 5 | STDP: Spike-Timing Dependent Plasticity | 11 min | [Watch](https://youtu.be/z4vZTeTGiVQ) |
| 6 | From Spiking Plasticity Models to Rate Models | 9 min | [Watch](https://youtu.be/LrzHKIMunFw) |
| 6b | Math Detour: From Spiking to Rate Models | 27 min | [Watch](https://youtu.be/PUTOf8aBQaw) |
| 7 | Triplet STDP Model | 11 min | [Watch](https://youtu.be/EsP5mX04jZs) |
| 8 | Online Learning of Memories | 15 min | [Watch](https://youtu.be/MSgbOvqFWws) |

### Textbook Reading

- [Chapter 17: Synaptic Plasticity and Learning](https://neuronaldynamics.epfl.ch/online/Ch17.html) *(Note: Chapter numbering may vary in online version)*
- [Chapter 19: Decision Making](https://neuronaldynamics.epfl.ch/online/Ch19.html)

### Key Concepts
- Hopfield networks and attractor dynamics
- Energy landscape and memory retrieval
- Hebbian learning ("fire together, wire together")
- Spike-timing dependent plasticity (STDP)
- Bienenstock-Cooper-Munro (BCM) rule

---

## Bonus: Neural Manifolds (Optional Advanced Topic)

### Video Lecture 15: Neural Manifolds and Low-Dimensional Dynamics (39 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | What are Neural Manifolds? | 9 min | [Watch](https://mediaspace.epfl.ch/media/What%20is%20a%20Neural%20Manifold/0_ok6gwdej) |
| 2 | Two Views of Neural Activity in the Brain | 15 min | [Watch](https://mediaspace.epfl.ch/media/Two%20views%20of%20neural%20activity%20in%20the%20brain/0_q1vtm0vd) |
| 3 | Low-Rank Recurrent Neural Networks | 15 min | [Watch](https://mediaspace.epfl.ch/media/Low-rank%20recurrent%20neural%20networks/0_o05h1k91) |

---

## Additional Lectures (Decision Making, Perception)

### Video Lecture 12: Continuum Models - Cortical Fields and Perception (62 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Aims and Challenges for this Chapter | 7 min | [Watch](https://youtu.be/7UW24UYtkCg) |
| 2 | Transients | 16 min | [Watch](https://youtu.be/xwr6lerXbMk) |
| 3 | Spatial Continuum (Cortex) | 3 min | [Watch](https://youtu.be/eZtMmPyO5M0) |
| 4 | Spatial Continuum (Model) | 18 min | [Watch](https://youtu.be/f2tadlvuhcg) |
| 5 | Solution Types | 8 min | [Watch](https://youtu.be/iEQxmhs3e0w) |
| 6 | Perception | 10 min | [Watch](https://youtu.be/Vh93h77B8rk) |

### Video Lecture 13: Decision Models - Competitive Dynamics (66 min)

| Part | Topic | Duration | Link |
|------|-------|----------|------|
| 1 | Introduction: Aims and Challenges of Decision Models | 18 min | [Watch](https://youtu.be/sT-XepFxq7o) |
| 2 | Perceptual Decision Making | 15 min | [Watch](https://youtu.be/kLBnY-COlMo) |
| 3 | Theory of Decision Dynamics (Cortex) | 11 min | [Watch](https://youtu.be/MtthfGUKEqU) |
| 4 | Solutions of Decision Dynamics: Symmetric and Biased Case | 8 min | [Watch](https://youtu.be/7la4FoA--lM) |
| 5 | Simulations and Experiments on Decision Dynamics | 8 min | [Watch](https://youtu.be/9T0sukbGOXA) |
| 6 | Decisions, Actions, Volition | 6 min | [Watch](https://youtu.be/yAxhhwz5SP8) |

---

## Quick Reference: All Textbook Chapters

| Part | Chapter | Link |
|------|---------|------|
| **I. Foundations** | 1. Introduction | [Ch 1](https://neuronaldynamics.epfl.ch/online/Ch1.html) |
| | 2. Hodgkin-Huxley Model | [Ch 2](https://neuronaldynamics.epfl.ch/online/Ch2.html) |
| | 3. Dendrites and Synapses | [Ch 3](https://neuronaldynamics.epfl.ch/online/Ch3.html) |
| | 4. Phase Plane Analysis | [Ch 4](https://neuronaldynamics.epfl.ch/online/Ch4.html) |
| **II. Generalized IF** | 5. Nonlinear IF Models | [Ch 5](https://neuronaldynamics.epfl.ch/online/Ch5.html) |
| | 6. Adaptation and Firing Patterns | [Ch 6](https://neuronaldynamics.epfl.ch/online/Ch6.html) |
| | 7. Variability and Neural Codes | [Ch 7](https://neuronaldynamics.epfl.ch/online/Ch7.html) |
| | 8. Noisy Input Models | [Ch 8](https://neuronaldynamics.epfl.ch/online/Ch8.html) |
| | 9. Noisy Output: Escape Rate | [Ch 9](https://neuronaldynamics.epfl.ch/online/Ch9.html) |
| | 10. Estimating Models | [Ch 10](https://neuronaldynamics.epfl.ch/online/Ch10.html) |
| | 11. Encoding and Decoding | [Ch 11](https://neuronaldynamics.epfl.ch/online/Ch11.html) |
| **III. Networks** | 12. Neuronal Populations | [Ch 12](https://neuronaldynamics.epfl.ch/online/Ch12.html) |
| | 13. Fokker-Planck Approach | [Ch 13](https://neuronaldynamics.epfl.ch/online/Ch13.html) |

---

## Python Exercises

Install the exercise package:
```bash
pip install neurodynex3
```

Documentation: [neuronaldynamics-exercises.readthedocs.io](https://neuronaldynamics-exercises.readthedocs.io/)

---

*Last updated: March 2026*
