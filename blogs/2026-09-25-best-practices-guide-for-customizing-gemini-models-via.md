---
title: "Best practices guide for customizing Gemini models via Reinforcement Learning (RL)"
url: "https://cloud.google.com/blog/topics/developers-practitioners/best-practices-guide-for-customizing-gemini-models/"
date: "2026-09-25"
author: "Jiaqi Pan"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
Reinforcement learning (RL) has been a keystone of modern LLM post-training, but it demands large training clusters and access to model internals that external customers can't have with proprietary models like Gemini. So here at Google Cloud, we packaged it into a managed RL fine-tuning service (RLFT service) — you bring prompts and a reward function; we handle the infrastructure and the proprietary model internals. Now, you can adapt Gemini with the service — teaching the model from a reward signal you define, rather than from a fixed set of labeled answers.
