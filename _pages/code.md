---
title: "A physicist's code"
layout: single
tags:
permalink: /code/
modified: 2017-06-12
header:
  overlay_color: "#5e616c"
  overlay_image: sixPtRelations.jpg
  overlay_filter: .4
  caption: ""
excerpt:
author: John_Joseph
comments: true
---

I'll update here with links to code I've contributed to/developed. -jjmc

## Related to the Effective Field Theory of Large Scale Structure
* some relevant EFTofLSS papers:
  * [[Establishing the EFT](http://arxiv.org/abs/arXiv:1206.2926)]
  * [[IR-safe two-loop power spectrum](http://arxiv.org/abs/arXiv:1304.4946)]
  * [[EFT at two-loops](http://arxiv.org/abs/arXiv:1310.0464) ]

* **CosmoEFT:** Calculating 1 & 2-loop IR-safe power spectra for realistic cosmologies.  (c++)  Hosted [here](http://web.stanford.edu/~senatore/CosmoEFT.tar.gz)

    * Uses [Copter](http://mwhite.berkeley.edu/Copter/) to map from transfer function + cosmology to linear powerspectrum.

    * Uses the [Monte-Carlo integration](https://en.wikipedia.org/wiki/Monte_Carlo_integration)  library [CUBA](http://www.feynarts.de/cuba/).

    * Originally developed in a project with Daniel Green, Simon Forman, and Leonardo Senatore towards precision EFTofLSS predictions at two-loops. Updated later to expand around Planck Best-fit Cosmology by M. Cataneo and S. Forman for [this paper](https://inspirehep.net/record/1469026). Currently maintained by [M. Cataneo](http://www.ph.ed.ac.uk/people/matteo-cataneo).

* See also other useful EFT code Leonardo has curated / been involved with: [here](http://web.stanford.edu/~senatore/), esp. towards resumming in the IR.

* If there's pedagogic interest, I can upload some early Mathematica code for EFT of LSS at 1-loop including exact time evolution.

## Related to scattering amplitudes, unitarity, and double-copy.
* some relevant amplitudes papers:
   * [TASI 2014 lecture notes](http://arxiv.org/abs/arXiv:1506.00974).
   * [State sums in 4D for SUSY gauge theories](http://arxiv.org/abs/arXiv:0903.5348)
   * [Double-copy at loop level](http://arxiv.org/abs/arXiv:1004.0476)
   * [Color-kinematics and $$(n-3)!$$(BCJ) Relations](http://arxiv.org/abs/arXiv:0805.3993)

* **ampGraphTools:** Mathematica library for graph manipulation/dressing esp towards multiloops. Hosted [here](https://github.com/drjjmc/ampGraphTools_mma).
   * I use this for pretty much any amplitudes calculation.  Working it's way towards documentation and actual public release.  Feel free to poke around.
