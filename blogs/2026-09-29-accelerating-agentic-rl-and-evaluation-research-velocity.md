---
title: "Accelerating agentic RL and evaluation research velocity with 45x faster GKE Agent Sandbox"
url: "https://cloud.google.com/blog/products/containers-kubernetes/accelerate-agentic-rl-with-gke-agent-sandbox/"
date: "2026-09-29"
author: "Tinsley Shi"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
When scaling up agentic reinforcement learning (RL) and evaluation across massive parallel rollouts, frontier AI labs inevitably hit a bottleneck: Expensive GPU clusters sit idle, waiting minutes for CPU sandbox cold-starts, plus thousands of multi-gigabyte SWE-bench -style image pulls and scheduling backlogs. It’s a sandbox infrastructure problem that silently slows down your research and burns your training budget. To solve this fundamental infrastructure bottleneck, today we are introducing GKE Agent Sandbox optimized for RL along with the Agent Sandbox RL orchestration SDK , plus native in
