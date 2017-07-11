---
title: Summer School Lectures for Amplitudes 2017...
excerpt: Video & computational notebook generated as live-lectures posted.
header:
   teaser: doubleCopy.png
   overlay_color: "#5e616c"
   overlay_image: doubleCopy.png
   overlay_filter: .2
categories:
- lectures
tags:
- lectures
- double copy
- amplitudes
- color-kinematics
- video
- mathematica
- predictions
author: John_Joseph
pinned: true
---

Link to all summer school lectures hosted by the Higgs Center for Theoretical Physics in Edinburgh, [here](https://indico.ph.ed.ac.uk/event/30/).  

Other lecturer's:
 Stefan Weinzierl, Marcus Spradlin, Jaroslav Trnka, and Johannes Henn.

Also nice research presentations by: Jorrit Bosma, Sebastian Mizera, Gustav Mogull, Chia-Hsien Shen, Andrew McLeod, Theresa Abl, Joe Farrow, and Andres Luna-Godoy.  

# Lectures
Introducing graph methods for modern amplitude calculation.  Topics:

* Graphs and Ordered Amplitudes

* Integrand Verification -- two-loops.

* Integrand Cut Construction -- two loops.

* Introduction to Color-Kinematics

Unsatisfactory tensile strength of one leg necessitated a little creativity in lecturing.  I didn't want to present a straight-up slide show which I find a little off-putting for lectures. Rather I decided to live-generate a Mathematica notebook as the projected lecture. Obviously this could be incredibly off-putting, but it's the type of thing I would've loved to see when I entered this field in 2006.

Indeed, I organized around what I had to do as a grad student to think through and understand the graphical mechanics behind the first paper that made sense to me re: the unitarity method -- the spectacular 1998 two loop maximally supersymmetric supergravity calculation of Bern, Dixon, Dunbar, Perelstein and Rozowsky. You can find the paper  [here](https://arxiv.org/abs/hep-th/9802162).  

I start by introducing the need for graphs with structure to encode the types of minus signs that show up around vertex flips for adjoint  color-weights.  I explain how to generate the graphs contributing to cuts and to dress them with a candidate graphically organized integrand (mapping from graphs to weights).  We poke at what's necessary to constrain a graphical integrand to match a given theory, and at the end delve into constraints that have nothing to do with physical observation but have everything to do with lining up *local* stories relating gauge theory and gravity predictions.

I did a little post-cleanup to make it somewhat more readable for people who don't get to hear my vocalizations, but have posted sooner rather than indulge ever-present obsessive impulses towards stand-alone readability.

I don't emphasize it but I've dropped in some pretty [chonto](http://www.urbandictionary.com/define.php?term=chonto) casually tossed off calculations like automatically taking gauge integrands to symmetric double-copy gravity cuts via KLT , or evaluating state sums for generic cuts in various SUSY gauge theories at the push of a button. As these weren't (primarily) graphical methods they weren't central to these lectures, but I can probably be tempted into writing some words about them at some point.  

Notebook uses my github hosted amplitudes graph library [ampGraphTools]((https://github.com/drjjmc/ampGraphTools_mma)). (No need to install the library, it imports directly from github if the lectures' notebook is executed.)  Presented with an emphasis on output, not so much on code/library use, but does provide a slice of insight into how I actively think through this graphical playground when I'm poking about.

As a side note, I saved the notebook periodically throughout my lecture, and had it temporarily hosted via a bit.ly link for students to grab as they liked.  Interesting to see the stats of how many students bothered to grab the notebook vs who couldn't care less.

Definitely welcome any questions, desire for clarification, and requests for any topics I skipped in this limited lecture time.

Video for [[Lecture 1](https://media.ed.ac.uk/media/Amplitudes+Summer+School+2017+-+ohn+Joseph+CarrascoA+Graphical+Methods+for+Sharp+PredictionA+from+theories+entirely+formal+to+the+utterly+effective+-+lecture+1+/1_aan0792b/60996171)]
[[Lecture 2](https://media.ed.ac.uk/media/Amplitudes+Summer+School+-+John+Joseph+CarrascoA+Graphical+Methods+for+Sharp+PredictionA+from+theories+entirely+formal+to+the+utterly+effective+-+lecture+2/1_f4m1wl5h)] [[Lecture 3](https://media.ed.ac.uk/media/Amplitudes+Summer+School+2017A+John+Joseph+Carrasco++-+Graphical+Methods+for+Sharp+PredictionA+from+theories+entirely+formal+to+the+utterly+effective+-+lecture+3/1_jqiem0l6)] [[Lecture 4](https://media.ed.ac.uk/media/Amplitudes+Summer+School+2017A+John+Joseph+Carrasco+-+Graphical+Methods+for+Sharp+PredictionA+from+theories+entirely+formal+to+the+utterly+effective+-+lecture+4/1_3chpd4tj)]

Can find live Mathematica notebook for all 4 lectures [here](https://figshare.com/articles/Graphical_Methods_for_Sharp_Predictions_Live_Lecture_Notes_-_Amplitudes_2017_Summer_School/5197213).
