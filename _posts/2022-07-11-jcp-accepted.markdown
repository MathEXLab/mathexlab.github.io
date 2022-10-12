---
layout: news
title: New Publication
subtitle: Neural-network learning of SPOD latent dynamics
icon: users
date: 2022-07-11
image: /images/post_paper_jcp_spod.jpg
hero_image: false
hero_height: is-small
hero_darken: true
show_sidebar: false
tags: research computational mathematics
summary: |-
  Paper accepted in <b>Journal of Computational Physics</b>
  on emulating Spectral Proper Orthogonal Decomposition's 
  latent space.
---

<html>
  <div class="content">
  Our paper titled <u>Neural-network learning of SPOD latent 
  dynamics</u> was just accepted for publication in <i>Journal 
  of Computational Physics</i>. 
  
  Thanks to all authors: 
  <b>Andrea Lario</b> (SISSA, Italy), <b>Romit Maulik</b> 
  (Argonne National Laboratory, USA), <b>Oliver Schmidt</b> 
  (University of California San Diego, USA), and <b>Gianluigi 
  Rozza</b> (SISSA, Italy).
  <br>
  <a href="https://www.sciencedirect.com/science/article/pii/S002199912200537X" 
     style="">
    <button class="button is-outlined is-link is-small"> <b>LINK</b> </button>
  </a>
  </div>


  <div class="content"><h4> Plain-language description </h4></div>
  <hr>
  <div class="notification is-info is-light">
    Deep learning strategies are gaining traction as a tool 
    for surrogate modeling (also referred to as emulation 
    or non-intrusive reduced order modeling) of dynamical 
    systems. Data associated to dynamical systems usually 
    have both a space and a time component. For instance, 
    one can think of the evolution in time of the temperature 
    at various locations worldwide. The various locations 
    where the temperature is provided constitute the space 
    component of the data, while the time snapshots constitute 
    the time component. A common case in computational 
    physics is when we have access to values of a given 
    quantity at <i>S</i> spatial locations (or grid points), 
    for <i>N</i> time snapshots. In this case, the dimension 
    of the problem is <i>S</i> x <i>N</i>, where the spatial 
    component <i>S</i> might be extremely large. The key in 
    surrogate modeling or emulation is to identify a suitable 
    representation of the data that reduces the high dimensionality 
    of <i>S</i> to a more computationally manageable number, 
    that we denote with <i>Sr</i> << <i>S</i>. The new reduced 
    space of dimension <i>Sr</i>, often referred to as the latent 
    space, is where we seek to learn the time evolution of the 
    system. The learnt reduced space can then be used to reconstruct 
    the original high-dimensional space by inverting the data 
    compression. Emulation techniques are particularly useful 
    when fast predictions are required, e.g., in the context 
    of digital twins.
  </div>

  <div class="content"><h4> Abstract </h4></div>
  <hr>
  <div class="notification is-light">
    We aim to reconstruct the latent space dynamics of high dimensional, 
    quasi-stationary systems using model order reduction via the spectral 
    proper orthogonal decomposition (SPOD). The proposed method is based 
    on three fundamental steps: in the first, once that the mean flow 
    field has been subtracted from the realizations (also referred to 
    as snapshots), we compress the data from a high-dimensional 
    representation to a lower dimensional one by constructing the SPOD 
    latent space; in the second, we build the time-dependent coefficients 
    by projecting the snapshots containing the fluctuations onto the SPOD 
    basis and we learn their evolution in time with the aid of recurrent 
    neural networks; in the third, we reconstruct the high-dimensional 
    data from the learnt lower-dimensional representation. The proposed 
    method is demonstrated on two different test cases, namely, a 
    compressible jet flow, and a geophysical problem known as the 
    Madden-Julian Oscillation. An extensive comparison between SPOD 
    and the equivalent POD-based counterpart is provided and differences 
    between the two approaches are highlighted. The numerical results 
    suggest that the proposed model is able to provide low rank predictions 
    of complex statistically stationary data and to provide insights 
    into the evolution of phenomena characterized by specific range 
    of frequencies. The comparison between POD and SPOD surrogate 
    strategies highlights the need for further work on the characterization 
    of the interplay of error between data reduction techniques 
    and neural network forecasts.
  </div>

  <br>
</html>
