---
layout: post
title:  "MathJax with Kramdown"
date:   2020-04-07 10:30:00
type: post
comments: true
---
Consider an ergodic diffusion $X_t$ with invariant distribution $\pi_\infty(dx)$. For example, this could be a Langevin diffusion $dX = -\nabla V(X)\,dt + \sqrt{2 T} \, dW$, and in that case the invariant distribution is the Boltzman distribution with density proportional to $\exp[ - V(x) / T]$ , where $T$ takes the role of a temperature parameter. 



So what happens if we add a small forcing term? In the case of the Langevin diffusion, one could consider a function $F$ and the perturbed diffusion 

$$dX = \color{red}{ \epsilon \, F(X)\, dt} -\nabla V(X)\,dt + \sqrt{2 T} \, dW$$

for some small $\epsilon \ll 1$.