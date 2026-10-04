---
title: "A guide to speeding up your video processing with AlphaEvolve"
url: "https://cloud.google.com/blog/topics/developers-practitioners/how-to-speed-up-your-video-processing-with-alphaevolve/"
date: "2026-09-23"
author: "Anant Nawalgaria"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
In real-time streaming, every millisecond counts. For example, at 30 frames per second (fps), developers have a strict frame budget of just 33.3 ms (and only 16.6 ms at 60 fps) to ingest camera frames, run neural segmentation, apply shaders, and composite output. Exceeding that budget by even a fraction of a millisecond leads to dropped frames and stuttering.
