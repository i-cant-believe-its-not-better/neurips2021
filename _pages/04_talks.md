---
layout: page
permalink: /talks/
title: Talks
description: ICBINB@NeurIPS 2021 - A Workshop for "beautiful" ideas that *should* have worked
---

### Invited Talks

#### [Robert C. Williamson](https://uni-tuebingen.de/en/research/core-research/cluster-of-excellence-machine-learning/research/research/cluster-research-groups/professorships/foundations-of-machine-learning-systems/) (8:00-8:30 EST)

**Title**: Better

**Abstract**: *I will discuss what is behind the notion of “better” as used in ML, and explore the problems of leaderboards and the notion that what our goal should be is to produce better algorithms. I will argue that we need a richer notion of our collective goal, one which might be well captured by the “rhetoric of machine learning”. I end with a meditation on the place and role of beauty in our research endeavours.*

#### [Mihaela Rosca](http://elarosca.net/) (10:00-10:30 EST)

**Title**: A story of distributional learning with games

**Abstract**: *Learning implicit generative models through a two-player game as done by Generative Adversarial Networks (GANs) has led to many empirical and theoretical breakthroughs. In this talk, we cover two arcs of the GAN story: the distributional view of GANs, and the games view of GANs, from their foundational principles to their research questions. We then build the case for a unified view of GANs, combining the distributional and games views, and assess its own principles and research questions. We conclude by arguing that while the path towards a unified view is challenging, it is worth pursuing as it could lead to the next important steps in the GAN story.*

#### [Nyalleng Moorosi](https://twitter.com/nunuska?lang=en) (10:45-11:15 EST)

**Title**: AI Continualism & the Becoming of the Past

**Abstract**: *This talk discusses the concept of AI continualism as it functions in the discipline of machine learning. We diagnose continualism to be a system that works under the authority of a given past and as of now is incapable of capturing revolutionary events. The objective of AI continualism, we claim,  is to uncritically reproduce the patterns of a given datafied past into the future. As a way to overcome this problem, we will offer a new understanding of the role of historical past and a concept of responsible interpretation that engages with ML artifacts. We claim that these two perspectives are enduring challenges that the ML community needs to address to ensure a just future of AI. The talk will be presented by Nyalleng Moorosi and his co-author Razvan Amironesei.*

#### [Tom Griffiths](https://cocosci.princeton.edu/tom/index.php) (11:30-12:00 EST)

**Title**: Metareasoning is important but intractable

**Abstract**: *One of the challenges that human minds face is a limit on the computational resources we can use — our brains. That means that one of the signatures of human intelligence is the ability to adaptively allocate our computational resources where they have the best effect, doing things like reusing partial solutions to past problems. Research in artificial intelligence has provided a framework for capturing this capacity, called rational metareasoning. However, even in the simplest cases metareasoning is extremely computationally expensive. We can make some progress by removing uncertainty about the consequences of executing computations, but it still remains a difficult problem. I guess I can believe it’s not better, but I wish it were better as I think it’s the key to understanding human intelligence and something that is going to become increasingly important for machines.*


#### [Tina Eliassi-Rad](http://eliassi.org/) (14:45-15:15 EST)

**Title**: The Why, How, and When of Representations for Complex Systems

**Abstract**: *The theme of this year's Nobel Prize in Physics was the study of complex systems. At the most basic level, complex systems consist of units and their interactions. In this talk, I will describe each step of a data analysis pipeline suitable for the study of complex systems: from the system dependencies that can manifest themselves in different flavors (temporal, subset, and spatial) to the common mathematical representations (such as graphs, simplicial complexes, and hypergraphs), their underlying assumptions, and the dependencies they encode. I will discuss the mathematical relationships between representations and explain how information can be lost (or imputed) when we convert data from one representation to another. I will use examples to highlight the importance of dependencies and careful choice of representations and algorithms when studying complex systems. The main message of the talk is that there is no perfect way to analyze a complex system, and that modeling decisions made when examining a data set from one system are not necessarily transferable to another system, or even to another data set from the same system. Yet, I see many studies apply certain pipelines for seemingly no other reason than because they are common in a particular field. Instead, I recommend evaluating and studying each new complex system and dataset individually and questioning each assumption and modeling decision. This talk is based on the following paper: [Leo Torres, Ann Sizemore Blevins, Danielle S. Bassett, Tina Eliassi-Rad: The Why, How, and When of Representations for Complex Systems. SIAM Review 63(3): 435-485 (2021).](https://doi.org/10.1137/20M1355896)*

#### [Chris Maddison](http://www.cs.toronto.edu/~cmaddis/) (15:30-16:00 EST)

**Title**: I Can't Believe Latent Variable Models Are Not Better

