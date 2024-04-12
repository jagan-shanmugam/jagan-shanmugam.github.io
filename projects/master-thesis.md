# Latent Space Bayesian Optimization with Transfer Learning

<!-- <br>

<img src="https://github.com/tobwil/markdown_website/assets/72387477/fd99d0d2-703e-466c-b017-2a10d9cc7fdd" height="200">
<br> -->

## Abstract

Bayesian Optimization (BO) is a popular optimization method for expensive black-box functions, used in a variety of fields including hyperparameter optimization and industrial processes, up to moderate dimensions (10-20). The black box functions are sometimes over-parameterized which results in modeling redundant dimensions in high dimensional spaces. Optimization methods that focus on the most relevant
dimensions find optimal solutions faster. Additionally, existing optimization data, e.g. from optimizing similar problems, can be used to further speed up the optimization process on the task of interest i.e. perform Transfer Learning. To warm start BO on the task at hand, it is of utmost importance to model data collected from similar tasks to transfer knowledge. In Transfer Learning BO, models which learn the underlying intrinsic function are essential. We propose a latent space model with Transfer Learning to, 1. learn a transformation from input space to latent space and 2. learn a common set of features from the learned latent space across multiple tasks to perform efficient Transfer Learning. Our model is empirically evaluated against state-of-the-art methods on synthetic benchmarks.
<br>

**[<i class="fa-solid fa-up-right-from-square"></i> To read more - Click Here](https://github.com/jagan-shanmugam/Course-Work/blob/master/Master-Thesis/Master-Thesis-PPT.pdf)**
