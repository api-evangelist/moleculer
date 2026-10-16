---
title: "Circuit breaker, retry and timeout in Node.js microservices — and why you need all three"
url: "https://medium.com/moleculer/circuit-breaker-retry-and-timeout-in-node-js-microservices-and-why-you-need-all-three-2b0f9c5064b3?source=rss----65ff99209d8f---4"
date: "2026-10-07"
author: "Icebob"
feed_url: "https://medium.com/feed/moleculer"
---
A microservice architecture has one failure mode that a monolith never had: a dependency that is almost working. Not down — down is easy, the connection is refused and you know in a millisecond. Almost working means it answers one call in three, or it answers everything but takes four seconds to do it.
