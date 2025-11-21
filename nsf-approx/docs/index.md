# Approximation and Randomization in the Programmable Data Planes

## Overview

The rise of the programmable data plane opens the door to entirely new approaches to networking. The programmable data plane allows operators to define their own packet headers and specify how the data plane should process these headers or add new headers. The programmable data plane enables a wide range of applications, including not only traditional forwarding, routing, and load-balancing tasks, but also new methods for advanced monitoring and troubleshooting. They also become new platforms for in-network computing that can accelerate distributed applications, database queries, and machine learning.

However, the programmable data plane is now and for the foreseeable future will be highly constrained, as various activities draw on their memory and computational resources, and work must be done at line rate. Because of their constrained nature, programmable switches are natural targets for approximation algorithms and randomized algorithms. Approximation algorithms provide an answer that is only approximately correct, and randomized algorithms may only be correct with high probability or introduce other randomness in their performance, such as requiring a variable amount of latency. Utilizing approximate and randomized algorithms can greatly reduce the resource requirements while still providing suitably effective results for handling real-world problems.

## Research Goals

The research focus for this project is the design and analysis of systems for the programmable data plane that use approximation and randomization to reduce resource complexity while providing solutions for network problems. Particular areas of focus are the following:

1. **Theoretical Framework**: Devising theoretical formalizations that provide a framework for designing algorithms in current and future switch architectures, with the goal of influencing future development of switches.

2. **Novel Algorithms**: Designing novel methods and algorithms for distributed network applications, making use of the programmable data plane. In particular, we aim to improve network telemetry approaches, but we also plan to attack additional applications.

3. **Utility Libraries**: Providing libraries of utilities, from low-level functions to higher-level data structures and algorithms, for approximation algorithms and randomized algorithms in switch architectures.

These three focus areas provide a synergistic virtuous circle. We plan to utilize theoretical models to build general code libraries for this setting, allowing more rapid development of results for specific applications. In turn, this will lead to improvements and expansion of the theoretical model and library code, creating a positive feedback loop for this line of research.

---

<div style="text-align: center; margin: 40px 0;">
  <img src="https://www.seas.harvard.edu/sites/default/files/images/H_SEAS_logo_RGB_1.jpg" alt="Harvard SEAS logo" style="max-width: 250px; opacity: 0.9;">
</div>
