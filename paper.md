---
title: 'ComCH: A lightweight specialized computer algebra system for the study of commutativity up-to-coherent-homotopies'
tags:
  - Python
  - computer algebra system
  - topology
  - homotopical algebra
  - operads
  - cohomology operations
authors:
  - name: Anibal M. Medina-Mardones
    orcid: 0000-0002-0905-262X
    affiliation: "1, 2" # (Multiple affiliations must be quoted)
affiliations:
 - name: Max Planck Institute for Mathematics, Bonn, Germany
   index: 1
 - name: University of Notre Dame, IN, USA
   index: 2
date: 11 November 2020
bibliography: paper.bib
csl: cambridge-university-press-numeric.csl
---

# Summary

All the basic notions of number, from the integers to the complex, are equipped with a commutative product, and it was believed until Hamilton's introduction of the quaternions, that the product of any number system must be commutative. Hamilton's discovery allowed for the consideration of other algebraic structures where commutativity is not assumed, and the conceptual shift that followed is only comparable to the effect non-euclidean geometries had in the study of shapes. Around a century later, after the development of the novel fields of topology and homotopy, mathematicians returned to the question of commutativity and identified other levels enriching the basic dichotomy. These intermediate structures correspond to coherent systems correcting homotopically the lack of strict commutativity, and constitute the focus of extensive current research.

# Statement of need

An important challenge for the application of commutativity up-to-coherent-homotopies and related notions, which are often defined non-constructively, is to describe them in effective terms suitable for concrete computations. `ComCH`, a dependency-free `Python 3` package, is a specialized computer algebra system that serves to bridge the gap between theoretical concepts and concrete applications in this context, by providing effective models for complexes parameterizing different levels of homotopical commutativity.

Some theoretical concepts modeled in this work have already found modern applications in, for example, topological data analysis [Medina-Mardones -@mm_persistence], condensed matter physics [@kapustin_thorngren], and motion planning [@g_lm_rm], with a key notion being that of cohomology operation at the chain level. See [@mm], [@brumfiel_mm_morgan], and `[@kaufmann_mm]` for more details. This notion is carefully implemented in `ComCH` and serves as a primary example of its capabilities.

asdasd

@mm_persistence says blah.

lnlk 

-@mm_persistence says blah.

[-@mm_persistence says blah.]

asdasd

@mm_persistence [p. 33] says blah.


# Mathematical overview

Following the pioneering work of Steenrod, Cartan, Adem, Stashef, Boardman-Vogt, May, Dyer-Lashof and others, today we understand the correct framework for the study of commutativity up-to-coherent-homotopies as the one provided by operads and PROPs. In particular, $E_n$-operads play a central role parameterizing the different levels of homotopical commutativity. In this package, we focus on the category of chain complexes, and consider two models for the $E_\infty$-operad which are equipped with filtrations by $E_n$-operads. These models are respectively due to McClure-Smith [@mcclure_smith] and Berger-Fresse [@berger_fresse] and are known as the surjection and Barratt-Eccles operads.

# Acknowledgements

We gratefully acknowledge the support of Kathryn Hess, contributions from Djian Post, Wojciech Reise and Michelle Smith, and stimulating conversations with Dennis Sullivan, Greg Brumfiel, John Morgan, Ralph Kaufmann, Paolo Salvatore, Umberto Lupo, and Guillaume Tauzin. Work partially supported by Innosuisse grant 32875.1 IP-ICT - 1.

# References