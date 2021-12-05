# Awesome-Next-Steps-in-Machine-learning
A Collection of Resources for Next-Steps in Machine learning.


## Deep learning from Neuroscience
Resources understanding how Mind works from neuroscience perspective and Deep learning community could get inspiration from it. 

### 1. [Jeff Hawkins: Thousand Brains Theory of Intelligence | Lex Fridman Podcast #25](https://youtu.be/-EVqrDlAqYo)
Insightful discussion of Jeff Hawkings on latest advancement in neuroscience and why machine learning people should pay attention.
- Mammals (humans specifically) have highly developed neocortex, the part of brain associated with higher-level cognition. Neocortex is highly sparse, unlike current dense networks.
- Neural nets in brains use Hebbian learning and not Backpropagation. 
- Each of our thought is due to a **specific pattern of firing of neurons with a happening with a certain timing**. Timing is extremely important.
- While Elon and Sam are focusing on the AI takeover,Jeff actually predicted something like covid (1:57:13)


## System II Deep learning
Discusses what deep learning requires to do move towards higher-level cognition. 

### 1. [Yoshua Bengio | From System 1 Deep Learning to System 2 Deep Learning | NeurIPS 2019](https://bdtechtalks.com/2019/12/23/yoshua-bengio-neurips-2019-deep-learning/)

Summary :

Deep learning systems (layered neural network architectures) are really good at prediction given an input. For instance, they may predict risk associated with a patient between 0-1 given huge vector representing patients information. But, they are just doing computation over input and these architecture don't support ways to tell why the machine made the decision. Humans don't focus in pixel level. Looking at image of cat, they perviece pointed ears, deep eyes, white fur and small size (in comparison to table on the side), and recognize it as cat. When asked why, we can describe the reasons it's a house cat and not a wild siberian tiger who we can imagine as just a scaled version of house cat.

On the other hand, there are symbolic AI systems that can do causal reason of what causes what effect. They need an structured-relational data to act. To do so, again human labelling is necessary, making traditional AI systems not **Scalable and Limited**, also pointed out by Rich Sutton Points in [`The Bitter Truth`](http://www.incompleteideas.net/IncIdeas/BitterLesson.html).
The Traditional AI can do causal reasoning over a data where higher level abstraction is provided in data. What we want instead is a deep learning system that can build model of the world at a higher level abstraction by learning from raw-information. 

Bengio's proposal to move deep learning towards Human-Level intelligence. 
- Out-of-Order Distribution
- Attention
- Consiousness Prior

### 2. [TrustML Seminar: Sara Magliacane on "Causality-inspired ML: what can causality do for ML?"](https://youtu.be/X8foHlW-Dsw)

#### Summary : 

What can causality do for "TrustWorthy" Machine leanring ? 
- Fairness, Selection Bias, Generalization
- Heterogeneous data, small data, non i.i.d data
- Not just correlate input to output and do prediction, But Actionable insights. Decisions cannot be made with just prediction.





