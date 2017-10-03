## Neural Task Programming:<br/> Learning to Generalize Across Hierarchical Tasks

Danfei Xu\*, Suraj Nair\*, Yuke Zhu, Julian Gao, Animesh Garg, Li Fei-Fei, Silvio Savarese

Abstract: In this work, we propose a novel robot learning framework called Neural Task Programming (NTP), which bridges the idea of few-shot learning from demonstration and neural program induction. NTP takes as input a task specification (e.g., video demonstration of a task) and recursively decomposes it into finer sub-task specifications. These specifications are fed to a hierarchical neural program, where bottom-level programs are callable subroutines that interact with the environment. We validate our method in three robot manipulation tasks. NTP achieves strong generalization across sequential tasks that exhibit hierarchal and compositional structures. The experimental results show that NTP learns to generalize well towards unseen tasks with increasing lengths, variable topologies, and changing objectives.

[![Alt text](https://img.youtube.com/vi/THq7I7C5rkk/0.jpg)](https://www.youtube.com/watch?v=THq7I7C5rkk&feature=youtu.be)

[Implementation details](implementation.pdf)

### Support or Contact

[Danfei Xu](http://cs.stanford.edu/~danfei/), [Yuke Zhu](https://web.stanford.edu/~yukez/), [Animesh Garg](http://animesh.garg.tech)

 <sup>* These authors contributed equally to the paper</sup>
