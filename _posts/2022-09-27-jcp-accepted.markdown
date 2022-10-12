---
layout: news
title: New Publication in Nature Reviews Physics
subtitle: Spectral/hp element methods linear mechanism of (apparent) energy transfer in Fourier space
icon: users
date: 2022-09-27
image: /images/post_paper_jcp.jpg
hero_image: false
hero_height: is-small
hero_darken: true
show_sidebar: false
tags: research computational mathematics
summary: |-
  Paper accepted in Journal of Computational Physics
  on Spectral/hp element methods' linear mechanism
  of (apparent) energy transfer in Fourier space
  for implicit Large-Eddy Simulation (LES).
---

<html>
  <div class="content">
  Our paper titled <i>Spectral/hp element methods' linear
  mechanism of (apparent) energy transfer in Fourier space:
  insights into dispersion analysis for implicit LES</i>
  was just accepted for publication in Journal of Computational
  Physics.
  </div>

  <div>
    <a href="https://authors.elsevier.com/c/1fpiQ508HsaBh" style="">
      <button class="button is-outlined is-info is-small"> LINK </button>
    </a>
  </div>

  <div class="content"><h4> Plain-language description </h4></div>
  <div class="notification is-success is-light">
    Broadly speaking, physical systems can be described by
    partial differential equations (PDEs). These are equations
    that depend on more than one independent variable (e.g,
    they may depend on time and space). In addition, they
    contain changes (or derivatives) of the physical (or
    prognostic) variables with respect to the independent
    variables). PDEs frequently exhibit highly nonlinear
    and multiscale behaviour, and the usually do not have
    analytical solutions. Hence, to solve them it is common
    to rely on numerical approximations.
    These approximations may suffer from numerical errors,
    that might produce an unphysical solution. In this paper,
    we build on previous work on the topic, and furhter characterize
    some of these errors for spectral element numerical methods.  
  </div>

  <div class="content"><h4> Abstract </h4></div>
  <div class="notification is-info is-light">
    In recent years, different dispersion-diffusion (eigen)analyses
    have been developed and used to assess various spectral element
    methods (SEMs) with regards to accuracy and stability, both of
    which are very important aspects for under-resolved computations
    of transitional and turbulent flows. Not surprisingly, eigenanalysis
    has been used recurrently to probe the inner-workings of SEM-based
    implicit LES approaches, where numerical dissipation acts alone
    in lieu of a subgrid model. In this study we present and discuss
    an intriguing linear mechanism that causes energy transfer across
    Fourier modes as seen in the energy spectrum of SEM computations.
    Despite its linear nature, this mechanism has not been considered
    in eigenanalyses so far, possibly due to its connection to the
    often overlooked multiple eigencurves feature of periodic eigenanalysis.
    As we unveil the mechanism in the simplified context of linear advection,
    we point out how its effects might take place in actual turbulence
    simulations. In particular, we highlight how taking it into account
    in eigenanalysis can improve dissipation estimates in wavenumber
    space, potentially allowing for a superior correlation between
    dissipation estimates and energy spectra measured in SEM-based
    eddy-resolving turbulence computations.
  </div>

  <br>
</html>
