![TDL logo](/banner2.gif)

This is a GitHub page of Theoretical Deep Learning course held by Neural Networks and Deep Learning Lab., MIPT. The working language of this course is Russian.

**Location:** Moscow Institute of Physics and Technology, Phystech.Bio building, room 512

**Time:** Friday, 10:45, starting from 15th of February, 2019.

**Videos** are available [here](https://www.youtube.com/playlist?list=PLt1IfGj6-_-dMa3Ff8mwjq1yOGijJ89Wa).

Lecture slides, homework assignments and videos will appear in this repo and will be available for everyone. However, we can guarantee that we will check your homework only if you are a MIPT student.

**For MIPT students:** in the case you want to take this course into your personal syllabus, the real name of the course is: "Теоретический анализ подходов глубокого обучения".

Further announcements will be in our Telegram chat: https://t.me/joinchat/D_ljjxJHIrD8IuFvfqVLPw

## Syllabus:

This syllabus is not final and may change. The order of topics will change with high probability.

1. [**15.02.2019**](/lecture_1) Introduction. Loss landscape of linear networks.

2. [**22.02.2019**](/lecture_2) Loss landscape of linear networks.

3. [**1.03.2019**](/lecture_3) Loss landscape of linear res-nets. Loss landscape of wide, but shallow sigmoid nets.

4. **8.03.2019** No class.

5. [**15.03.2019**](/lecture_4) Loss landscape of deep and wide sigmoid nets.

6. [**22.03.2019**](/lecture_5) Spin-glass model. Elimination of local minima.

7. **29.03.2019** GD almost surely converges to local minima. Noisy GD converges to local minima for any initialization.

8. **5.04.2019** GD dynamics on wide, but shallow non-linear networks. Generalization to deep nets.

9. **12.04.2019** Necessary conditions of learning.

9. **19.04.2019** (Ivan Skorokodov) The information bottleneck method.

10. **26.04.2019** Learning guarantees. Rademacher complexity. VC-dimension.

11. **3.05.2019** No class.

12. **10.05.2019** No class.

13. **17.05.2019** Modern approaches in obtaining generalization guarantees.

14. **24.05.2019** Modern approaches in obtaining generalization guarantees.

15. **31.05.2019** Reserve day.

## Prerequisites:

* Basic calculus / probability / linear algebra (matrix differentiation, SVD, eigenvalues, eigenvectors, Hessian, Markov's inequality)
* Labs are given as jupyter notebooks 
* We use python3; need familiriaty with numpy, pytorch, matplotlib
* Some experience in DL (not the first time of learning MNIST, familiarity with such words as BatchNorm, ResNet, Dropout)
* Labs are possible to do on CPU, but it can take quite a long time to train (~1-2 days).
    
## Grading:

This course will contain (at least) two labs and (at least) three theoretical assignments. 
There also will be an oral exam (in the form of interview) at the end of the course.

Let p_{labs} = "your points for labs" / "total possible points for labs". Define p_{theory} and p_{exam} analogously.

Your final grade will be computed as follows:
grade = min(10, p_{labs} * k_{labs} + p_{theory} * k_{theory} + p_{exam} * k_{exam}), where the coefficents are:
* k_{labs} = 3
* k_{theory} = 5
* k_{exam} = 4

This numbers are not final and can change slightly.

The deadlines for all assignments are computed as follows: "the day, when the assignments appear at this page, 23:59 Moscow time" + 3 weeks. **All deadlines are strict.**

All homework assignments will appear not more often than once a week.

Send your homeworks to tdl_course_mipt@protonmail.com

E-mails should be named as "Lab or theory" + "number" + "-" + "Your Name and Surname"

## Homeworks:

~~The first theoretical assignment is out! Deadline: 16.03.2019 23:59 Moscow time.~~

**The first lab assignment is out! Deadline: 28.03.2019 23:59 Moscow time.**

**The second theoretical assignment is out! Deadline: 16.04.2019 23:59 Moscow time.**

Theoretical assignments live [here](/hw_theory).
Labs live [here](/hw_lab).

## Course staff:

- [Eugene Golikov](https://github.com/varenick) - course admin, lectures, homeworks
- [Ivan Skorokhodov](https://github.com/universome) - homework review and beta-test, lecture about information bottleneck, off-screen comments

We also thank [Mikhail Arkhipov](https://github.com/mu-arkhipov) for gingerbread operating.

This course is dedicated to the memory of [Maksim Kretov](https://github.com/kretovmk) | 30.12.1986 - 13.02.2019, without whom this course would have never been created.
