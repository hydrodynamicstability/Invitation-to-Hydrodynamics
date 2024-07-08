## Continuum mechanics in the great physics courses

Several of the key architects of contemporary theoretical physics have published entire physics courses, ranging from the *Feynman Lectures on Physics*, 
intended for  first and second year undergraduates, to the graduate-level *Course of Theoretical Physics* by Landau & Lifshitz.  In this essay I share some 
thoughts on the  coverage of continuum mechanics in these courses, including also those of Arnold Sommerfeld, Wolfgang Pauli, and Kip Thorne & Roger Blandford.  I end with very brief discussions of the textbooks of Steven Weinberg, and of the Berkeley Physics Course.

Unfortunately, like my list of [books on fluid and continuum mechanics written by physicists](https://github.com/hydrodynamicstability/Invitation-to-Hydrodynamics/blob/main/booksByPhysicists.md), I have restricted discussion here to works available in English and published after the second world war.  Consequently I do not discuss works such as Max Planck's 5-volume *Introduction to Theoretical Physics* (English edition, 1932), of which the second volume covers *The Mechanics of Deformable Bodies*.  (The third and final part of that volume covers fluid mechanics.)

&emsp; -- Christopher Tong, Ph.D. (physics).

### The Feynman Lectures on Physics

Richard P. Feynman's 3-volume set of lectures (1963-1965), intended for first and second year college students, was developed to challenge the "best" students in the 
class, without leaving too many of the others behind.  The result is perhaps less satisfactory as an introductory course, and more so as a source of physical 
intuition and insight from a master theorist, for use by both mature and maturing students of physics.  In volume 2, *Mainly Electromagnetism and Matter*, 
Feynman covers solid mechanics in chapters 38-39, and fluid mechanics in chapters 40-41.  The latter chapters are memorably titled "The Flow of Dry Water" 
and "The Flow of Wet Water", respectively, to indicate their coverage of first inviscid, then viscous flows.  All four of these chapters are only about 
12 pages long each.  Also highly relevant is Section 31-6, in the chapter on tensors, discussing the (Cauchy) stress tensor, though he makes explicit use of 
it only in Ch. 39.  Finally in volume 1, *Mainly Mechanics, Radiation, and Heat*, ch. 47 covers sound and the wave equation.  

The entire series of lectures can be accessed [online](https://www.feynmanlectures.caltech.edu/) at no cost; it includes the audio recordings from which the
written version was prepared.  The recordings are particularly entertaining; for example, you can hear applause when Feynman manages to blow out some candles using a smoke ring generator; the end of the recordings capture some of Feynman's conversations with students.

### Feynman on fluids

"Feynman is famously reported to have worked hard on turbulence in the 1950s but to have gotten nowhere and finally given up."

&emsp; -- Gregory L. Eyink and Katepalli R. Sreenivasan (2006), *Reviews of Modern Physics*, vol. 78, pp. 87--135.

The two chapters on fluids are favorites for many physicists who work in hydrodynamics.  True to his intent for the whole course, he covers topics 
well beyond what most introductory physics courses do, and gives you a flavor of the types of problems studied in more advanced hydrodynamics courses.

The chapter titles, "The Flow of Dry Water" and "The Flow of Wet Water", are a riff on John von Neumann's dismissal of theorists who analyzed inviscid 
flows as those who study "dry water".  In the recorded version of the lecture, but not the written version, Feynman himself called inviscid flow theory 
a "nitwit theory"; however, he later acknowledges that away from the boundary layer and turbulent wake, inviscid theory is a good approximation.
Chapter 40 begins with a brief discussion of hydrostatics, quickly disposing of standard topics involving pressure.  He then turns to incompressible, 
inviscid flow, introducing the field theoretic formulation of mass and momentum balance, deriving the material derivative operator, and introducing the notions of vorticity and circulation.  He presents the theorem that if a fluid begins in an irrotational state, it will always remain so.  Feynman 
then provides two derivations of the Bernoulli equation, one for a streamline, derived from the equation of motion, and the other from conservation of 
energy considerations.  He then explains the Torricelli efflux problem, accounting for the tapering of the stream; he argues that if a re-entrant 
discharge tube is used, the jet tapers to exactly 50% of the cross-sectional area of the opening.  (Here is an example of going a step beyond the typical introductory physics course.)
Feynman then discourses on the Venturi effect, circulation, irrotational flow, and angular momentum, including an analogy with magnetostatics.  He moves on to the Helmholtz vortex theorems, giving each a physical interpretation.  He ends with a famous smoke ring demonstration, and its explanation 
using vortex lines.  (For those who know of Feynman's work on superfluid circulation quantization, his interest in vortex lines should be no surprise.)

Chapter 41 begins with the definition of viscosity; the remainder, Feynman admits, is for "entertainment" purposes.  He begins by introducing the 
no-slip condition, then Couette-Taylor flow.  Feynman then presents the constitutive equation for Newtonian fluids, with two viscosity coefficients, 
then derives the Navier-Stokes equations (not named in the text, though in the recording they are named), and its vorticity form, to build 
intuition about vorticity diffusion.  Feynman then discusses dynamic similarity, the Reynolds number, and the Mach number.  He turns next to the drag 
coefficient for flow past a circular cylinder, showing an empirical curve for how it varies with Reynolds number.  Feynman discusses the transition 
from laminar to steady flow, then to periodic flow (Benard-Karman vortex shedding), boundary layer separation, and finally a turbulent wake.  He 
briefly discusses the zero viscosity limit, then returns to Couette-Taylor flow to discuss the regime changes in that problem.  Feynman ends with 
some big-picture discussion of how simple equations can generate complex behavior.

In his comments at the 2022 [*Boulder School for Condensed Matter and Materials Physics*](https://boulderschool.yale.edu/2022/boulder-school-2022), Royce Zia reminds us that [Feynman's blackboard](https://doi.org/10.1063/1.2810904), at the time of his death, had a list of topics "to learn", including "Non linear classical hydro\[dynamics\]".

### Landau and Lifshitz

Lev D. Landau and Evgenii M. Lifshitz's 10-volume *Course of Theoretical Physics* is on the opposite end of the *Feynman Lectures*, best used by graduate 
students.  They too are a hallmark of the physics literature.  Landau was directly involved in the first 8 volumes, while vols. 9-10 were coauthored 
with Lev Pitaevskii.  Landau began developing the material in the 1930s and, working with Lifshitz, completed most of the work by the time of the 1962 
accident that curtailed his career in theoretical physics.  English translations appeared in 1951-1960, with later editions appearing throughout the 
1960s, '70s, and '80s.

Landau and Lifshitz have dedicated entire volumes to both *Fluid Mechanics* (vol. 6) and the *Theory of Elasticity* (vol. 7), which originated as a 
single book on continuum mechanics in the original 1944 Russian edition.  In addition, volume 8, *Electrodynamics of Continuous Media*, includes a 
chapter on magnetohydrodynamics (ch. 8). In vol. 10, *Physical Kinetics*, Alfven waves and the kinetic 
theoretic formulation of the Navier-Stokes equations are discussed.  Volume 9, *Statistical Physics, Part 2, Theory of the Condensed State*, discusses the 
microscopic theory of superfluidity (Ch. 3) as well as hydrodynamic fluctuations (Ch. 9).  The macroscopic theory of superfluidity is discussed 
in Ch. 16 of *Fluid Mechanics*.

### Landau and Lifshitz on fluids

The *Fluid Mechanics* volume is a favorite among physicists who work in this field.  In the preface to the second English edition, Lifshitz writes:

> This book has a special place among those I had occasion to write jointly with L. D. Landau.  He gave it a part of his soul.  That branch of 
theoretical physics, new to him at the time, caught his fancy, and in a very typical way he set about thinking through it *ab initio* and deriving 
its basic results.   This led to a number of original papers which appeared in various journals, but several of his contributions or ideas were not 
published elsewhere than in the book, and in some instances even his priority was not established till later.

Further comments on Landau/Lifshitz' *Fluid Mechanics* are forthcoming.

### Arnold Sommerfeld

"You see, one of the nice things about Sommerfeld was that he was keenly interested in Hydrodynamics and the problem of turbulence, which was not solved. I don't think it's ever been solved..."

&emsp; -- Paul Peter Ewald (1888-1985), [oral history interview](https://www.aip.org/history-programs/niels-bohr-library/oral-histories/4596-1) by Charles Wiener, 1968.


Arnold Sommerfeld's 6-volume *Lectures on Theoretical Physics* (English translations published 1949-1956) are long out of print, though now available 
electronically from Elsevier, and perhaps of mainly historical interest at this juncture.  These lectures, Sommerfeld said in 1949, "were confined essentially to classical physics, which, as a basis for all modern developments, must never be curtailed" (*Am. J. Phys.*, 17:  315-316).  He added, "I used to organize my own lectures in such a way that they were too easy for advanced students and too difficult for beginners."

Volume 2 is on the *Mechanics of Deformable Bodies*, covering both solid and fluid mechanics.  Sommerfeld passed away during the preparation of volume 5, *Thermodynamics and Statistical Mechanics*; thus the final chapter (ch. 5), which includes a development of the hydrodynamic balance equations from kinetic theory (Sec. 43), was prepared by the editors, F. Bopp and J. Meixner.

Further comments on Sommerfeld's *Mechanics of Deformable Bodies* are forthcoming.

### Wolfgang Pauli

Wolfgang Pauli's 6-volume *Lectures on Physics* (1971) includes only two topics on fluids, both in volume 3, *Thermodynamics and Statistical Physics*. 
First there is a discussion of the hydrostatic equilibrium condition for a chemical reaction in equilibrium (Ch. 3).   Later in the same volume, in the chapter on the kinetic theory of gases (Ch. 5), Pauli derives a hydrodynamic momentum balance equation, in fairly general form, for an ideal gas.  It should be noted that Pauli's course does not include a volume on classical mechanics, let alone continuum mechanics.

### Modern Classical Physics, by Thorne and Blandford

"Long, long ago, when we (the authors) were students, some basic understanding of continuous media--fluids and elastic solids--was expected of us, and there were physics courses in which we could learn it.  That is no longer true, but we believe it should be, and this book is designed to facilitate such courses."

&emsp; -- Kip S. Thorne and Roger D. Blandford, *Elasticity & Fluid Dynamics*, preface.

A new contender on the scene is *Modern Classical Physics:  Optics, Fluids, Plasmas, Elasticity, Relativity, and Statistical Physics*, by Kip S. Thorne and 
Roger D. Blandford.  This course is intended for first-year graduate students, requiring as pre-requisites independent coverage of classical mechanics, 
thermodynamics, and electromagnetism.  Originally published in 2017 as a single massive volume, in 2021 a (very slighlty revised) version was issued where topics are split 
up into 5 volumes.  Volume 3 covers *Elasticity & Fluid Dynamics*.  (However, the chapter on magnetohydrodynamics was not included; instead it appears in Volume 4 on *Plasma Physics*.)  The chapters included in this volume make reference to earlier ones (relativity and statistical 
physics) and future ones (plasma physics).

Though I enjoyed reading the fluid dynamics chapters in general, a few points of contention could be made.  Their treatment of Stokes' creeping flow problem (Sec. 14.3.2) seems particularly baroque.  Their unusual approach is meant, as they write, to make contact with "some general ideas that ought to be familiar from other areas of physics."  They later concede (Exercise 14.20) that a more conventional approach using a streamfunction "is more straightforward but less intuitive" than their exposition.  

Another (more tongue-in-cheek) disagreement is detailed on a [companion page](DbyDt.md).  Meanwhile in the elasticity chapters, Prof. James Hanna has [observed](https://arxiv.org/abs/2303.12729) that Fig. 11.10 (on elastica) is incorrect, or at least highly distorted, though this is not noted in the book's errata list.

Further comments on *Modern Classical Physics* are forthcoming.

### Steven Weinberg

Of the architects of contemporary physics since Landau, perhaps Steven Weinberg is the closest to having attempted to write a series of textbooks spanning multiple subdisciplines.  While these books (the 3-volume *Quantum Theory of Fields*, *Cosmology*, *Lectures on Quantum Mechanics*, *Lectures on Astrophysics*, and *Foundations of Modern Physics*) do not formally constitute a "course" in physics, few other of our field's titans have taken as much time to write so much for students.  As far as I know, hydrodynamics makes an appearance in three of these seven works:  *Cosmology*, *Lectures on Astrophysics*, and *Foundations of Modern Physics*.  Coverage in the first two of these is rather specialized, so here I focus on the third, published just days before his death, and the only one of his texts intended for undergraduates.   A short discussion of fluid dynamics appears (Sec. 2.5) in the chapter on thermodynamics and kinetic theory.  Unlike most presentations in statistical physics texts, which are based on the kinetic theory of gases, Weinberg actually gives a continuum derivation of the Navier-Stokes equations, but not a conventional one.  HIs account uses a style of reasoning that "has become common in the quantum theory of fields, leading to what are known as effective-field theories".  No physicist interested in fluid dynamics should miss it.  

### What about the Berkeley Physics Course?

As far as I can tell, this famous 5-volume course lacks a systematic presentation of continuum mechanics.  For example, I could not find any reference to fluid or solid mechanics in the second edition of *Mechanics* by Kittel, Knight, and Ruderman (1973).  Rather, fluid topics are scattered in at least three of the five volumes.  Thus the Berkeley course does more than Pauli, but less than the other courses discussed here, as far as hydrodynamics goes.

Edward M. Purcell (Nobel in Physics, 1952) was famously interested in low Reynolds number hydrodynamics in biology, but the second edition of his *Electricity and Magnetism* (1985) mentions magnetohydrodynamics only in passing, at the end of a discussion of the change in magnetic field at a current sheet (Sec. 6.6).  Frederick Reif's *Statistical Physics* (1967) discusses fluids in the final chapter (8), defining viscosity and providing a rough approximate calculation of what it should be for a dilute gas of identical-mass and identical-speed molecules, in terms of the mean free path and molecular speed.  He provides a similar calculation for the thermal conductivity of a dilute gas.  The problems at the end of the chapter discuss a few more hydrodynamic topics (Millikan's oil drop experiment, a rotating cylinder viscometer, and Poiseuille flow).  (Reif had done research on superfluid helium, among other topics.)

Frank S. Crawford's *Waves* (1968) depicts ocean waves on its cover.  Crawford was interested in acoustics, and his book discusses Newton's incorrect derivation of the speed of sound, and its modern correction (Sec. 4.2, example 2) and a few other acoustic topics (Sec. 4.4, example 10; Sec. 5.3, example 3).  In addition he discusses surface waves on water (Sec. 6.2, example 5; Sec. 7.3) including deep water and shallow water waves.  In his 2001 comparative review of textbooks for a vibration and waves course, Lyle Roelofs wrote of Crawford:

> In my opinion this is the book that displays the deepest physical insight and has the most interesting applications. It includes a large number of fascinating home experiments. Physical reasoning is favored over mathematical, to the extent that complex numbers are not even mentioned. Although this book cannot be selected for use in a course, all instructors should avail themselves of a copy to enrich their teaching.

(Source:  Roelofs, *American Journal of Physics*, 69:  922-926.)

[Return to main page](https://hydrodynamicstability.github.io/Invitation-to-Hydrodynamics/)

#### Disclaimers

The content on this site was developed solely on my personal time. The views expressed are solely my own, and do not necessarily represent the views, policies, or opinions of my employer or any organization with which I am affiliated.

(c) 2022-2024 by Christopher Tong.  
