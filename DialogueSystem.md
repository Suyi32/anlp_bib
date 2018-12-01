# Annotated bibliography for dialogue system
Suyi Li

## Contributing
Please feel free to email Suyi Li (suyi.li@yale.edu).

## Useful Tutorial for Dialogue System

-	[Neural Approaches to Conversational AI - Question Answering, Task-Oriented Dialogue and Chatbots: A Unified View](https://arxiv.org/pdf/1809.08267.pdf) (ACL'18)
-	[Deep Learning for Conversational AI](https://www.poly-ai.com/docs/naacl18.pdf) (NAACL'18)
-	[Deep Learning for Dialogue Systems](http://aclweb.org/anthology/P17-5004) (ACL'17)
-	[Open-Domain Neural Dialogue Systems](http://aclweb.org/anthology/I17-5003) (AFNLP'17)


## Task-oriented Dialogue System
For task-oriented applications, they are built to handle relatively specific tasks and assist users to achieve specific goals. (e.g. find products, restaurants or flights reservation)
__

[**Task-oriented Dialogue System for Automatic Diagnosis**](http://aclweb.org/anthology/P18-2033) [[project page](https://github.com/LiuQL2/MedicalChatbot)]

Qianlong Liu, Zhongyu Wei, Baolin Peng, Xiangying Dai, Huaixiao Tou, Ting Chen, Xuanjing Huang, Kam-fai Wong (ACL'18)

Aims to build a dialogue system for automatic diagnosis. The authors firstly built a dataset collected from an online medical forum by extracting symptoms from both patients’ self-reports and conversational data between patients and doctors. Both the symptoms and the diseases are treated as slots as in the conventional dialogue systems. There is only one agent in the dialogue system, who is in charge of both symptom selection and disease prediction.

***

[**Dialogue Learning with Human Teaching and Feedback in End-to-End Trainable Task-Oriented Dialogue Systems**](https://arxiv.org/pdf/1804.06512.pdf) [[Dataset](https://github.com/google-research-datasets/simulated-dialogue)]

Bing Liu, Gokhan Tur, Dilek Hakkani-Tur, Pararth Shah, Larry Heck (NAACL'18)

Present a hybrid imitation and reinforcement learning method for training task-oriented dialogue systems through online user interactions. With this hybrid learning method, a dialogue agent can effectively learn from its interaction with users by learning from human teaching and feedback. Experimental results show that dialogue agents can learn effectively from the mistake it makes via imitation learning from user teaching. Applying reinforcement learning with user feedback after the imitation learning stage further improves the agent’s capability in successfully completing a task.

***

Other Related Papers
[**A Network-based End-to-End Trainable Task-oriented Dialogue System**](https://arxiv.org/pdf/1604.04562.pdf) [[GitHub](https://github.com/shawnwun/NNDIAL)](EACL'17)
[**End-to-End Learning of Task-Oriented Dialogs**](http://aclweb.org/anthology/N18-4010)
[**Sequicity: Simplifying Task-oriented Dialogue Systems with Single Sequence-to-Sequence Architectures**](http://aclweb.org/anthology/P18-1133) [[GitHub](https://github.com/WING-NUS/sequicity)](ACL'18)
[**Mem2Seq: Effectively Incorporating Knowledge Bases into End-to-End Task-Oriented Dialog Systems**](http://aclweb.org/anthology/P18-1136) [[GitHub](https://github.com/HLTCHKUST/Mem2Seq)](ACL'18)
[**Learning End-to-End Goal-Oriented Dialog**](https://arxiv.org/pdf/1605.07683.pdf)(ICLR'18)
