#CUDAForge

**Training and Evaluation for CUDA Coding Agents**

CUDAForge is an open-source research project exploring how to train and evaluate coding models that generate, debug, and optimize CUDA kernels under limited compute budgets.

### Objectives
- Establish reproducible baselines for small coding models on CUDA tasks.
- Verify generated kernels through compilation and execution.
- Measure correctness separately from runtime and performance.
- Explore supervised fine-tuning (SFT) using verified examples.
- Evaluate whether reinforcement learning, including GRPO, improves performance beyond SFT.
- Report compute costs, held-out results, and limitations transparently.

### Roadmap
1. Review existing projects, datasets, benchmarks, and licenses.
2. Select a small task set and establish a baseline.
3. Build a verified training dataset and test parameter-efficient SFT.
4. Develop a bounded agent execution loop with compilation and testing tools.
5. Run RL experiments only when baseline results justify the cost.
6. Publish reproducible experiments, configurations, code, and results.

**Current status:** Early-stage research and feasibility planning. No training improvements or benchmark results are claimed yet.
