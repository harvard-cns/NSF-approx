# Code

## Open Source Projects

### NEO: CPU Offloading for Online LLM Inference

**Repository**: [https://github.com/NEO-MLSys25/NEO](https://github.com/NEO-MLSys25/NEO)

NEO is an online LLM inference system that offloads part of attention compute and KV cache states from the GPU to the local host CPU, effectively increasing the GPU batch size and thus inference throughput. The system implements asymmetric GPU-CPU pipelining and load-aware scheduling to balance GPU and CPU loads and fully utilize their compute and memory resources.

**Features:**
- Asymmetric GPU-CPU pipelining
- Load-aware scheduling
- Support for multiple GPU models (T4, A10G, H100)
- Support for various LLM models (7B, 8B, 70B)
- Evaluation on diverse workloads (code generation, text summarization)

## Research Tools and Libraries

This project is developing libraries of utilities, from low-level functions to higher-level data structures and algorithms, for approximation algorithms and randomized algorithms in switch architectures. These libraries will be made available as the research progresses.

## Availability

For access to additional code repositories and software tools developed as part of this project, please contact the project investigators.

