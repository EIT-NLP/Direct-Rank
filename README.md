# Rethinking Reasoning in Document Ranking: Why Chain-of-Thought Falls Short

[![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.08985)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Code-Coming%20Soon-orange.svg)](#code-coming-soon)

### Overview

Large Language Models (LLMs) are increasingly employed in Information Retrieval (IR) pipelines, especially for reranking, where rerankers refine initial retrieval results. Inspired by the success of large reasoning models (LRMs), recent work has begun adding explicit chain-of-thought (CoT) reasoning into rerankers, hoping that step-by-step reasoning might yield better judgments. Yet, whether reasoning truly helps ranking remains unclear.

In this study, we conduct a systematic analysis of reasoning in reranking across pointwise and listwise paradigms, under both supervised and reinforcement learning. Surprisingly, we find that reasoning-augmented rerankers consistently underperform their direct, non-reasoning counterparts—despite much higher inference cost. 

