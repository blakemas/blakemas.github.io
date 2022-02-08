---
title: "Finding All epsilon-Good Arms in Stochastic Bandits"
collection: publications
permalink: /publication/2020-12-07-all-eps-good
excerpt: 'In this paper, we introduce the all-epsilon-good identification problem in multi-armed bandits.'
date: 2020-12-07
venue: 'Neural Information Processing Systems'
paperurl: 'https://proceedings.neurips.cc/paper/2020/file/edf0320adc8658b25ca26be5351b6c4a-Paper.pdf'
citation: '<b>Mason, B.</b>, Jain, L., Tripathy, A., & Nowak, R. (2020). Finding all $\epsilon $-good arms in stochastic bandits. <i>Advances in Neural Information Processing Systems</i>, 33, 20707-20718.'
---

The pure-exploration problem in stochastic multi-armed bandits aims to find one
or more arms with the largest (or near largest) means. Examples include finding
an epsilon-good arm, best-arm identification, top-k arm identification, and finding all
arms with means above a specified threshold. However, the problem of finding all
epsilon-good arms has been overlooked in past work, although arguably this may be the
most natural objective in many applications. For example, a virologist may conduct
preliminary laboratory experiments on a large candidate set of treatments and
move all epsilon-good treatments into more expensive clinical trials. Since the ultimate
clinical efficacy is uncertain, it is important to identify all ✏-good candidates.
Mathematically, the all-epsilon-good arm identification problem presents significant new
challenges and surprises that do not arise in the pure-exploration objectives studied
in the past. We introduce two algorithms to overcome these and demonstrate their
great empirical performance on a large-scale crowd-sourced dataset of 2.2M ratings
collected by the New Yorker Caption Contest as well as a dataset testing hundreds
of possible cancer drugs.

[Download paper here](https://proceedings.neurips.cc/paper/2020/file/edf0320adc8658b25ca26be5351b6c4a-Paper.pdf)

Recommended citation: <b>Mason, B.</b>, Jain, L., Tripathy, A., & Nowak, R. (2020). Finding all $\epsilon $-good arms in stochastic bandits. <i>Advances in Neural Information Processing Systems</i>, 33, 20707-20718.