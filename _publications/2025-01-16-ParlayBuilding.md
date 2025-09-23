---
title: "Log-Optimal Portfolio Construction for Binary Options with Combinatorial Constraints"
collection: Publications
category: UnderReview
category2: RNR
permalink: /publications/2025-01-16-ParlayBuilding
excerpt: 'This paper develops an exact algorithm for a portfolio allocation problem in sports betting, incorporating a log-utility objective function and practical constraints.'
date: 2025-08-14
venue: 'Management Science'
slidesurl: ''
paperurl: '/files/Decary2025_JMP.pdf'
citation: 'Jeff Decary, David Bergman, Bin Zou (2025). "Log-Optimal Portfolio Construction for Binary Options with Combinatorial Constraints".'
---

We study the problem of optimal wealth allocation across independent binary options with known payouts, aiming to maximize log utility under practical constraints. This general framework arises in settings such as prediction markets (e.g., Kalshi and Polymarket), financial event contracts (e.g., Nadex), and sports betting (e.g., Draftkings and FanDuel). The Kelly Criterion provides a classical solution for the bet sizing of a single binary option, and numerous papers have explored extensions to multiple binary options. Our work expands on this body of research by investigating how to incorporate combinatorial constraints into the model, including limits on the number of binary options to select in a portfolio, a requirement that arises in many settings. These constraints considerably increase the computational complexity of the problem, thereby necessitating advanced solution methodologies. To address this challenge, we develop a logic-based Benders decomposition algorithm that provides a scalable and computationally efficient solution framework. Although broadly applicable, we focus on sports betting due to its market scale and unique inclusion of parlay options. We also study how sportsbooks can make slight modifications to parlay pricing so that optimal allocations do not include parlay options, even though such options may remain attractive to bettors.



