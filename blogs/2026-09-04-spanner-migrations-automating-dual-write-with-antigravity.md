---
title: "Spanner migrations: Automating dual-write with Antigravity CLI for minimal disruption"
url: "https://cloud.google.com/blog/topics/developers-practitioners/using-antigravity-cli-to-streamline-dual-write-database-migration/"
date: "2026-09-04"
author: "Sachin Mathapati"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
When Google's Finance Engineering team needed to modernize their legacy data layer, they chose Spanner , a globally distributed, strongly consistent, multi-model database with high availability capabilities. But migrating to Spanner without taking production services offline was a daunting engineering challenge: As the internal team responsible for the application, we needed to manually rewrite dual-write logic across dozens of Data Access Objects (DAOs), a process that is slow and prone to human error. Further, doing so without disruption would have required implementing multi-phase dual-writ
