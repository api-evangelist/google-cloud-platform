---
title: "Experimenting with TPUs, GKE Managed DRANET, and Multi-cluster Inference Gateway"
url: "https://cloud.google.com/blog/topics/developers-practitioners/experimenting-with-tpus-gke-managed-dranet-and-multi-cluster-inference-gateway"
date: "2026-06-02"
author: "Ammett Williams"
feed_url: "https://cloud.google.com/blog"
---
This post demonstrates building a highly available AI inference setup using GKE Managed DRANET for TPU resource sharing, Multi-cluster GKE Inference Gateway for cross-region load balancing with automatic failover, and Cloud Storage FUSE for model storage. The setup deploys a Gemma 3 LLM across two GKE clusters in different regions using 4 TPU v6e chips each, with traffic routing to the closest region and automatic failover.
