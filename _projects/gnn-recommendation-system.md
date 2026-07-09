---
layout: page
title: Graph-Based Recommendation System
description: Improving recommendation quality using Graph Neural Networks for information retrieval.
img: assets/img/projects/RS.png
importance: 3
category: machine-learning
---




## Project Overview

| | |
|---|---|
| **Role** | Machine Learning Engineer |
| **Domain** | Recommendation Systems |
| **Project Type** | Graph Machine Learning |
| **Status** | Completed |
| **Technologies** | Python · PyTorch · Graph Neural Networks · Pandas |

---

# Executive Summary

This project explored the application of Graph Neural Networks (GNNs) to improve recommendation quality by learning complex relationships between users, queries, and items.

The objective was to investigate how graph representation learning could outperform traditional recommendation approaches in sparse interaction environments while improving ranking performance.

---

# Business Problem

Traditional recommendation systems often struggle to capture higher-order relationships between users and items, especially when interaction data is limited.

This project investigated whether graph-based learning could better model these relationships and improve recommendation quality for information retrieval tasks.

---

# Technical Solution

A Graph Neural Network-based recommendation pipeline was developed to learn latent representations from graph-structured interaction data.

The model was trained and evaluated against baseline recommendation approaches using standard ranking metrics to measure recommendation quality.

---

# My Contributions

- Designed and implemented the graph-based recommendation workflow.
- Built the training and evaluation pipeline using PyTorch.
- Compared graph-based learning with baseline recommendation methods.
- Evaluated recommendation quality using Recall@10 and NDCG.
- Improved ranking performance through graph representation learning.

---

# Results

- Achieved approximately **1.37% improvement in Recall@10** over the baseline model.
- Improved recommendation quality in sparse interaction scenarios.
- Demonstrated the effectiveness of Graph Neural Networks for recommendation tasks.

---

# Technology Stack

- Python
- PyTorch
- Graph Neural Networks
- Pandas
- NumPy

---

# Engineering Decisions

Rather than relying solely on traditional collaborative filtering techniques, I explored Graph Neural Networks to better capture indirect relationships between users, queries, and items.

Graph-based representation learning provided a more expressive framework for modeling recommendation problems where relational information plays a significant role.

---

# Lessons Learned

This project deepened my understanding of graph representation learning, recommendation systems, and ranking evaluation.

If I continue developing this project, I would explore Graph Attention Networks (GAT), larger-scale datasets, and production-ready deployment for real-time recommendation services.