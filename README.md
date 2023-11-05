Code adapted from the paper "McCabe, M., Harrington, P., Subramanian, S., & Brown, J. (2023). Towards stability of autoregressive neural operators."

The paper can be found here: https://arxiv.org/abs/2306.10619

The corresponding code can be found here: https://anonymous.4open.science/r/stabilizing_neural_operators-5774/README.md

The goal of this repository is to explore the methods of solving partial differential equations using neural operators. In particular, neural operators typically use an input/output pair with a small time scale. While this method can be good for predicting a small set of states, we can use autoregression instead to produce a much longer simulation. Autoregression has been used in the most recently trending products, like ChatGPT which uses a transformer model. Some issues autoregression introduces in the neural operator space is a growing margin of error. As states diverge from the
ground truth, this error grows. 

The paper Towards Stability of Autoregressive Neural Operators references the use of Navier-Stokes fluid flow, rotating shallow water, and a high-resolution global weather forecasting system to demonstrate their findings. The design principles introduced led to 800% longer forecast without qualitative signs of divergence compared to original models.

Infinitely stable simulations using autoregressive neural operators has yet to be seen, this repository serves as an experiment to approach that goal.




