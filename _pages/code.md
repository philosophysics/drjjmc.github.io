---
title: "A physicist's code"
layout: single
tags:
permalink: /code/
modified: 2017-06-12
header:
  overlay_color: "#5e616c"
  overlay_image: graphOps.jpg
  overlay_filter: .4
  caption: ""
excerpt:
author: John_Joseph
comments: true
---

I'll update here with links to code I've contributed to/developed. -jjmc

## Related to the Effective Field Theory of Large Scale Structure
Related original papers [here](http://inspirehep.net/search?ln=en&ln=en&p=find+a+Carrasco+and+a+Senatore&of=hb&action_search=Search&sf=&so=d&rm=citation&rg=100&sc=0):

* **CosmoEFT:** Calculating 1 & 2-loop IR-safe power spectra for realistic cosmologies.  (c++)  Hosted [here](http://web.stanford.edu/~senatore/CosmoEFT.tar.gz)

    * Uses Copter ([here](http://mwhite.berkeley.edu/Copter/)) to map from transfer function + cosmology to linear powerspectrum.

    * Uses the monte carlo library CUBA ([here](http://www.feynarts.de/cuba/))  for integration.

    * Originally developed in a project with Daniel Green, Simon Forman, and Leonardo Senatore towards precision EFTofLSS predictions at two-loops. Updated later to expand around Planck Best-fit Cosmology by M. Cataneo and S. Forman for [this paper](https://inspirehep.net/record/1469026). Currently maintained by [M. Cataneo](http://www.ph.ed.ac.uk/people/matteo-cataneo).

* See also other useful EFT code Leonardo has curated / been involved with: [here](http://web.stanford.edu/~senatore/), esp. towards resumming in the IR.

* If there's pedagogic interest, I can upload some early Mathematica code for EFT of LSS at 1-loop including exact time evolution.

## Related to scattering amplitudes, unitarity, and double-copy.
Related TASI 2014 lecture notes [here](http://arxiv.org/abs/arXiv:1506.00974).  

* **ampGraphTools:** Mathematica library for graph manipulation/dressing esp towards multiloops. Hosted [here](https://github.com/drjjmc/ampGraphTools_mma).
   * I use this for pretty much any amplitudes calculation.  Working it's way towards documentation and actual public release.  Feel free to poke around.
