---
layout: page
title: Agent-Based Customer Support System
description: LLM-powered multi-agent customer support workflow built with OpenAI API and Swarm.
#img: /Users/fatemehrezvani/Documents/PORTFOLIO/fatemehrezvani.github.io/assets/img/projects/service_agents.png
importance: 1
category: featured
github: assets/img/service-agents.png
---

# Agent-Based Customer Support System

### LLM-powered multi-agent workflow for intelligent customer request routing and response generation.

---

## Project Snapshot

| | |
|---|---|
| **Role** | Machine Learning Engineer |
| **Domain** | Customer Support AI |
| **Project Type** | LLM Application |
| **Status** | Completed |
| **Technologies** | Python · OpenAI API · Swarm · Prompt Engineering |

---

# Executive Summary

Customer support teams receive a wide variety of customer requests every day. Efficiently understanding user intent and routing each request to the appropriate specialist is essential for improving response quality and reducing manual effort.

This project explores how Large Language Models (LLMs) and agent-based workflows can automate customer request triage. Using OpenAI models and the Swarm framework, I designed a multi-agent system capable of classifying user intent, routing requests to specialized agents, and generating context-aware responses.

---

# Business Problem

Traditional customer support workflows often rely on manual request classification or static rule-based routing. As request volume grows, these approaches become difficult to maintain, resulting in slower response times and inconsistent customer experiences.

The objective of this project was to investigate how an LLM-powered multi-agent architecture could streamline request routing while maintaining response quality.

---

# Technical Solution

The system was designed as a collaborative workflow where multiple AI agents perform specialized tasks instead of relying on a single monolithic prompt.

The workflow includes:

- Intent identification
- Request classification
- Agent selection
- Context-aware response generation

The application was implemented in Python using OpenAI API and the Swarm framework to coordinate communication between specialized agents.

---

# My Contributions

- Designed the overall multi-agent workflow.
- Implemented intent classification logic.
- Integrated OpenAI API for natural language understanding and response generation.
- Built specialized routing logic using Swarm.
- Developed prompt engineering strategies to improve response consistency.
- Evaluated workflow performance using realistic customer support scenarios.

---

# Results

- Improved customer support efficiency by approximately **2%** through adaptive routing.
- Reduced manual intervention required during request triage.
- Demonstrated how multi-agent collaboration can improve scalability compared with single-agent workflows.

---

# Technology Stack

- Python
- OpenAI API
- Swarm Framework
- Prompt Engineering
- Large Language Models (LLMs)

---

# Engineering Decisions

Instead of relying on a single prompt for every customer request, I designed a multi-agent architecture where each agent has a specialized responsibility.

This modular design improves maintainability, enables easier experimentation, and makes the workflow more scalable as new support scenarios are introduced.

---

# Lessons Learned

This project strengthened my understanding of agent orchestration, prompt engineering, and LLM application design.

If I continue developing this system, I would extend it by integrating persistent conversation memory, retrieval-augmented generation (RAG), FastAPI for deployment, and Docker for containerization to support production-ready AI services.