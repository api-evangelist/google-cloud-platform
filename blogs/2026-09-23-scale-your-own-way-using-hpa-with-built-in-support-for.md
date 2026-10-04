---
title: "Scale your own way, using HPA with built-in support for PromQL metrics queries in GKE"
url: "https://cloud.google.com/blog/products/containers-kubernetes/native-support-for-prometheus-metrics-in-gke/"
date: "2026-09-23"
author: "Jean-Marc François"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
Earlier this year, we announced native support for Google Kubernetes Engine (GKE) custom metrics. This milestone allowed you to scrap external adapters and instead collect autoscaling metrics directly from your pods. By routing these metrics straight to the Horizontal Pod Autoscaler (HPA), we cut metrics reading latency down to 5 seconds.
