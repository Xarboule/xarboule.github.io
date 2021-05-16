---
title: "Using differential execution analysis to identify thread interference"
collection: publications
permalink: /publication/2019-9-7-differential-exec
excerpt: 'In this paper, we propose a holistic metric able to pinpoint the blocks of code that suffer interference the most, regardless of the interference cause. Our metric uses performance variation as a universal indicator of interference problems.'
date: 2019-9-7
venue: 'IEEE Transactions on Parallel and Distributed Systems,  VOL. 30,  NO. 12,  December 2019'
paperurl: 'https://hal.archives-ouvertes.fr/hal-02179717/document'
citation: 'Mohamed Said Mosli Bouksiaa, François Trahay, Alexis Lescouet, Gauthier Voron, Remi Dulong, et al.. Using differential execution analysis to identify thread interference. IEEE Transactions on Parallel and Distributed Systems, Institute of Electrical and Electronics Engineers, 2019, 30 (12), pp.2866-2878. ⟨10.1109/TPDS.2019.2927481⟩. ⟨hal-02179717⟩'
---

*Abstract :* Understanding the performance of a multi-threaded application is difficult. The threads interfere when they access the same shared resource, which slows down their execution. Unfortunately, current profiling tools report the hardware components or the synchronization primitives that saturate, but they cannot tell if the saturation is the cause of a performance bottleneck. In this paper, we propose a holistic metric able to pinpoint the blocks of code that suffer interference the most, regardless of the interference cause. Our metric uses performance variation as a universal indicator of interference problems. With an evaluation of 27 applications we show that our metric can identify interference problems caused by 6 different kinds of interference in 9 applications. We are able to easily remove 7 of the bottlenecks, which leads to a performance improvement of up to 9 times.

[Download paper here](https://hal.archives-ouvertes.fr/hal-02179717/document)

_Recommended citation:_ Mohamed Said Mosli Bouksiaa, François Trahay, Alexis Lescouet, Gauthier Voron, Remi Dulong, et al.. Using differential execution analysis to identify thread interference. IEEE Transactions on Parallel and Distributed Systems, Institute of Electrical and Electronics Engineers, 2019, 30 (12), pp.2866-2878. ⟨10.1109/TPDS.2019.2927481⟩. ⟨hal-02179717⟩
