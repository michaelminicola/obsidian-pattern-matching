Pattern Matching can take many forms in terms of Computing for Cognitive Augmentation. On of them is in the creation of AI, as show here: [[AI and The Human Brain]] and [[PM in Technologies]]. However, there are also other examples as follows.

## Self-Driving Cars

In the "Reinforcement Learning to Drive a Car by Pattern Matching" article, the authors discuss how self-driving cars rely on Pattern Matching to be able to do so. They created a system that consists of three subsystems: Intelligent Image Processing (IIP), Pattern Matching (PM), and Reinforcement Learning (RL) [1]. 

The IPP is responsible for processing incoming video stream of the environment surrounding the car and "the real-time calculation of reduced parametric descriptions of the scene called Abstract Complete Situation Descriptions (ACSD’s)" [1]. 

The PM then tries to retrieve similar situations to the one the car is currently facing, from a pattern database. It does so through 2 steps [2]: 
1. scanning the pattern database for similar situations.
2. storing the ACSD of the situation together with the steering commands, for future reference.

Lastly, RL is used to determine the correct steering behavior for the current situation, which is based on both the actual scene and the previously recorded ones [2]. 

The following figure summarizes the above system [2]:

![[Pasted image 20251030195122.png]]

## Bioinformatics

In Bioinformatics, PM is a very important tool that is used with DNA. It is used to parse DNA sequences, find matches, and other things. There are tens of PM algorithms that each have their own purposes, attributes, and complexities, to strive for the best outcomes. In the “A survey on improving pattern matching algorithms for biological sequences” article, the authors list 23 of such algorithms. Here are 3 of them to name a few: Karp-Rabin algorithm, BRFS, and KMP [2]. 

## Auto Spelling Correction

Auto Correction system rely on Pattern Matching to fix spelling. They first use a transformation model to capture the user's spelling behavior. The software then "[estimates] the transformation model using clicks on search engine recourse links, which represent user confirmed query misspellings". Then, an algorithm is used to determine the highest-probability correction for the specific misspelled word [3].
## References

[1] M. Krödel and K. D. Kuhnert, “Reinforcement learning to drive a car by pattern matching,” in _Pattern Recognition (DAGM 2002)_, L. Van Gool, Ed. Berlin, Heidelberg: Springer, 2002, vol. 2449, pp. 338–345. doi: 10.1007/3-540-45783-6_39.

[2] B. Hamed, O. Ibrahim, and T. Abd El-Hafeez, “A survey on improving pattern matching algorithms for biological sequences,” _Concurrency and Computation: Practice and Experience_, vol. 34, Sep. 2022, Art. no. e7292. doi: 10.1002/cpe.7292.

[3] H. Duan and P. Hsu, “Online spelling correction for query completion,” in _Proceedings of the 20th International Conference on World Wide Web (WWW)_, Hyderabad, India, 2011, pp. 117–126. [Online]. Available: [https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/WWW11-OnlineSpellingCorrection.pdf](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/WWW11-OnlineSpellingCorrection.pdf?utm_source=chatgpt.com)



