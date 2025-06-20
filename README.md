## AI Mathematical Olympiad Progress Prize 2 (AIMO2) Solution

This repository contains my solution for the AI Mathematical Olympiad Progress Prize 2 competition on Kaggle, focusing on solving mathematical olympiad problems using large language models.

### Competition Overview

The AIMO2 competition challenges participants to develop AI systems capable of solving complex mathematical problems typically found in olympiad competitions.

### Problem Description

- **Task**: Solve mathematical olympiad-style problems across various domains (algebra, geometry, number theory, combinatorics)
- **Input**: Text-based mathematical problem statements
- **Output**: Numerical answers (modulo 1000 when applicable)
- **Evaluation**: Correctness of final answers

### Model Selection
- **Primary Model**: DeepSeek-R1 Distill Qwen-7B-AWQ (quantized version)
- **Framework**: vLLM for efficient inference with tensor parallelism
- **Hardware**: 4x GPU setup with distributed execution

### Setup and Execution
#### Prerequisites
- Python 3.8+
- CUDA-compatible GPUs (4x recommended)
- 32GB+ GPU memory total
- vLLM framework
#### Installation
- git clone https://github.com/lakshmiprasanna07/aimo2.git
- cd aimo2
- pip install -r requirements.txt
#### Running the solution
jupyter notebook main.ipynb
### License
This project is licensed under the MIT License - see the LICENSE file for details.
### Contact
For questions about the implementation or collaboration opportunities, please open an issue or contact lakshmiprasanna.lp07@gmail.com
