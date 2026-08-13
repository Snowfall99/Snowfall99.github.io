---
title: "Bridging the Gap of Timing Assumptions in Byzantine Consensus"
collection: publications
category: manuscripts
permalink: /publication/2023-themix
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-11-27
venue: 'Middleware'
link: 'https://dl.acm.org/doi/10.1145/3590140.3629114'
paperurl: 'https://dl.acm.org/doi/pdf/10.1145/3590140.3629114'
codeurl: 'https://github.com/Snowfall99/ThemiX'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: '<b>Zixuan Chen</b>, Lei Fan, Shengyun Liu, Marko Vukolić, Xiangzhe Wang, Jingjing Zhang (alphabetical order)'
---
Asynchronous Byzantine Fault-Tolerant (BFT) consensus protocols maintain strong consistency across nodes (i.e., ensure safety) and terminate probabilistically (i.e., ensure liveness) despite unbounded network delay. In contrast to protocols under partial synchrony, asynchronous counterparts pay no extra timing assumptions for electing a special role, and thus is more robust to network issues. To formally study this feature, we propose a new classification method for consensus and accordingly categorize relevant work: timing-balanced protocols are those that do not introduce strictly stronger timing-related assumptions for liveness, compared to ones required by safety.
We further propose ThemiX, a novel timing-balanced protocol under the hybrid model: either there is no corrupt node, or the number of correct and online nodes constitute a majority. ThemiX tolerates f Byzantine faults with a total of n = 2f + 1 nodes, achieving optimal resilience. If every node is honest or benign, ThemiX is an asynchronous protocol. Otherwise, ThemiX relies on timing assumptions for ensuring safety and probabilistic termination. No leader or any special role is elected. To boost performance, we further integrate two practical mechanisms that respectively allow ThemiX to proceed at the pace of actual network speed and bypass the expensive coin-tossing phase (i.e., randomization). Large-scale experiments on Amazon EC2 platform show that ThemiX achieves up to 86% reduction in latency compared to the consensus component of HoneyBadgerBFT and provides sustainable performance under simulated network faults.
