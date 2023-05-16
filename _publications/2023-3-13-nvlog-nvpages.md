---
title: "NVMM cache design: Logging vs. Paging"
collection: publications
permalink: /publication/2023-3-13-nvcache
excerpt: 'How should we design an NVMM-based caching system to fully exploit its potential? We build two caching mechanisms, NVPages and NVLog, based on two radically different design approaches.'
date: 2023-3-13
venue: "NVMW'23: 14th Annual Non-Volatile Memories Workshop (San Diego)"
paperurl: 'https://arxiv.org/pdf/2305.02244'
citation: "Rémi Dulong, Quentin Acher, Baptiste Lepers, Valerio Schiavoni, Pascal Felber, Gaël Thomas: NVMM cache design: Logging vs. Paging, 14th Annual Non-Volatile Memories Workshop (NVMW'23)"
---

*Abstract :* Modern NVMM is closing the gap between DRAM and persistent storage, both in terms of performance and features. Having both byte addressability and persistence on the same device gives NVMM an unprecedented set of features, leading to the following question: How should we design an NVMM-based caching system to fully exploit its potential? We build two caching mechanisms, NVPages and NVLog, based on two radically different design approaches. NVPages stores memory pages in NVMM, similar to the Linux page cache (LPC). NVLog uses NVMM to store a log of pending write operations to be submitted to the LPC, while it ensures reads with a small DRAM cache. Our study shows and quantifies advantages and flaws for both designs. 

[Download paper here](https://arxiv.org/pdf/2305.02244)

_Recommended citation:_ Rémi Dulong, Quentin Acher, Baptiste Lepers, Valerio Schiavoni, Pascal Felber, Gaël Thomas: NVMM cache design: Logging vs. Paging, 14th Annual Non-Volatile Memories Workshop (NVMW'23)
