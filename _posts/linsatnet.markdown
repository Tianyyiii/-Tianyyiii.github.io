---
layout: post
title:  "LinSATNet: The Positive Linear Satisfiability Neural Networks"
date:  2023-03-21 22:21:59 +00:00
image: /images/fuzzy22.png
categories: research
author: "Tianyi Chen"
authors: "Runzhong Wang, Yunhao Zhang, Ziao Guo, <strong>Tianyi Chen</strong>, Xiaokang Yang, Junchi Yan"
venue: "ICML"
github: https://github.com/Thinklab-SJTU/LinSATNet
---
Proposed the first differentiable satisfiability layer based on an extension of the classic
Sinkhorn algorithm for jointly encoding multiple
sets of marginal distributions.  We showcase our
technique in solving constrained (specifically satisfiability) problems by one-shot neural networks,
including i) a neural routing solver learned without supervision of optimal solutions; ii) a partial
graph matching network handling graphs with unmatchable outliers on both sides; iii) a predictive
network for financial portfolios with continuous
constraints.