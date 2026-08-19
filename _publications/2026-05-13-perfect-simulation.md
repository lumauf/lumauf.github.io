---
title: "Perfect simulation for interacting Hawkes processes with reset-induced variable length memory"
collection: publications
category: publications
permalink: /publication/13-05-2026-hawkes
excerpt: 'This paper is my first paper.'
venue: 'Pre-print'
#slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2605.13519'
#bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
We study a class of interacting nonlinear Hawkes point processes on the integer lattice in which each component is reset after its own jumps. The intensity of a component depends on the post-reset activity of its nearest neighbours, which produces a variable-length memory structure.
We develop a graphical construction based on a dominating Poisson environment and introduce the clan of ancestors of a space-time point. The clan is the finite or infinite backward exploration of all events whose acceptance decisions may influence the target value. Our main result is a constructive subcriticality criterion: if the sure-event rate exceeds the candidate-event rate, equivalently if β∗/(β∗−β∗)>1, then the clan is almost surely finite. The proof is based on an explicit dominating branching process associated with the genealogical structure of the exploration.
The finiteness of the clan yields a measurable local construction of the stationary regime. We prove existence and uniqueness of the stationary solution by a coupling argument and obtain an exact backward--forward perfect simulation algorithm. The algorithm terminates almost surely in the subcritical regime and returns exact samples from the stationary law. Numerical experiments, together with reproducibility details and R code, illustrate the finite-clan mechanism and the computational behaviour near the theoretical threshold. 
