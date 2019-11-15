## PATH PLANNING PROBLEMS WITH SIDE-OBSERVATIONS - WHEN COLONELS PLAY HIDE-AND-SEEK

Numerical experiments as supplemental material for the work *Dong-Quan Vu, Patrick Loiseau, Alonso Silva  & Long Tran-Thanh. 2020. Path Planning Problems with Side-Observations—When Colonels Play Hide-and-Seek. In Proceedings of the 34th AAAI Conference on Artificial Intelligence (AAAI 2020)*. Article link: [ArXiv Preprint](https://arxiv.org/abs/1905.11151)

Corresponding contact: quan_dong.vu@nokia.com
### Introduction

We study the sequential learning problems in the Colonel Blotto and Hide-and-Seek games with limited feedback, that are modeled as Path Planning Problems with Side-Observations (SOPPP). We propose an algorithm, called EXP3-OE, that solves any SOPPP and provides two main improvements in comparison with the state-of-the-art:
- (i) it runs polynomially in terms of the games' parameters, 
- (ii) it provides improved upper-bound guarantees of the expected regret.

In this work, we conducted several experiments in support of these two main novel results. 

### User's Guide:
The repository consists the following files:
- Experiment_1.py     # The main file of experiment 1 (see Section 1.)
- Experiment_2.py     # The main file of experiment 2 (see Section 2.)
- Experiment_3.py     # The main file of experiment 3 (see Section 3.)
- Graph_construct.py  # Contruct the corresponding DAG for each instance of the game
- Weight_pushing.py   # Weight_pushing techniques that allows efficient implementation of EXP3-OE



**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
