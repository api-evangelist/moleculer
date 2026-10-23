---
title: "Event-driven architecture in Node.js:"
url: "https://medium.com/moleculer/event-driven-architecture-in-node-js-6706172f3f3e?source=rss----65ff99209d8f---4"
date: "2026-10-13"
author: "Icebob"
feed_url: "https://medium.com/feed/moleculer"
---
Event-driven architecture in Node.js: pub/sub with NATS, Kafka and Redis — and when an event is not enough Request/response is how a microservice system starts, and events are how it stops being a distributed monolith. The moment orders has to call mailer, analytics and inventory after every checkout, orders knows about three services it should not care about, is as slow as the slowest of them, and fails when any of them is down. Flip it around — orders announces "order created", and whoever cares subscribes — and the coupling goes away.
