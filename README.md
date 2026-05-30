Auxiliary objectives are widely used in deep learning to improve representation
quality and generalization, yet their optimization behavior remains poorly under
stood. In particular, combining a primary task objective with auxiliary semantic
supervision often leads to unstable or architecture-dependent gradient interaction.
In this work, we show that such a behavior can be understood through a simple
geometric principle: the alignment between learned representations and auxiliary
targets. We begin with writer identification as a motivating case study, where weak
alignment between objectives leads to unstable gradient interaction, sensitivity to
loss weighting, and strong dependence on visual backbone architecture.
In contrast, compositional image classification exhibits a different regime. Here,
representations show strong alignment with auxiliary text targets, leading to consis
tently positive gradient cosine similarity, negligible conflict, and stable optimization
across two different visual architecture backbones. We formalize this phenomenon
through a simple alignment statistic measuring the separation between target and
non-target similarities. Empirically, we show that this statistic predicts optimization
dynamics across tasks and architectures. We further provide a first-order theoretical
analysis showing that the expected interaction between objectives is controlled by
the alignment.
