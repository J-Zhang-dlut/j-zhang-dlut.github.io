---
title: "Multi-View Representation Learning via Dual Optimal Transportation"
collection: publications
category: manuscripts
permalink: /publication/journal4
excerpt: ''
date: 2021-04-03
venue: 'IEEE Access'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9585688/'
citation: 'Li P, Gao J, Zhai B, et al. Multi-view representation learning via dual optimal transportation[J]. IEEE Access, 2021, 9: 144976-144984.'
---

Recently, multi-view representation learning has gained rapid growth in various fields. Most of previous multi-view learning methods rely on strong notions of distances that often provide no useful gradients in deep network training, which greatly degrades the performance in merging complementary information of views. To address this challenge, a multi-view representation learning network with dual optimal transportation (MDOT-Net) is proposed to capture fusion representations embedded in a common manifold with the weak topology. In MDOT-Net, the multi-view representation learning is modelled as an optimal transportation (OT) problem in manifold fitting, which is further decomposed into the intra-view OT and the inter-view OT. The intra-view OT is implemented by a view-specific adversarial variational network, which accurately captures local manifold structures within views by leveraging fusion knowledge. The inter-view OT is implemented by a view-fusion adversarial inference network, which models fusion representations compatible with diversities of sub-manifolds by utilizing view-specific knowledge. The two OTs boost mutually by providing prior knowledge to each other in multi-view representation learning. Finally, numerous experiments are conducted on four benchmark datasets, and the results demonstrate MDOT-Net is competitive against state-of-the-art algorithms.
