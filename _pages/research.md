---
layout: archive
title: "Publications"
permalink: /Research/
author_profile: true
redirect_from: 
- /research/
- /research.html
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!-- %%{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %} -->

<span style="color:CornflowerBlue">[Confidence-Based Model Selection: When to Take Shortcuts for Subpopulation Shifts](https://arxiv.org/pdf/2306.11120.pdf)</span>  
   <sup>**Annie S. Chen**, Yoonho Lee, Amrith Setlur, Sergey Levine, Chelsea Finn <br>
   ***ArXiv Preprint, 2023*** <br>
  We propose COnfidence-baSed MOdel Selection (COSMOS), where we adaptively choose among models with different strengths to achieve high performance on both majority and minority subpopulations. COSMOS does not require any target labels or group annotations and can even be used for hyperparameter tuning. 

<span style="color:CornflowerBlue">[Language-Driven Representation Learning for Robotics](https://arxiv.org/pdf/2302.12766.pdf)</span>  
   <sup>Siddharth Karamcheti, Suraj Nair, **Annie S. Chen**, Thomas Kollar, Chelsea Finn, Dorsa Sadigh, Percy Liang <br>
   ***Robotics: Science and Systems (RSS), 2023*** <br>
  We propose Voltron, which uses language to learn better visual represnetations for a diverse range of robotics problems by trading off conditioning and generation.  

<span style="color:CornflowerBlue">[Project and Probe: Sample-Efficient Domain Adaptation by Interpolating Orthogonal Features](https://arxiv.org/pdf/2302.05441.pdf)</span>  
   <sup>**Annie S. Chen**\*, Yoonho Lee\*, Amrith Setlur, Sergey Levine, Chelsea Finn <br>
   ***ICLR TrustML-(un)Limited Workshop, 2023 (Oral)*** <br>
  We propose Project and Probe (Pro^2), a lightweight + data-efficient approach for domain adaptation. Pro^2 first learns a linear projection that maps a pre-trained embedding onto orthogonal directions while being predictive of labels in the source dataset. The goal of this step is to learn a variety of predictive features, so that at least some of them remain useful after distribution shift. Pro^2 then learns a linear classifier on top of these projected features using a small target dataset. 

<span style="color:CornflowerBlue">[Surgical Fine-Tuning Improves Adaptation to Distribution Shifts](https://arxiv.org/pdf/2210.11466.pdf)</span>  
   <sup>Yoonho Lee\*, **Annie S. Chen**\*, Fahim Tajwar, Ananya Kumar, Huaxiu Yao, Percy Liang, Chelsea Finn <br>
   ***International Conference on Learning Representations (ICLR), 2023*** <br>
  We show that selectively fine-tuning a subset of layers (which we term surgical fine-tuning) matches or outperforms fine-tuning all layers. Moreover, the type of distribution shift influences which subset is more effective to tune: for example, for image corruptions, fine-tuning only the first few layers works best.

<span style="color:CornflowerBlue">[You Only Live Once: Single-Life Reinforcement Learning](https://arxiv.org/pdf/2210.08863.pdf)</span>  
   <sup>**Annie S. Chen**, Archit Sharma, Sergey Levine, Chelsea Finn <br>
   ***Neural Information Processing Systems (NeurIPS), 2022*** <br>
   Agents operating in the real world must often contend with novel situations that differ from their prior experience. In these situations, the agent only has one trial to complete the given task and must adapt on-the-fly to novelty without human interventions. To model such settings more formally, we study single-life reinforcement learning (SLRL) where given prior data, an agent must complete a task in a single trial in a domain with a novel distribution shift without any human interventions or supervision. </sup> 

<span style="color:CornflowerBlue">[Learning Generalizable Robotic Reward Functions from "In-The-Wild" Human Videos](https://sites.google.com/view/dvd-human-videos)</span>  
   <sup>**Annie S. Chen**, Suraj Nair, Chelsea Finn <br>
   ***Robotics Science and Systems (RSS), 2021*** <br>
   ***ICLR Workshop on Self-Supervised Reinforcement Learning, 2021, (Oral)*** <br>
   We propose a simple approach, Domain-agnostic Video Discriminator (DVD), that learns multitask reward functions by training a discriminator to classify whether two videos are performing the same task. These reward functions can generalize to unseen environments and tasks by learning from a small amount of robot data and a large, diverse dataset of in-the-wild human videos.</sup> 
   
<span style="color:CornflowerBlue">[Just Train Twice: Improving Group Robustness without Training Group Information](https://arxiv.org/pdf/2107.09044.pdf) 
</span>  
<sup>Evan Z. Liu\*, Behzad Haghgoo\*, **Annie S. Chen**\*, Aditi Raghunathan, Pang Wei Koh, Shiori Sagawa, Percy Liang, Chelsea Finn<br>
  ***International Conference on Machine Learning (ICML), 2021 (Long Talk)*** <br>
  A simple method that improves worst-group classification performance on datasets with spurious correlations without requiring training group annotations. JTT first detects informative training examples, which are often minority examples, by training an initial ERM classifier and extracting the misclassified examples. It then trains a final classifier by upsampling the selected examples. 

<span style="color:CornflowerBlue">[Batch Exploration with Examples for Scalable Robotic Reinforcement Learning](https://sites.google.com/view/batch-exploration)</span>  
   <sup>**Annie S. Chen**\*, Hyunji Nam\*, Suraj Nair\*, Chelsea Finn <br>
   ***Robotics and Automation Letters (RA-L) & International Conference on Robotics and Automation (ICRA), 2021*** <br>
   We propose a framework for leveraging weak human supervision to enable better robotic exploration for scalable data collection. Under this framework, the robot autonomously collects high quality data with a few minutes of human supervision, providing better data for downstream offline RL.</sup> 

<span style="color:CornflowerBlue">[On the Opportunities and Risks of Foundation Models](https://arxiv.org/abs/2108.07258)</span>  
   <sup>Rishi Bommasani, ..., **Annie Chen**, ... Percy Liang <br>
   Report by the [Center for Research on Foundation Models (CRFM)](https://crfm.stanford.edu/), 2021 <br></sup> 
   
<span style="color:CornflowerBlue">[Limit Theorems for Descents in Permutations and Arithmetic Progressions in Z/pZ](https://arxiv.org/abs/1810.02425)</span>  
   <sup>Bryce Cai, **Annie S. Chen**, Ben Heller, Eyob Tsegaye <br>
   ***Outstanding Poster Presentation, Joint Mathematics Meetings (JMM) Undergraduate Poster Session, 2019***<sup>
   
<span style="color:CornflowerBlue">[Index divisibility in dynamical sequences and cyclic orbits modulo p](http://nyjm.albany.edu/j/2017/23-45v.pdf)</span>  
   <sup>**Annie S. Chen**, T. Alden Gassert, Katherine E. Stange <br>
   ***New York Journal of Mathematics (NYJM), 2017***<sup>
  


