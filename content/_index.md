---
title: Home
---
<p align="center">
<img src="/media/sulin_avatar.jpeg" width="350">
</p>

<style>
  /* For desktop view */
  .intro {
    font-size: 1.8em;
  }

  /* For mobile view */
  @media only screen and (max-width: 600px) {
    .intro {
      font-size: 1.5em; /* Adjust font size for mobile */
    }
  }
</style>

<span class="intro">Hi! I'm Sulin.</span>
</span> <a href="https://github.com/liusulin" style="border:none; position:relative; top:3px; left: 15px;" target="_blank"> <img src="/media/icons/github.svg" class="filter-black" width="25" height="25"></a>         <a href="https://twitter.com/su_lin_liu" style="border:none; position:relative; top:3px; left:20px;" target="_blank"> <img src="/media/icons/twitter.svg" class="filter-black" width="25" height="25"></a>        <a href="https://www.linkedin.com/in/sulin-liu" style="border:none; position:relative; top:3px; left:25px;" target="_blank"> <img src="/media/icons/linkedin.svg" class="filter-black" width="25" height="25"></a>          <a href="https://scholar.google.com/citations?user=s3NlgA4AAAAJ&hl=en" style="border:none; position:relative; left:22px; top:5px;" target="_blank"> <img src="/media/icons/google-scholar.svg" class="filter-black" width="30" height="30"></a>          <a href="mailto:sulinliu@mit.edu" style="border:none; position:relative; left:21px;top:3px; " target="_blank"> <img src="/media/icons/mail.svg" class="filter-black" width="25" height="25"></a>   <a href="https://www.dropbox.com/scl/fo/nvl71srie7qgo5mnp27cy/ANQQ0efKaqxcVVM5FE_Cwms?rlkey=oi1hfnnvbrn5u5mu36fjjt23g&st=k2i6muxe&dl=0"  target="_blank" class="cv-link" style="border:none; position:relative; left: 23px; top:-0.9px;" ><span style="font-size:1.37em"> CV  </span></a>                      

