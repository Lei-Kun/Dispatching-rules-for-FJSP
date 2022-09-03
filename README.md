# Dispatching-rules-for-DFJSP (Gantt-chart-for-FJSP)

This project is the implement of baseline methods of our published paper "A Multi-action Deep Reinforcement Learning Framework for Flexible Job-shop Scheduling Problem". Paper link: https://www.sciencedirect.com/science/article/pii/S0957417422010624

Everyone is welcome to use our code and cite our paper.

{Kun Lei, Peng Guo, Wenchao Zhao, Yi Wang, Linmao Qian, Xiangyin Meng, Liansheng Tang,
A multi-action deep reinforcement learning framework for flexible Job-shop scheduling problem,
Expert Systems with Applications,
Volume 205,
2022,
117796,
ISSN 0957-4174,
https://doi.org/10.1016/j.eswa.2022.117796.
(https://www.sciencedirect.com/science/article/pii/S0957417422010624)}

# Introduction
We chose the top-ranked (for FJSP with minimizing the makespan objective) four job sequencing rules and two machine assignment dispatching rules and combined them as eight compound dispatching rules as the baseline in our paper, i.e., four job sequencing dispatching rules including First in First Out (FIFO), Most Operation Number Remaining (MOPNR), Least Work Remaining (LWKR), and Most Work Remaining (MWKR), and two machine assignment dispatching rules including Shortest Processing Time (SPT) and Earliest End Time (EET). The eight compound dispatching rules are used as the benchmark for testing the performance of the proposed end-to-end DRL framework.

You can download form FJSP benchmark website to test other FJSP instances.   
