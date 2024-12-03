---
title: Causal Inference
layout: default
permalink: /causal-inference/
nav_order: 9
has_children: false
---

### **Overview**
Applied Econometrics is concerened with the interpretation of statistical results in various contexts. In this course, we anchor ourselves around the ideas of potential outcomes framework and local variation of the treatment variable. These two concepts motivate the use of instrumental variables, regression discontinuity, and difference-in-differences and therefore will be essential to our understanding of the empirical literature.

One point to highlight is that in contrast to other notes on applied econometrics ([Goldsmith-Pinkham](https://github.com/paulgp/applied-methods-phd), [Hull](https://about.peterhull.net/metrix), [Roth](https://github.com/jonathandroth/Econ1630_Github)), these slides/notes are quite brief. They're meant to help one develop a conceptual framework that one can use to read the typical applied micro paper. We're going to let detials slip through the cracks. The hope, as Brad Osgood says is that "If you keep the big picture in mind, in many cases the details will take care of themselves --really." 

<iframe src="https://slides.com/pharringtonp19/housing-homelessness-econometrics/embed?byline=hidden" width="576" height="420" title="Housing & Homelessness: Applied Econometrics" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

### **Randomized Control Trials**
In this class we discuss the ethics and responsabilities around Randomized Control Trials. In particular we discuss some of the key issues that arise when randomizing financial resources among those in great need. 

<div style="border: 2px solid black; padding: 10px; text-align: center; width: calc(33.33% - 1%); margin: 0 auto;">
  <!-- Title of the PNG -->
  <div style="font-weight: bold;">Kinstler (2024)</div>
  
  <!-- PNG Image -->
  <a href="https://www.economist.com/1843/2024/03/01/how-poor-kenyans-became-economists-guinea-pigs" style="display: block;">
    <img src="./../assets/images/economist.png" alt="Alt text" style="width: 100%; height: auto;" />
  </a>
</div>

### **Language Models**

Bengio et al. (2003) highlight the challenge of learning probability distributions over high dimensional discrete spaces and the **need** to generalize. It emphasizes how the task of gernalization is equivalent to transfering probability mass. Randford et al. (2018) describe how the curse of dimensionality at that the task level (dataset, objective), make an explicit multi-task approach infeasible. Bertsch et al. (2024) compare the relative effectiveness of in ncontext Learning versus fine-tuning for multic-class classifaction as the size of the examples increases. [Slides](https://slides.com/pharringtonp19/the-final-lecture-5976a6/fullscreen)

<div style="display: flex; flex-wrap: wrap; justify-content: space-between; border: 2px solid black; padding: 10px;">

  <!-- First PDF and its title -->
  <div style="width: calc(33.33% - 1%); border-right: 2px solid gray;">
    <div style="text-align: center; font-weight: bold;">Bengio et al. (2003)</div>
    <a href="https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf" style="display: block;">
      <img src="./../assets/images/bengio.png" alt="Alt text" style="width: 100%; height: auto;" />
    </a>
  </div>

  <!-- Second PDF and its title -->
  <div style="width: calc(33.33% - 1%); border-right: 2px solid gray;">
    <div style="text-align: center; font-weight: bold;">Radford et al. (2018)</div>
    <a href="https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf" style="display: block;">
      <img src="./../assets/images/gpt2.png" alt="Alt text" style="width: 100%; height: auto;" />
    </a>
  </div>

  <!-- Second PDF and its title -->
  <div style="width: calc(33.33% - 1%); ">
    <div style="text-align: center; font-weight: bold;">Bertsch et al. (2024)</div>
    <a href="https://arxiv.org/pdf/2405.00200" style="display: block;">
      <img src="./../assets/images/ict.png" alt="Alt text" style="width: 100%; height: auto;" />
    </a>
  </div>

</div>


<div style="border: 2px solid black; padding: 10px; text-align: center; width: calc(33.33% - 1%); margin: 0 auto;">
  <!-- Title of the PNG -->
  <div style="font-weight: bold;">Mikolov et al. (2013)</div>
  
  <!-- PNG Image -->
  <a href="https://aclanthology.org/N13-1090.pdf" style="display: block;">
    <img src="./../assets/images/cont_rep.png" alt="Alt text" style="width: 100%; height: auto;" />
  </a>
</div>