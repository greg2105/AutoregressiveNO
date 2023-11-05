Exploring Stable Autoregressive Neural Operators

This repository contains an implementation and experiments for training autoregressive neural operator models, with a focus on improving stability for long-term simulations.

The code is adapted from techniques presented in "Towards Stability of Autoregressive Neural Operators" by McCabe et al. (2023). The original paper can be found at https://arxiv.org/abs/2306.10619 and the reference code is available at https://anonymous.4open.science/r/stabilizing_neural_operators-5774/.

Neural operators have shown promise for modeling spatiotemporal physical systems. However, when trained autoregressively to simulate over long time horizons, error accumulation can lead to instability. This work explores methods to mitigate exploding errors.

Key improvements include:

    Architectural changes to control instability-inducing operations
    Application-specific optimizations tailored to physical systems
    Experiments on fluid flow, weather forecasting, and other simulations

The techniques presented in the paper enabled 800% longer stable forecasts on benchmark systems compared to baseline neural operator models.

This repository provides implementations of the proposed methods. The goals are to:

    Reproduce results on established test problems
    Explore autoregressive neural operator architectures
    Push towards even longer stable simulations
    Investigate alternatives to improve stability

The initial focus is on applying techniques to problems involving systems of partial differential equations and spatiotemporal data. Example systems include Navier-Stokes fluids, shallow water models, and global weather datasets.

Feedback and contributions welcome! Please open an issue or pull request if you have ideas for enhancing stability or new applications to explore.

