---
title: "Elevated query error rates"
url: "https://status.axiom.co//incidents/01M5F849HVK9P6A1SYN2WWH0RP"
date: "2026-10-21"
feed_url: "https://status.axiom.co/feed.rss"
---
Status: Resolved A portion of queries experienced increased latency and elevated error rates which was caused by an interaction between our service mesh and internal cache services. Following a deployment, some query workers continued attempting to connect to outdated cache instance addresses, even after the replacement instances had become healthy. This resulted in query timeouts and failures.
