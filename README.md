# A Tree-Structured Framework for the Collatz Conjecture

This repository contains a research manuscript proposing a new structural framework to analyze the Collatz (3n+1) problem.  
The approach is based on a rigorously defined *starting set*, *growth node set*, *branch node set*, and a *connection rule* that together form a directed, acyclic, rooted tree covering all positive odd integers.

## Overview

The paper introduces:

- A classification of all odd starting points via modular conditions (1 mod 6, 3 mod 6, 5 mod 6).  
- A deterministic growth process generating all even integers from each starting point.  
- A branching process defined by the reverse Collatz rule (n−1)/3 when valid.  
- A connection rule merging independently generated trees.  
- A global Collatz Tree Model where:
  - Every odd number appears exactly once.
  - The root node is 1.
  - Every node has a unique parent (except 1).
  - All reverse paths eventually reach 1.
  - No non-trivial cycles exist.

## Contents

- `paper.pdf` — The full manuscript.  
- `figures/` — Diagrams illustrating the tree model.  
- `examples/` — Computation examples and verification scripts (optional).  

## Purpose

This work aims to provide:
- A structural understanding of why the Collatz trajectories converge.
- A tree representation where the reverse Collatz iteration corresponds to tracing unique paths to the root.
- A unified generating function for all branch node sets.

## Citation

If you reference this work, please cite the DOI generated through Zenodo.
# 考拉兹猜想的树状结构框架

本仓库包含一篇研究论文，提出了一种新的结构框架来分析考拉兹(3n+1)问题。

该方法基于严格定义的*起始集*、*增长节点集*、*分支节点集*以及*连接规则*，它们共同构成了一棵覆盖所有正奇数的有向、无环、有根树。

## 概述

本文介绍了：

- 通过模条件（1 mod 6、3 mod 6、5 mod 6）对所有奇数起始点进行分类。

- 一个确定性的增长过程，从每个起始点生成所有偶数。

- 一个分支过程，当满足逆考拉兹规则(n-1)/3时定义。

- 一个连接规则，用于合并独立生成的树。

- 一个全局考拉兹树模型，其中：

- 每个奇数恰好出现一次。

- 根节点为 1。

- 每个节点都有唯一的父节点（节点 1 除外）。

- 所有反向路径最终都到达节点 1。

- 不存在非平凡环路。

## 目录

- `paper.pdf` — 完整论文。

- `figures/` — 树模型示意图。

- `examples/` — 计算示例和验证脚本（可选）。

## 目的

本工作旨在提供：

- 对考拉兹轨迹收敛原因的结构性理解。

- 一种树状表示，其中反向考拉兹迭代对应于追踪到达根节点的唯一路径。

- 所有分支节点集的统一生成函数。

## 引用

如果您引用本工作，请引用通过 Zenodo 生成的 DOI。

