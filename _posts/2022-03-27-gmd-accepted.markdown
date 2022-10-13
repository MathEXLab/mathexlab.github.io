---
layout: news
title: New Publication
subtitle: Efficient high-dimensional variational data assimilation 
  with machine-learned reduced-order models
icon: print
date: 2022-03-27
image: /images/post_paper_gmd_anl.jpg
hero_image: false
hero_height: is-small
hero_darken: true
show_sidebar: false
tags: research computational mathematics
summary: |-
  Paper accepted in <b>Geoscientific Model Development (GMD)</b>
  on efficient ways of implementing variational data assimilation 
  using reduced order models obtained with machine learning.
---

<html>
  <div class="content">
  Our paper titled <u>Efficient high-dimensional variational data 
  assimilation with machine-learned reduced-order models</u> was 
  just accepted for publication in <i>Geoscientific Model Development 
  (GMD)</i>. 
  
  Thanks to Argonne National Laboratory collaborators: 
  <b>Romit Maulik</b>, <b>Vishwas Rao</b>, <b>Jiali Wang</b>, 
  <b>Emil Constantinescu</b>, <b>Bethany Lusch</b>, 
  <b>Prasanna Balaprakash</b>, <b>Ian Foster</b> and <b>Rao Kotamarthi</b>
  <br>
  <a href="https://gmd.copernicus.org/articles/15/3433/2022/" 
     style="">
    <button class="button is-outlined is-link is-small"> <b>LINK</b> </button>
  </a>
  </div>


  <div class="content"><h4> Plain-language description </h4></div>
  <hr>
  <div class="notification is-info is-light">
    A physical system, such as the atmosphere, can be characterized 
    by our prior knowledge, in the form of a mathematical model, plus 
    a set of observations from various sensors. 

    Data assimilation (DA) combines our prior knowledge of the system, 
    i.e. the mathematical model, with observations to estimate of state 
    of the system at a desired time. 
    
    In this paper, we propose a data assimilation approach that uses 
    a machine learning emulator to replace the (usually expensive) 
    mathematical model adopted in 4-dimensional data assimilation 
    (also referred to as 4D-Var). Our results indicate that 
    machine-learning-assisted data assimilation is faster than 
    traditional model-based data-assimilation by 4 orders of 
    magnitude, allowing computations to be performed on a workstation 
    rather than a dedicated high-performance computer.
  </div>

  <div class="content"><h4> Abstract </h4></div>
  <hr>
  <div class="notification is-light">
    Data assimilation (DA) in geophysical sciences remains the cornerstone 
    of robust forecasts from numerical models. Indeed, DA plays a crucial 
    role in the quality of numerical weather prediction and is a crucial 
    building block that has allowed dramatic improvements in weather 
    forecasting over the past few decades. DA is commonly framed in 
    a variational setting, where one solves an optimization problem 
    within a Bayesian formulation using raw model forecasts as a prior 
    and observations as likelihood. This leads to a DA objective function 
    that needs to be minimized, where the decision variables are the 
    initial conditions specified to the model. In traditional DA, the 
    forward model is numerically and computationally expensive. Here 
    we replace the forward model with a low-dimensional, data-driven, 
    and differentiable emulator. Consequently, gradients of our 
    DA objective function with respect to the decision variables 
    are obtained rapidly via automatic differentiation. We demonstrate 
    our approach by performing an emulator-assisted DA forecast 
    of geopotential height. Our results indicate that emulator-assisted 
    DA is faster than traditional equation-based DA forecasts by 
    4 orders of magnitude, allowing computations to be performed 
    on a workstation rather than a dedicated high-performance computer. 
    In addition, we describe accuracy benefits of emulator-assisted 
    DA when compared to simply using the emulator for forecasting 
    (i.e., without DA). Our overall formulation is denoted AIEADA 
    (Artificial Intelligence Emulator-Assisted Data Assimilation).
  </div>

  <br>
</html>