**Abstract**: *Latent variable models hold the promise of extracting meaningful features in an unsupervised way, but have so far largely failed to deliver. On the other hand, contrastive-type methods, e.g., SimCLR and CLIP, have delivered. CLIP's representations give rise to impressive zero-shot performance on ImageNet and are now being used widely to generate beautiful artificial art. Why has CLIP succeeded where the long literature on unsupervised latent variable models struggled? In this talk, I will attempt to give a simple answer to this question.*


#### [Daniel J. McDonald](https://dajmcdon.github.io/) (16:30-17:00 EST)

**Title**: Your model is beautiful, but does it predict?

**Abstract**: *Models that are capable of accurate statistical prediction may be horrible at causal, counterfactual prediction. However, it has long been understood that the reverse is not true. A model that gets the causal structure right, and can make accurate counterfactual predictions, should a fortiori be capable of accurate statistical prediction as well. In this talk, we exhibit some simple statistical techniques — using simulation to assess estimation methods; using randomization to gauge how well a model can appear to fit nonsense data; comparing predictive accuracy to simple baselines — that should be prerequisites to confidently proclaiming a model’s utility for structural understanding. These techniques are not recondite points of mathematical theory, and involve no controversial questions in the foundations of statistics. Rather, they are readily explained notions, accepted on pretty much all sides, whose force is easily grasped once they are presented. We illustrate this point mainly within the realm of macroeconomics, where the favourite models of the last 40 years fail all of these tests, raising the question “why are they ubiquitous?” We’ll conclude with some similar points about many of the epidemic models used to examine the current pandemic.*



### Contributed Talks

####  Wouter Kool (8:30-8:45 EST)

**Title**: [Unbiased Gradient Estimation with Balanced Assignments for Mixtures of Experts](https://openreview.net/forum?id=Hvfva7l1tcj)

**Abstract**: *Training large-scale mixture of experts models efficiently on modern hardware requires assigning datapoints in a batch to different experts, each with a limited capacity. Recently proposed assignment procedures lack a probabilistic interpretation and use biased estimators for training. As an alternative, we propose two unbiased estimators based on principled stochastic assignment procedures: one that skips datapoints which exceed expert capacity, and one that samples perfectly balanced assignments using an extension of the Gumbel-Matching distribution. Both estimators are unbiased, as they correct for the used sampling procedure. On a toy experiment, we find the `skip'-estimator is more effective than the balanced sampling one, and both are more robust in solving the task than biased alternatives.*

#### Francesco Negri (10:30-10:45 EST)

**Title**: [Continual Learning with Memory Cascades](https://openreview.net/forum?id=E1xIZf0E7qr)

**Abstract**: *Continual learning poses an important challenge to machine learning models. Kirkpatrick et al. introduced a model that combats forgetting during continual learning by using a Bayesian prior to transfer knowledge between task switches. This approach showed promising results but the algorithm was given access to the time points when tasks were switched. Using a model of stochastic learning dynamics we show that this model is very closely related to the previously developed cascade model to combat catastrophic forgetting. This general formulation allows us to use the model also for online learning where no knowledge about task switching times is given to the network. Also it allows us to use deeper hierarchies of Bayesian priors. We evaluate this model on the permuted MNIST task. We demonstrate improved task performance during task switching, but find that online learning is still significantly worse when task switching times are unknown to the network.*


#### Chelsea Murray (15:15-15:30 EST)

**Title**: [Addressing Bias in Active Learning with Depth Uncertainty Networks... or Not](https://openreview.net/forum?id=gVi-oIwRIks)

**Abstract**: *Farquhar et al. [2021] show that correcting for active learning bias with underparameterised models leads to improved downstream performance. For overparameterised models such as NNs, however, correction leads either to decreased or unchanged performance. They suggest that this is due to an “overfitting bias” which offsets the active learning bias. We show that depth uncertainty networks operate in a low overfitting regime, much like underparameterised models. They should therefore see an increase in performance with bias correction. Surprisingly, they do not. We propose that this negative result, as well as the results Farquhar et al. [2021], can be explained via the lens of the bias-variance decomposition of generalisation error.*


#### [Benjamin Bloem-Reddy](https://www.stat.ubc.ca/~benbr/) (16:00-16:15 EST)

**Title**: [Beauty in Machine Learning: Fluency and Leaps](https://openreview.net/forum?id=t_yk349a9Ec)

**Abstract**: *The extrapolative leaps from training to deployment are precisely where ML's best methods for system development succeed, and where most---and the most consequential---failures occur. I argue that the leap is where beauty can and does play a role. Beauty also serves to highlight some important aspects of the leap that are not specific to beauty. Based on this, and drawing on research on beauty from psychology, cognitive science, and philosophy of science, I articulate some fundamental problems and suggest directions for potential solutions.*


