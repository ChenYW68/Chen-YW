---
title: "Composite quantile regression for a distributed system with non-randomly distributed data"
collection: publications
category: manuscripts
permalink: /publication/2025-01-01-Quantile-number-7
excerpt: 'This paper proposed a novel estimation method for composite quantile regression.'
date: 2025-01-01
venue: 'Statistical Papers'
slidesurl: 'https://chenyw68.github.io/Chen-YW/files/Composite quantile regression for a distributed system with non-randomly distributed data.pdf'
paperurl: 'https://chenyw68.github.io/Chen-YW/files/Composite quantile regression for a distributed system with non-randomly distributed data.pdf'
bibtexurl: 'https://chenyw68.github.io/Chen-YW/files/Jin2025composite.bib'
citation: 'Jin J, Hao C, Chen, Y(2025). &quot;Composite quantile regression for a distributed system with non-randomly distributed data.&quot; <i>Statistical Papers</i>. 66(1): 1.'
---

The composite quantile regression estimator is widely acknowledged for its robustness and efficiency, offering a compelling alternative to both ordinary least squares and quantile regression estimators in linear models. However, when data are not randomly distributed across different workers in distributed settings, existing methods for composite quantile regression become statistically inefficient. To address this limitation, we present a novel one-step upgraded pilot composite quantile regression method. Our proposed approach involves two essential steps. In the first step, we obtain a pilot estimator by leveraging a small random sample collected from different workers. Subsequently, in the second step, we perform one-step updating based on the pilot estimator, involving the summarization of sample moment quantities on each worker. The resulting estimator is theoretically proven to be as statistically efficient as the composite quantile regression estimator using the entire sample, without relying on restrictive assumptions about randomness. Furthermore, the resulting estimator inherits the robustness and efficiency advantages of the composite quantile regression estimator, while also being computationally efficient in terms of communication cost and storage usage. To validate the practical performance of our proposed method, we conduct numerical studies using simulated and real data, demonstrating its effectiveness in real-world scenarios.