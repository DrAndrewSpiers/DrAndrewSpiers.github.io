---
title: 'Opening up second-order black hole perturbation theory with two papers and Mathematica resources'
date: 2023-08-07
permalink: /posts/2012/08/blog-post-2-papers/
tags:
  - cool posts
  - category1
  - category2
---

Recently I put two papers on the arxiv, which both focus on tools and techniques for tackling second-order black hole perturbation theory.

Not only do these papers offer excellent descriptions of second-order methods, they both come with tools in Mathematica that you can use to compute second-order calculations in your research.

The first paper, [Second-order Teukolsky formalism in Kerr spacetime: formulation and nonlinear source](https://arxiv.org/abs/2305.19332/){:target="_blank"}{:rel="noopener noreferrer"}), covers the different second-order Teukosky equations. Since Adma Pound and I found the reduced second-order Teukolsky equation in 2019, I have been singing its praises for second-order self-force calculations. Our paper covers its advantages. The accompanying [mathematica booklet](https://github.com/DrAndrewSpiers/NP-and-GHP-Formalisms-for-2nd-order-Teukolsky/){:target="_blank"}{:rel="noopener noreferrer"}) provides many tools in the Newman--Pernrose and GHP formalisms, including expressions for the source of the reduced second-order Teukolsky equation.

The second paper, [Second-order perturbations of the Schwarzschild spacetime: practical, covariant and gauge-invariant formalisms](https://arxiv.org/abs/2306.17847/){:target="_blank"}{:rel="noopener noreferrer"}), covers coordinate expressions for second-order black hole perturbation theory in Schwarzschild spacetime. The various conventions for calculations in Schwarzschild are covered, including the Barack--Lousto--Sage basis, Martel and Poisson Conventions, scalar, vector and tensor spherical harmonics, spin-weighted spherical harmonics, and the Teukolsky equation. This paper and accompanying Mathematica package [PerturbationEquations](https://bhptoolkit.org/PerturbationEquations/){:target="_blank"}{:rel="noopener noreferrer"}), provide expressions for the second-order field equations and sources at second-order in a coordinate form in various basis and gauges. The plan is to extend this package to Kerr once expressions are obtained.

Please, take these resources and run with them. If you need any help or find any bugs, then you can contact me at andrew.spiers@nottingham.ac.uk