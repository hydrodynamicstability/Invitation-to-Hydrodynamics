## An Invitation to Fluid Mechanics for Physicists

"Hydrodynamics and magnetohydrodynamics are fundamental, regardless of popular opinion."  -- [Eugene N. Parker](https://news.uchicago.edu/story/eugene-parker-legendary-figure-solar-science-and-namesake-parker-solar-probe-1927-2022) (1927-2022)\*

&emsp; \*Quoted in the retrospective by Stuart D. Bale, *Science*, 376:  461 (29 Apr 2022).

"That we have written an equation does not remove from the flow of fluids its charm or mystery or its surprise."  - [Richard P. Feynman](http://www.richardfeynman.com/about/bio.html) (1918-1988)\*\*

&emsp; \*\* *The Feynman Lectures in Physics*, vol. 2, ch. 41.  (Addison-Wesley, 1964.)

**Welcome.**  This page aims to outline why a physicist should learn a little bit of fluid mechanics, and how to get started doing so.   -- Christopher Tong, Ph.D. (physics).

### Why should a physicist learn some fluid mechanics?

- To use it in their work:

  - Wide applications *within* physics, including plasma physics, astrophysics & cosmology, condensed and soft matter physics, and hybrid fields such as physical chemistry, biological physics, and environmental science and engineering.
  
  - Crucial subject for the study of geophysics, atmosphere and ocean dynamics, hydrology, and all their counterparts in planetary physics.

  - Applications across engineering and technology, including civil, chemical, biomedical, mechanical, and aerospace engineering, but even occasionally in electrical and nuclear engineering, and materials science and engineering.  Closely allied fields include acoustics and rheology.

- For its own sake:

  - "\[T\]here are so many curious and beautiful natural phenomena, visible every day in the world about us, which a physicist with no knowledge of fluid mechanics is unable to appreciate in full."  -- Thomas E. Faber, *Fluid Dynamics for Physicists* (Cambridge University Press, 1995).

  - "\[A\]t present, fluid mechanics is one of the most actively developing fields of physics, mathematics and engineering, so you may wish to participate in this exciting development."  -- Gregory Falkovich, *Fluid Mechanics:  A Short Course for Physicists* (Cambridge University Press, 2011).

Some additional reasons physics *students* should consider learning some fluid mechanics:

- It's an excellent arena to practice working with vector calculus, partial differential equations, and other mathematical (and indeed, computational) methods.

- Even more important, it is an excellent arena in which to practice using dimensional analysis, scaling arguments, and other tools of physical intuition.

- "\[M\]ost other subjects in the physics curriculum are almost exclusively concerned with *linear* processes, whereas fluid dynamics leads one into the *non-linear* domain."  -- Thomas E. Faber, *Fluid Dynamics for Physicists* (Cambridge University Press, 1995).

- As James S. Trefil has argued, many physicists end up pursuing careers in fields beyond conventional physics research, and should be educated as generalists.  "This point was brought home to me most forcefully when I became involved in some interdisciplinary research projects in medicine, and discovered to my chagrin that I did not possess the background necessary to make meaningful contributions in many areas of the research."  -- James S. Trefil, *Introduction to the Physics of Fluids and Solids* (Pergamon, 1975; reprinted by Dover, 2010).

### Intrigued, but not yet ready to commit?

Here's a few sampler dishes to see if you like it.  Effort increases as you work your way down the list.

- Watch this 46-minute video lecture, [Why Hydrodynamics?](https://podcasts.ox.ac.uk/why-hydrodynamics) by Prof. Steve Simon, a condensed matter theorist at Oxford University.  It's a nontechnical talk aimed at fellow physicists.  
 
- Read the fluid mechanics chapters (vol. 2, ch. 40-41) of the [Feynman Lectures on Physics](https://www.feynmanlectures.caltech.edu/), to find out what Richard Feynman wanted every physics undergraduate to know about fluid mechanics.  This is about 24 pages of material.

- Read the first chapter of T. E. Faber's *Fluid Dynamics for Physicists* (Cambridge University Press, 1995).  Several writers have praised the first chapter, "A bird's eye view", as an overview of hydrodynamic problem solving, using the example of ejecting liquid from a syringe.  This is 36 pages of material.

- Read geophysicist Grae Worster's little book, *Understanding Fluid Flow* (AIMS Library Series, Cambridge University Press, 2009).  In 100 pages you will gain a quick overview of some of the prominent ideas of the subject.

### Some introductory thoughts

Fluid mechanics consists of the statics and dynamics of fluids (hydrostatics and hydrodynamics, respectively), classically including liquids, gases, and plasmas, under conditions when these materials deform continuously in response to shear stress.  The same macroscopic laws of fluid mechanics are operative despite fundamentally different microscopic physics governing these states of matter, perhaps a clue that fluid mechanics is an emergent phenomenon.  These macroscopic laws were developed primarily in the 18th and 19th centuries, well before the general acceptance of the atomic hypothesis was achieved, and have scarcely needed revision since then.  Nonetheless, a number of *fundamental* problems involving fluid dynamics remains unsolved, and there is a wide range of applications throughout science, engineering, and medicine.

In classical mechanics, we typically study point particles, systems thereof, and rigid bodies.  However, an oft-neglected feature of mechanics in today's physics curriculum is *continuum mechanics*, the statics and dynamics of deformable solids and fluids, as well as materials with more complex rheology.  The classical theory of continua makes use of both the continuum hypothesis (ignoring the discrete molecular structure of matter) and the assumption of local thermodynamic equilibrium.  In fluid dynamics, the bulk transport of mass, momentum, and heat are nonequilibrium phenomena, but we posit the existence of scalar, vector, and tensor fields where mechanical variables (like velocity and stress) and thermodynamic variables (like density, pressure, and temperature) can be *locally* well defined, even as they vary globally in space and time.  In kinetic theories of gases, however, it is possible to derive the classical equations of hydrodynamics as approximations to the Boltzmann transport equation for, e.g., dilute monatomic gases with conservative binary collisions.  The approximation is often based on decomposing the number density distribution function in state space as the sum of a Maxwell-Boltzmann distribution and a small deviation, and expanding the collision integral to first order in that deviation.  Thus while hydrodynamics is usually considered a branch of mechanics, it has intimate connections with statistical mechanics and nonequilibrium thermodynamics.

Fluid dynamics is often divided into incompressible and compressible flows (the latter is sometimes termed "gas dynamics").  The transmission of sound waves in fluids is a link between compressible hydrodynamics and acoustics, another neglected topic of classical physics in the contemporary curriculum.   Less neglected is *magnetohydrodynamics*, the extension of hydroynamics to electrically conducting fluids in the presence of magnetic fields, an often useful approximation in plasma physics, astrophysics, and cosmology (where relativistic fluid dynamics may also be considered).  Meanwhile quantum fluids and superfluidity (liquid helium-3's and -4's superfulid states being iconic examples) have been the source of multiple Nobel Prizes in Physics.  Computational fluid dynamics (CFD) is one of the oldest domains of computational physics, and the arena of much applied research.

Fluid dynamics is of increasing interest in condensed and soft matter physics, biological and medical physics, and environmental physics.  The subject has historically even deeper connections to applied mathematics, physical chemistry, all the geophysical, atmospheric, oceanic, and planetary sciences, and to civil, mechanical, aerospace, chemical, and biomedical engineering, among others.  In fact it could be argued that civil engineers were the first hydrodynamicists, since all ancient civilizations were founded on river banks, and they collectively needed to solve the problems of irrigation, drainage, and flood control.  By that argument, the study of fluid flow is as old as human civilization itself.


### Forthcoming essays

- Fluid mechanics in the physics curriculum.
- Continnum mechanics in the great physics courses.
- Continuum mechanics books written by physicists.
- Fluid mechanics and the history of physics.
- Additional resources


#### Disclaimers

The content on this site was developed solely on my personal time.  The views expressed are solely my own, and do not necessarily represent the views, policies, or opinions of my employer or any organization with which I am affiliated.

(c) 2022 by Christopher Tong
