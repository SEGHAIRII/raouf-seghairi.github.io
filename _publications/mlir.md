---
title: "Automatic Code Optimization using Reinforcement Learning in the MLIR Compiler."
collection: publications
category: technical_reports
permalink: /publication/mlir-optim
excerpt: "This technical report presents the design and implementation of a Monte Carlo Tree Search (MCTS)–based auto-scheduler for the MLIR compiler, aimed at improving automatic code optimization through efficient exploration of transformation spaces. The proposed method models the optimization process as a hierarchical search problem, where transformations such as tiling, parallelization, interchange, and vectorization are represented as nodes within a dynamic search tree. By leveraging the MCTS algorithm, the system balances exploration and exploitation to identify high-performing optimization schedules without exhaustive search. The implementation integrates evaluation-by-execution to provide accurate performance feedback, ensuring reliable reward estimation for each transformation path. Experimental results on matrix multiplication and convolution benchmarks demonstrate significant performance gains—achieving up to 4× reductions in execution time compared to unoptimized baselines—while maintaining generality and extensibility within the MLIR framework. This work highlights the potential of combining heuristic search and compiler optimization techniques to build adaptive and scalable auto-schedulers, paving the way for future integration with reinforcement learning–driven optimization systems."
date: November 2024
Status: 'Technical report' 
paperurl: 'https://www.researchgate.net/publication/396448821_Automatic_Code_Optimization_using_Reinforcement_Learning_in_the_MLIR_Compiler'

citation: ''
---
This technical report presents the design and implementation of a Monte Carlo Tree Search (MCTS)–based auto-scheduler for the MLIR compiler, aimed at improving automatic code optimization through efficient exploration of transformation spaces. The proposed method models the optimization process as a hierarchical search problem, where transformations such as tiling, parallelization, interchange, and vectorization are represented as nodes within a dynamic search tree. By leveraging the MCTS algorithm, the system balances exploration and exploitation to identify high-performing optimization schedules without exhaustive search. The implementation integrates evaluation-by-execution to provide accurate performance feedback, ensuring reliable reward estimation for each transformation path. Experimental results on matrix multiplication and convolution benchmarks demonstrate significant performance gains—achieving up to 4× reductions in execution time compared to unoptimized baselines—while maintaining generality and extensibility within the MLIR framework. This work highlights the potential of combining heuristic search and compiler optimization techniques to build adaptive and scalable auto-schedulers, paving the way for future integration with reinforcement learning–driven optimization systems.

<!-- The code is publicly available at [this http URL](https://github.com/SEGHAIRII/iterative-beam-search-flowshop). -->

[Download paper here](https://www.researchgate.net/publication/396448821_Automatic_Code_Optimization_using_Reinforcement_Learning_in_the_MLIR_Compiler)

<!-- Recommended citation: Seghairi, A., Akeb, A., Aboud, I., Brouthen, K., Mokrane, I. E., & Baghdadi, M. D. (2025, June 8). An iterative beam search method for the flowshop permutation problem [Preprint]. -->