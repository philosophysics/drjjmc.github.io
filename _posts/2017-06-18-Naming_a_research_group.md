---
title: Naming a research group...
excerpt: Wherein our hero sets out to find a name, and discovers yet his very soul.
categories:
- thoughts
tags:
- declarative physics
- sociology
- differential equations
- perturbations
- calculus helps
author: John_Joseph
pinned: false
---

So recently I found myself in the rather novel position of having to name my research group.  This was a bit of a stumper, as my interests aren't particularly narrow, and I've been hiring fairly broadly.  

Computers?
---------
An early contender was *"Advanced" Theoretical Physics*, in the computer-aided spirit of [Advanced Chess](https://en.wikipedia.org/wiki/Advanced_Chess).  Unlike some of our antecedents, I don't view engaging symbolic processor neural-adjuncts as some sort of intellectual *juicing*[^juice]. Indeed I'm more than happy to automate any aspect of my inquiry towards improved:
  * Accuracy (Verifiability / Reproducibility);
  * Coverage.

Both of which up the chances of discovering something truly interesting.  I'll likely be writing more about all of these soon.

[^juice]: That said, I'm completely willing to back a proposal for a **straight-edge** arXiv  sub-branch for research performed with neither *Mathematica* nor *caffeine*.

But as much as I enjoy the ever increasing meta-cognitive aspects of engaging our silicon friends to aid in the quest for deeper knowledge, I don't really think of this as a central enough tenant so as to be *defining*.

Also, and all things being equal, it's worth considering the following point: using the word *advanced* to describe one's own work is the type of thing that tends to piss people off.  I'm preternaturally pleased with myself whenever I realize there's an opportunity to avoid arbitrarily aggravating my colleagues. So what should my group be called?

Calculations?
-------------
A common trope is that theoretical physicists ambulate about dreaming big dreams. Sure we do. But what we *work* on is making predictions: some very formal like the high-energy (small-distance) behavior of supergravity. Some are highly phenomenological like early Dark Matter evolution towards the cosmological formation of Large Scale Structure.  

My group doesn't shy away from technically challenging problems -- rather we see them as providing strategic pressure to push our current ideas, tools, and interpretations to their failure-point.  Yet, every calculation we do is driven by a deep curiosity.  Every time we gear up for one of our analytic "experiments" we do so because we
expect the *theoretical data* we extract to be invaluable.  So while we're partial to calculating, it's the resulting data we're interested in; the journey might be fun, but in our case we really are interested in the destination.

Perturbation?
-------------
Physicists like to get to the nub of an issue -- simplifying away the stuff we don't care about to get to the heart of the stories worth telling.  Even when you've simplified away all the details you think are garbage (relevant to what you want to explore) you're often confronted with some differential equations whose solution may have important properties you don't sufficiently appreciate.

> Let me make an aside here about solutions and differential equations.  Did I say "confronted with diffEQs whose solution you do not know?"  I absolutely did not!  I hope the following tautology is obvious to everyone:  By specifying some (set of) differential equation(s) you've implicitly specified the class of solutions.  Ever since my volatile youth, it always got under my skin to hear people say they don't know the function that solves a differential equation.  Differential equations tell us how functions behave -- what else could anyone want in a solution??
>
> Let's just consider a simple example that's in a very real sense (with a slight generalization) kind of behind everything:
$$
\begin{align}
  \partial^2_t f(t) &= -f(t) &f(0)&=1 &f'(0)&=0\\
  \partial^2_t g(t) &= -g(t) &g(0)&=0 & g'(0)&=1\\
  \partial^2_t h(t) &= -h(t) & h(0)&=1 & h'(0)&=i
\end{align}
$$
By knowing nothing beyond the boundary conditions and the differential equations, it turns out we know a tremendous amount about these functions.  For example we know that  $$g' = f$$, which in turn means that $$f'=-g$$.  We know that $$h(t)=f(t)+i g(t)$$.  Cool.
But there's more fun to be had.  Note that $$|h|^2=f^2 + g^2$$. Taking the derivative of both sides:
$$
\begin{align}
\partial_t(|h|^2) &= 2\, f \,f' +  2 \,g \,g'\\
&= - 2 \,f\, g+2\, g \,f=0
\end{align}
$$
which means that $$|h|^2$$ is constant.  Since $$|h(0)|^2= 1$$ this means  $$f(t)^2 + g(t)^2 =1$$.  This is a spectacular result at the heart of trigonometry! (Of course you've already realized that $$f$$ is the cosine function, $$g$$ is the sine function, and $$h(t)=e^{i t}$$).
>
> Can we go further and derive those pesky trig identities from middle school?  Of course we can -- but let's leave that as an exercise to the reader.  From just considering these differential equations we know everything about these solutions except perhaps how to get numbers out.  But in fact we even know this, recalling our Taylor expansions:
$$\begin{align}
f(t)&=f(0) + t f'(0) + t^2 f''(0)/2! + t^3 f'''(0)/3!+\cdots\\
 &=1 -t^2/2 + t^4/4! -t^6/6!+-\cdots\,.
\end{align} $$  Which has taken me...

back to perturbations...

If you don't know sufficient properties of your (implicitly defined) solution to claim you *know* the solution, you can still get numbers out -- predictions. If you can find some parameter that is small enough you can expand around it and go after approximate solutions whose errors are parametrically controlled. In fact I'll go so far as to say:

> All physical solutions (even "exact" solutions) are perturbative in the crap you don't care about.

The tricky bit is when you care about the stuff that makes your life complicated -- but in this case we can try to expand about the complications.  A lot of our calculations are organized into formal expansions around some parameter which we then typically take to be small.  Why small? This is so that successive orders are parametrically suppressed and can eventually be neglected in prediction.  The above formula for $$f(t)$$ is true to all values of $$t$$.  Something nice happens with the numbers for $$t<1$$ --- I don't need to go very far in the expansion before $$t^n<<1$$.   

In any case, this is called a perturbative expansion as we imagine these corrections as small changes or perturbations to the leading order solution given a small enough parameter.  This is great, and a handy thing to have in one's tool belt. But again, it's not so much the tools as why we're going after the problems we do.  I'm not exactly sure what the point of a theory group's name is, but one might hope that it coordinates towards the type of physics one aspires to do.  

Skepticism and Trust
-----------------------

The more that I thought about it the more I realized that most of my approach is marked by the simultaneous presence of two attitudes. I have a tremendous amount of trust in the *what* -- the invariant predictions -- independent of choice or framework up to parametrically controlled error.   I'm much more skeptical about the ultimate truth of the stories -- the *how* (think Lagrangian's / Hamiltonians / particular gauge choices / which spectator or auxiliary fields we allow and which we integrate out etc) -- that let us arrive at these predictions.  

 I believe in predictions up to the point that they are consistent with actual observations.  I tend to think of the stories we have so far developed  behind them as effective just-so tales: grasping, yes, some essence of truth, but certainly not the only or ultimate way the universe behaves.  Of course I'm deeply impressed by the ultra-soft UV behavior of our favorite extended theories, or even the renormalizable behavior of our miraculous pointlike non-abelian gauge theories.  Does that mean I really believe they hold to all---or even any---scales beyond which they've been observed?  I think it's possible, but I also expect surprises from the universe.

It's absolutely possible to discover startling new structure unifying theories that have been at the heart of modern physics for decades and decades.  I believe as we gather more
theoretical data ---  the *what* --- and we give ourselves the space to play with different compatible stories, we'll find ever more efficient, and ever more meaningful *how's*.  It's this focus on the *what*, allowing a freedom in the *how*, that ended up suggesting the group name I finally decided on.

I've taken this inspiration from a certain paradigm of programming -- a functional one, where the idea is to write algorithms focused on the logic -- the objective --  and not so much the control-flow -- how it gets done.  This is called ["declarative programming"](https://en.wikipedia.org/wiki/Declarative_programming), and so it is in that sense I give you the Paris-Saclay Group for [*Declarative Theoretical Physics*](http://fancyphysics.org).