I am a postdoctoral researcher at MIT in [Rafael Gómez-Bombarelli](https://gomezbombarelli.mit.edu/)'s group, and I also collaborate with [Tommi Jaakkola](https://people.csail.mit.edu/tommi/)'s group. I received my PhD from Princeton University in 2023, advised by [Ryan P. Adams](https://www.cs.princeton.edu/~rpa/) and [Peter J. Ramadge](https://ee.princeton.edu/people/peter-j-ramadge/). In summer 2021, I interned at Meta Research with [Ben Letham](http://lethalletham.com/) and [Eytan Bakshy](https://eytan.github.io/) in the [Adaptive Experimentation](https://research.facebook.com/teams/central-applied-science/) team. I did my undergrad at National University of Singapore and worked with [Sinno Jialin Pan](https://personal.ntu.edu.sg/sinnopan/) at Nanyang Technological University, Singapore.


My research interests are broadly in machine learning, with a current focus on generative models:
 - **Planning in Diffusion/Masked Language Models**: [[DDPD: Discrete Diffusion with Planned Denoising](https://arxiv.org/abs/2410.06264)] introduces the first use of a planning model for guided self-correction in the denoising process, significantly improves generation quality compared to SOTA on GPT-2 scale language modeling and ImageNet 256 x 256.
 - **Scalable Training and Inference of Autoregressive Models**: [[Generative Marginalization Models](https://arxiv.org/abs/2310.12920)] scalable alignment with reward model, over 1000× speedup in marginal inference
 - **Amortized Inference/Optimization**: [[Marginal Inference](https://arxiv.org/abs/2310.12920), [Amortized Hyperparam. Optimization](https://papers.nips.cc/paper/2020/hash/f52db9f7c0ae7017ee41f63c2a7353bc-Abstract.html)]
 - **Interpretability and Safety in Knowledge Discovery**: [[SEBO: Sparse Bayesian Optimization](https://arxiv.org/abs/2203.01900), [ProBF: Probabilistic Safety Certificates](https://arxiv.org/abs/2112.12210)]

My work centers on innovating in **synthetic data generation**, designing complex **multi-component AI systems**, and deriving **scalable training objectives** grounded in first principles. I am passionate about using generative AI to tackle impactful real-world problems and drive advances in the next generation of AI-powered systems. 

## Representative Publications

**Think While You Generate: Discrete Diffusion with Planned Denoising**. [Paper](https://arxiv.org/abs/2410.06264) | [Code](https://github.com/liusulin/DDPD)\
<ins>Sulin Liu</ins>, Juno Nam, Andrew Campbell, Hannes Stärk, Yilun Xu, Tommi Jaakkola, Rafael Gómez-Bombarelli.\
*Under submission*, 2024.

**Flow Matching for Accelerated Simulation of Atomic Transport in Materials**. [Paper](https://arxiv.org/abs/2410.01464)\
Juno Nam, <ins>Sulin Liu</ins>, Gavin Winter, KyuJung Jun, Soojung Yang, Rafael Gómez-Bombarelli.\
*Under submission*, 2024.\
short version at *ICML Workshop on Machine Learning for Life and Material Science: From Theory to Industry applications*
(<span style="color:#b03060">Best paper in Material Science track, 2/141</span>)

**Generative Marginalization Models**. [Paper](https://arxiv.org/abs/2310.12920) | [Code](https://github.com/PrincetonLIPS/MaM) | [Video](https://icml.cc/virtual/2023/29185)\
<ins>Sulin Liu</ins>, Peter J. Ramadge, Ryan P. Adams.\
*International Conference on Machine Learning* (ICML), 2024.\
short version at *ICML Workshop on Structured Probabilistic
Inference & Generative Modeling*. (<span style="color:#b03060">Contributed talk, 6/125</span>)

**Sparse Bayesian Optimization**. [Paper](https://arxiv.org/abs/2203.01900) | [Code](https://github.com/facebookresearch/SparseBO) | [Tutorial](https://ax.dev/tutorials/sebo.html) | [Video](https://slideslive.com/38996665/sparse-bayesian-optimization?ref=search-presentations-sparse+bayesian)\
<ins>Sulin Liu</ins>\* (equal contr.), Qing Feng*, David Eriksson*, Benjamin Letham, Eytan Bakshy.\
*International Conference on Artificial Intelligence and Statistics* (AISTATS), 2023.\
short version at at *NeurIPS Workshop on Gaussian Processes, Spatiotemporal Modeling, and Decision-making Systems*. (<span style="color:#b03060">Contributed talk, top 5 selected</span>)


**Task-Agnostic Amortized Inference of Gaussian Process Hyperparameters**. [Paper](https://papers.nips.cc/paper/2020/hash/f52db9f7c0ae7017ee41f63c2a7353bc-Abstract.html) | [Code](https://github.com/PrincetonLIPS/AHGP) | [Slides](https://github.com/PrincetonLIPS/AHGP/blob/main/slides/AHGP_slides.pdf) | [Video](https://slideslive.com/38937035/taskagnostic-amortized-inference-of-gaussian-process-hyperparameters?ref=search-presentations-Task-Agnostic+Amortized+Inference+of+Gaussian+Process+Hyperparameters)\
<ins>Sulin Liu</ins>, Xingyuan Sun, Peter J. Ramadge, Ryan P. Adams.\
*Advances in Neural Information Processing Systems* (NeurIPS), 2020.\
short version at *7th ICML Workshop on Automated Machine Learning*. (<span style="color:#b03060">Spotlight talk</span>)

## Recent News
- 10/2024: Gave a talk on DDPD at Google DeepMind Seminar Series on Generative Modeling, Sampling and Transport.
- 10/2024: Preprint of DDPD is out on [arXiv](https://arxiv.org/abs/2410.06264). Check out the summary of the paper in this [thread](https://x.com/su_lin_liu/status/1846588886493094072)!
- 05/2024: Generative Marginalization Models accepted to ICML 2024!
- 12/2023: Invited to talk at Hong Kong University Institute of Data Science.
- 09/2023: Started my postdoc at MIT.
