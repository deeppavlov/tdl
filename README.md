![TDL logo](/banner2.gif)

This is a GitHub page of Theoretical Deep Learning course held by Neural Networks and Deep Learning Lab., MIPT. The working language of this course is Russian.

**Location:** Moscow Institute of Physics and Technology, Phystech.Bio building, room 512

**Time:** Friday, 10:45, starting from 15th of February, 2019.

**Videos** will be available.

Lecture slides, homework assignments and videos will appear in this repo and will be available for everyone. However, we can guarantee that we will check your homework only if you are a MIPT student.

Further announcements will be in our Telegram chat: https://t.me/joinchat/D_ljjxJHIrD8IuFvfqVLPw

## Syllabus:

This syllabus is not final and may change. The order of topics will change with high probability.

1. **15 Feb** | Introduction.

2. Loss surfaces of neural networks.
    * Loss surface of linear networks. Loss surfaces of deep and shallow non-linear networks. Spin-glass model. Elimination of local minima.

3. Gradient descent dynamics.
    * GD almost surely does not converge to strict saddles. Convergence guarantees for noisy GD. GD dynamics on linear networks. GD dynamics on wide shallow non-linear networks. Generalization to deep nets.

4. Statistical learning theory.
    * Formalization of learning task. PAC-learning. Empirical risk. Generalization guarantees. Finite and infinite hypothesis classes. VC-dimension. PAC-Bayes framework.

5. Generalization guarantees.
    * Covering numbers, McDiarmid’s inequality. Application of PAC-Bayesian framework. Compression framework. Examples of computing generalization guarantees. Link between generalization and loss surface properties.

6. Information propagation.
    * Necessary conditions of learning. Neural networks from the view of random matrix theory.

7. The information bottleneck method.
    * Definition. Learning phases. Critics.
    
## Prerequisites:

* Basic calculus / probability / linear algebra (matrix differentiation, SVD, eigenvalues, eigenvectors, Hessian, Markov's inequality)
* For labs we use Python; need familiriaty with numpy, pytorch, matplotlib
* Some experience in DL (not the first time of learning MNIST, familiarity with such words as BatchNorm, ResNet, Dropout)
* Good, if you sometimes read fresh papers on DL research
* Labs are possible to do on CPU, but it can take quite long to train (~1-2 days).
    
## Grading:

This course will contain (at least) two labs and (at least) two theoretical assignments.

Preliminary grading criteria:

* Labs - 20%
* Theoretical assignments - 30%
* Oral exam - 50%

## Course staff:

- [Eugene Golikov](https://github.com/varenick)

This course is dedicated to the memory of Maksim Kretov.
