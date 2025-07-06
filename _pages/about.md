---
layout: about
title: about
permalink: /
subtitle: Statistics and Data Science PhD. Student, The Wharton School, University of Pennsylvania

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: 

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hi! I'm Kevin, a 2nd-year statistics (and data science) PhD. student at Penn (Wharton), co-advised by two amazing supervisors in [Yuting Wei](https://yutingwei.github.io) and [Giles Hooker](https://gileshooker.com). Previously, I was an undergraduate at Michigan (go blue!), where I graduated with four majors in statistics, honors mathematics, economics, and data science. 

My work spans bandits and reinforcement learning, diffusion models, high-dimensional statistics, and methods for stochastic dynamical systems. 


<details markdown="1">
  <summary markdown="span"> <b> What have I done? </b> </summary>
With collaborators including but not limited to {[Wei Fan](https://scholar.google.com/citations?user=t3HOsqwAAAAJ&hl=en), [Chinmaya Kausik](https://chinmaya-kausik.github.io), [Ziping Xu](https://zipingxu.github.io), [Zhihan Huang](https://scholar.google.com/citations?user=_nDeOvUAAAAJ&hl=en), [Haimo Fang](https://www.linkedin.com/in/haimo-fang-50a085272)} and senior(er) faculty {[Yuting Wei](https://yutingwei.github.io), [Giles Hooker](https://gileshooker.com), [Ambuj Tewari](https://www.ambujtewari.com) and [Edward Ionides](https://ionides.github.io)}:
* **Hybrid reinforcement learning**. If offline RL is analogous to learning by watching, and online RL is analogous to learning by doing, then hybrid RL studies what happens when machines can learn by both watching and doing. We've shown that machines [require fewer data samples]((https://rlj.cs.umass.edu/2024/papers/RLJ_RLC_2024_152.pdf)) under [certain conditions](https://proceedings.neurips.cc/paper_files/paper/2024/hash/d9251dc20346dffe9b6db86dcc6f8cc9-Abstract-Conference.html) when they are allowed to access both offline and online data, and can also achieve computational efficiency speedups in settings like actor-critic methods and diffusion policies. 
* **Actor-critic algorithms and diffusion policies.** We've recently solved an open problem on whether [actor-critic algorithms can be sample-efficient](https://openreview.net/forum?id=1laMy7jPux&noteId=ywb8HMfjXc) in general. This comes with some implications in practice, such as on the efficiency of exact gradients (like with DDPG and TD3) relative to on-policy sampling (like with PPO). In unreleased work submitted to NeurIPS, we show that diffusion policies can indeed achieve sublinear regret.
* **Heterogenous data within sequential decision-making.** [Chinmaya](https://chinmaya-kausik.github.io) and I have a long-running collaboration working on mixtures of sequential decision-making processes. We first tackled the problem of [learning mixtures of Markov chains and MDPs](https://proceedings.mlr.press/v202/kausik23a.html) from logged data in a short oral presentation at ICML 2023. Recently, we use [a similar method](https://openreview.net/forum?id=jMNQaNbjQl) to accelerate the process of personalizing (to a new user) by exploiting low-dimensional structure within high-dimensional embeddings (from other users), amidst heterogeneity in user tastes and preferences.
* **Statistical inference for gradient boosting.** We’ve been developing methods for constructing confidence and prediction intervals for gradient boosting regression, along with hypothesis tests for variable importance. Our approach supports dropout and parallelized bootstrapping by leveraging a key insight: with appropriate (Boulevard-style) regularization, gradient boosting converges to kernel ridge regression. This line of work includes an unreleased NeurIPS submission and two additional papers currently in preparation.
* **Inference for partially-observed Markov processes.** Say you can't fully observe the environment around you, but you have an internal belief on the state of it. Given only a model/simulator for the environment dynamic, and a likelihood for what you observe given your belief, we've [developed improved algorithms](https://arxiv.org/abs/2407.03085) for estimation and inference for the parameters behind the model. Our work has applications to disease modeling, such as a study on [cholera in Haiti](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012032), and has spawned a [Python package in development](https://pypi.org/project/pypomp/), for which I wrote [most of the guts](https://github.com/hetankevin/diffPomp). This is a long-running collaboration with [Edward Ionides](https://ionides.github.io) and his lab, since I was an undergraduate at Michigan.
* **Applications to causal inference.** Don't want to get scooped, can elaborate offline. 
</details>

<details markdown="1">
  <summary markdown="span"> <b> How have I contributed to capitalism? </b> </summary>

* **Amazon.** I'm currently working at Amazon as an Applied Scientist intern. I'm part of the MOSS (Materials, Handling, and Equipment Optimization, Systems, and Science) Science team within Amazon Fulfillment Technologies and Robotics. My focus is on continuous-time behavior cloning, dynamics model estimation, and policy learning under sparse observations. This is for the purpose of optimizing package flow and staffing within the next generation of Amazon fulfillment centers. 
* **Shade.** During my final winter at Michigan and the following summer, I worked with Brandon (co-founder and CEO) and his brother Jonathan to build the core ML/AI systems behind [Shade, an AI-driven platform for managing creative assets](https://shade.inc). Shade serves as an all-in-one hub for media storage, collaboration, and workflow automation. There, Brandon and I delivered features including a text-audio search engine powered by multimodal embeddings, a similar search engine for 3D textures, jersey number recognition, fast online face clustering for facial recognition, and lightweight asset description generation from a small set of tags. I also constructed a framework for fast and lightweight fine-tuning of embeddings for large multimodal models, and trained more than a few deep classifiers. The three of us also distilled BLIP, speeding up inference by over 7 times while maintaining a similar level of performance. 
</details>

<!-- <details markdown="1">
  <summary markdown="span"> <b> What am I working on now? </b> </summary>

</details>


<details markdown="1">
  <summary markdown="span"> <b> What am I excited about? </b> </summary>

</details> -->


In my spare time, I build earphones and guitars, cook (including but not limited to Singaporean food, which I really miss), and bake (including but not limited to pineapple tarts and sourdough). 

<!-- 
Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->
