# Annotated bibliography for dialogue system

## Contributing
Please feel free to email Suyi Li (suyi.li@yale.edu).

## Useful Tutorial for Dialogue System

-	[Neural Approaches to Conversational AI - Question Answering, Task-Oriented Dialogue and Chatbots: A Unified View](https://arxiv.org/pdf/1809.08267.pdf) (ACL'18)
-	[Deep Learning for Conversational AI](https://www.poly-ai.com/docs/naacl18.pdf) (NAACL'18)
-	[Deep Learning for Dialogue Systems](http://aclweb.org/anthology/P17-5004) (ACL'17)
-	[Open-Domain Neural Dialogue Systems](http://aclweb.org/anthology/I17-5003) (AFNLP'17)


## Task-oriented Dialogue System
For task-oriented dialogue systems, they are built to handle relatively specific tasks and assist users to achieve specific goals. (e.g. find products, restaurants or flights reservation)


[**Task-oriented Dialogue System for Automatic Diagnosis**](http://aclweb.org/anthology/P18-2033) [[GitHub](https://github.com/LiuQL2/MedicalChatbot)]

Qianlong Liu, Zhongyu Wei, Baolin Peng, Xiangying Dai, Huaixiao Tou, Ting Chen, Xuanjing Huang, Kam-fai Wong (ACL'18)

Aims to build a dialogue system for automatic diagnosis. The authors firstly built a dataset collected from an online medical forum by extracting symptoms from both patients’ self-reports and conversational data between patients and doctors. Both the symptoms and the diseases are treated as slots as in the conventional dialogue systems. There is only one agent in the dialogue system, who is in charge of both symptom selection and disease prediction.

***

[**Dialogue Learning with Human Teaching and Feedback in End-to-End Trainable Task-Oriented Dialogue Systems**](https://arxiv.org/pdf/1804.06512.pdf) [[Dataset](https://github.com/google-research-datasets/simulated-dialogue)]

Bing Liu, Gokhan Tur, Dilek Hakkani-Tur, Pararth Shah, Larry Heck (NAACL'18)

Present a hybrid imitation and reinforcement learning method for training task-oriented dialogue systems through online user interactions. With this hybrid learning method, a dialogue agent can effectively learn from its interaction with users by learning from human teaching and feedback. Experimental results show that dialogue agents can learn effectively from the mistake it makes via imitation learning from user teaching. Applying reinforcement learning with user feedback after the imitation learning stage further improves the agent’s capability in successfully completing a task.

***

Other Related Papers
* [**A Network-based End-to-End Trainable Task-oriented Dialogue System**](https://arxiv.org/pdf/1604.04562.pdf) [[GitHub](https://github.com/shawnwun/NNDIAL)](EACL'17)
* [**Sequicity: Simplifying Task-oriented Dialogue Systems with Single Sequence-to-Sequence Architectures**](http://aclweb.org/anthology/P18-1133) [[GitHub](https://github.com/WING-NUS/sequicity)](ACL'18)
* [**Mem2Seq: Effectively Incorporating Knowledge Bases into End-to-End Task-Oriented Dialog Systems**](http://aclweb.org/anthology/P18-1136) [[GitHub](https://github.com/HLTCHKUST/Mem2Seq)](ACL'18)
* [**Learning End-to-End Goal-Oriented Dialog**](https://arxiv.org/pdf/1605.07683.pdf)(ICLR'18)
* [**End-to-End Learning of Task-Oriented Dialogs**](http://aclweb.org/anthology/N18-4010)(ACL'18)

## Non-task-oriented Dialogue System
Non-task-oriented dialogue system is also called chatbot. It is a computer program or an artificial intelligence which conducts a conversation with human smoothly via auditory or textual methods.

[**ScoutBot: A Dialogue System for Collaborative Navigation**](https://arxiv.org/pdf/1807.08074.pdf)

Stephanie M. Lukin, Felix Gervits, Cory J. Hayes, Anton Leuski, Pooja Moolchandani, John G. Rogers III, Carlos Sanchez Amaro, Matthew Marge, Clare R. Voss, David Traum (ACL'18)

ScoutBot is a dialogue interface to physical and simulated robots that supports collaborative exploration of environments. Users are allowed to issue unconstrained spoken language commands to ScoutBot. ScoutBot will prompt
for clarification if the user’s instruction needs additional input. It is trained on human-robot dialogue collected from
Wizard-of-Oz experiments, where robot responses were initiated by a human wizard in previous interactions.

***

[**Multi-Turn Response Selection for Chatbots with Deep Attention Matching Network**](http://aclweb.org/anthology/P18-1103)

Xiangyang Zhou, Lu Li, Daxiang Dong, Yi Liu, Ying Chen, Wayne Xin Zhao, Dianhai Yu and Hua Wu (ACL'18)

This paper focues on matching a response with its multi-turn context using dependency information based entirely on attention. The solution proposed in this paper is inspired by the recently proposed Transformer in machine
translation (Vaswani et al., 2017). Experiments on two large-scale multi-turn response selection tasks show that our proposed model significantly outperforms the state-of-the-art models.

***

Other Related Papers
* [**Learning Matching Models with Weak Supervision for Response Selection in Retrieval-based Chatbots**](http://aclweb.org/anthology/P18-2067) (ACL'18)
* [**Knowledge Diffusion for Neural Dialogue Generation**](http://aclweb.org/anthology/P18-1138) [[GitHub](https://github.com/WING-NUS/sequicity)] [[Database](https://github.com/liushuman/neural-knowledge-diffusion)]](ACL'18)
* [**Personalizing Dialogue Agents: I have a dog, do you have pets too?**](http://aclweb.org/anthology/P18-1205) [[Facebook Research](https://research.fb.com/publications/personalizing-dialogue-agents-i-have-a-dog-do-you-have-pets-too/)](ACL'18)
* [**Get The Point of My Utterance! Learning Towards Effective Responses with Multi-Head Attention Mechanism**](https://www.ijcai.org/proceedings/2018/0614.pdf) (IJCAI'18)


## Research on Dialogue State Tracking Challenge:
For dialogue state tracking challenge, it is a series of research community challenge tasks for accurately estimating a user’s goal and request in a dialog system.

[**Global-Locally Self-Attentive Dialogue State Tracker**](https://arxiv.org/pdf/1805.09655.pdf) [[GitHub](https://github.com/salesforce/glad)]

Victor Zhong, Caiming Xiong, Richard Socher (ACL'18)

Propose the Global-Locally Self-Attentive Dialogue State Tracker (GLAD), which learns representations of the user utterance and previous system actions with global-local modules. Global modules are used to share parameters between
estimators for different types of dialogue states, and local modules are used to learn slot-specific features. Experimental results show that the model improves tracking of rare states and achieves state-of-the-art performance
on the WoZ and DSTC2 state tracking tasks.

***

[**An End-to-end Approach for Handling Unknown Slot Values in Dialogue State Tracking**](http://aclweb.org/anthology/P18-1134)

Puyang Xu, Qi Hu (ACL'18)

Focuses on a practical yet rarely discussed problem in dialogue state tracking(DST), namely handling unknown slot values. This paper propse an E2E architecture based on the pointer network (PtrNet) that can effectively extract unknown slot
values while still obtains state-of-the-art accuracy on the standard DSTC2 benchmark. Extensive empirical evidence show that tracking unknown values can be challenging and theit approach can bring significant improvement with the help of an effective feature dropout technique.

***

## Tools for Dialogue System Research
* [**DeepPavlov: Open-Source Library for Dialogue Systems**](http://aclweb.org/anthology/P18-4021)[[GitHub](https://github.com/deepmipt/DeepPavlov)](ACL'18)
* [**ParlAI: A Dialog Research Software Platform**](https://arxiv.org/pdf/1705.06476.pdf)[[Project Page](http://www.parl.ai/)] [[GitHub](https://github.com/facebookresearch/ParlAI)]

***

## Other Topic Related to Dialogue System

### Dialogue2Query
* [**Learning to Map Context-Dependent Sentences to Executable Formal Queries**](https://arxiv.org/pdf/1804.06868.pdf)[[GitHub](https://github.com/clic-lab/atis)](NAACL'18)

### Incorporate Emotion into Dialogue System
* [**Emotional Chatting Machine: Emotional Conversation Generation with Internal and External Memory**](https://arxiv.org/pdf/1704.01074.pdf)[[GitHub](https://github.com/tuxchow/ecm)](AAAI'18)

### Dialogue Generation
* [**Automatic Dialogue Generation with Expressed Emotions**](http://aclweb.org/anthology/N18-2008)(NAACL'18)
* [**Adversarial Learning for Neural Dialogue Generation**](https://arxiv.org/pdf/1701.06547.pdf)[[GitHub](https://github.com/liuyuemaicha/Adversarial-Learning-for-Neural-Dialogue-Generation-in-Tensorflow)](EMNLP'17)


### Reinforcement Learning in Dialogue System
* [**Towards End-to-End Reinforcement Learning of Dialogue Agents for Information Access**](http://www.aclweb.org/anthology/P17-1045)][[GitHub](https://github.com/MiuLab/KB-InfoBot)](ACL'17)

* [**Feudal Reinforcement Learning for Dialogue Management in Large Domains**](https://arxiv.org/pdf/1803.03232.pdf)(NAACL'18)

* [**On-line Active Reward Learning for Policy Optimisation in Spoken Dialogue Systems**](https://arxiv.org/pdf/1605.07669.pdf)(ACL'16)

* [**Learning to Compose Words into Sentences with Reinforcement Learning**](https://arxiv.org/pdf/1611.09100.pdf)(ICLR'17)

* [**Composite Task-Completion Dialogue Policy Learning via Hierarchical Deep Reinforcement Learning**](https://arxiv.org/pdf/1704.03084.pdf)[[Microsoft Page](https://www.microsoft.com/en-us/research/publication/composite-task-completion-dialogue-system-via-hierarchical-deep-reinforcement-learning/)](EMNLP'17)




