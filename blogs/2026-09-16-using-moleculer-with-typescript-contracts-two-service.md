---
title: "Using Moleculer with TypeScript: contracts, two service styles, and the honest caveats"
url: "https://medium.com/moleculer/using-moleculer-with-typescript-contracts-two-service-styles-and-the-honest-caveats-96c46fb0c0b7?source=rss----65ff99209d8f---4"
date: "2026-09-16"
author: "Icebob"
feed_url: "https://medium.com/feed/moleculer"
---
“Does Moleculer work with TypeScript?” is the second most common question I get about it, right after the NestJS one. The short answer is yes — it ships its own type definitions, you can write services as typed schemas or as classes, and the runner loads .ts files. The longer answer has a few honest caveats, and since you'd hit them on day two anyway, I'd rather put them in the article.
