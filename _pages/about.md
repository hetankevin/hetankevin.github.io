---
layout: about
title: about
permalink: /
subtitle: Statistics and Data Science PhD. Student, The Wharton School, University of Pennsylvania

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>555 your office number</p>
    <p>123 your address street</p>
    <p>Your City, State 12345</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hi! I'm Kevin, a 2nd-year statistics (and data science) PhD. student at Penn (Wharton), co-advised by two amazing supervisors in [Yuting Wei](https://yutingwei.github.io) and [Giles Hooker](https://gileshooker.com). Previously, I was an undergraduate at Michigan (go blue!), where I graduated with four majors in statistics, honors mathematics, economics, and data science. 

My work spans bandits and reinforcement learning, diffusion models, high-dimensional statistics, and methods for stochastic dynamical systems. 


<details markdown="1">
  <summary markdown="span"> <b> What have I done? </b> </summary>
With collaborators including but not limited to {[Wei Fan](https://scholar.google.com/citations?user=t3HOsqwAAAAJ&hl=en), [Chinmaya Kausik](https://chinmaya-kausik.github.io), [Ziping Xu](https://zipingxu.github.io), [Zhihan Huang](https://scholar.google.com/citations?user=_nDeOvUAAAAJ&hl=en), [Haimo Fang](https://www.linkedin.com/in/haimo-fang-50a085272)}:
* **Hybrid reinforcement learning**. If offline RL is analogous to learning by watching, and online RL is analogous to learning by doing, then hybrid RL studies what happens when machines can learn by both watching and doing. We've [shown](https://rlj.cs.umass.edu/2024/papers/RLJ_RLC_2024_152.pdf) that machines require fewer data samples under [certain conditions](https://proceedings.neurips.cc/paper_files/paper/2024/hash/d9251dc20346dffe9b6db86dcc6f8cc9-Abstract-Conference.html) when they are allowed to access both offline and online data, and can also achieve computational efficiency speedups in settings like actor-critic methods and diffusion policies. 
* **Actor-critic algorithms and diffusion policies**. We've recently [solved](https://openreview.net/forum?id=1laMy7jPux&noteId=ywb8HMfjXc) an open problem on whether actor-critic algorithms can be sample-efficient in general. This comes with some implications in practice, such as on the efficiency of exact gradients (like with DDPG and TD3) relative to on-policy sampling (like with PPO). In unreleased work submitted to NeurIPS, we show that diffusion policies can indeed achieve sublinear regret.
* **Heterogenous data within sequential decision-making**. [Chinmaya](https://chinmaya-kausik.github.io) and I have a long-running collaboration working on 
* **Statistical inference for gradient boosting**. This is unreleased work submitted to NeurIPS.
* **Inference for partially-observed Markov processes**. 
* **Applications to causal inference**. Don't want to get scooped, can elaborate offline. 
<details markdown="1">



**How have I contributed to capitalism?**

- I'm currently working at Amazon as an Applied Scientist intern. I'm part of the MOSS (Materials, Handling, and Equipment Optimization, Systems, and Science) Science team within Amazon Fulfillment Technologies and Robotics. My focus is on continuous-time behavior cloning, dynamics model estimation, and policy learning under sparse observations. This is for the purpose of optimizing package flow and staffing within the next generation of Amazon fulfillment centers. 
- During my final winter at Michigan and the following summer, I worked with Brandon (co-founder and CEO) and his brother Jonathan to build the core ML/AI systems behind Shade, an AI-driven platform for managing creative assets. Shade serves as an all-in-one hub for media storage, collaboration, and workflow automation. There, Brandon and I delivered features including a text-audio search engine powered by multimodal embeddings, a similar search engine for 3D textures, jersey number recognition, fast online face clustering for facial recognition, and lightweight asset description generation from a small set of tags. I also constructed a framework for fast and lightweight fine-tuning of embeddings for large multimodal models, and trained more than a few deep classifiers. The three of us also distilled BLIP, speeding up inference by over 7 times while maintaining a similar level of performance. 

**What am I excited about?**




Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them.
