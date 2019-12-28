---
layout: post
title: Magnetic resonance imaging of single atoms on a surface
snippet: A paper review on an important feat in imaging
tags: physics, papers
---

## Aim

To demonstrate the MRI of individual atoms on a surface to subangstrom
spatial resolution.

## Apparatus

Cryogenic scanning tunneling microscope, Electron spin resonance,
Magnetic tip, RF oscillator, Ti$_\text{O}$ atom samples, MnO$_2$ surface

## Introduction

A clear image of Strontium was captured in 2018 by a group of students
from Oxford \[2\]. The primary idea is to design the magnetic field
gradient to locally tune the resonant frequency of spin ensembles for
capturing using MRI. Though low temperature STM has subnanometre spatial
resolution, their energy resolution is limited in tunneling spectroscopy
experiments due to thermal broadening. In this paper, a new method was
proposed to image the magnetic field to subangstrom resolution.

## Setup

Single adatoms are adsorbed on $MnO_2$ surface. Fe atoms form the spin
cluster on tip apex of STM. A magnetic field gradient of
$\SI{0.3}{\tesla}{\angstrom}^{-1}$ is formed over the sample which is
four to five orders of magnitude larger than in other scanning field
gradient experiments. This is a consequence of the close proximity
between the magnetic tip and the surface atom.

## Principle

Single adatoms adsorbed on a surface are electrically probed using an
STM tip above the atom. The Tunnel-current-assisted ESR is performed by
applying an RF frequency which induces spin transitions between the
ground and excited states due to Zeeman effect. At the resonant
frequency, when $f$ of RF Voltage $V_{RF} \approx f_0$, the frequency of
the atom, a peak in tunnel current is observed. The proximity of
magnetic STM tip also exerts a force due to the field $B_{tip}$, to the
adatoms, which further shifts the Zeeman splitting levels. This is a
local phenomena and such spatial variations in resonant frequency can be
utilized to acquire the information of both magnetic field lines and
topographic image simultaneously. Lateral scanning along $x$ and $y$
directions, while keeping a fixed vertical tip-atom distance $z$, the
MRI scan shows a crescent pattern at different $V_{RF}$. The slice
patterns are a function of $z$, vertical tip-sample distance, and $f$ of
$V_{RF}$ which basically control the tunnel current $I$.

Also, it was found that the resonant slices change drastically for
different magnetic tips. Importantly, for any given STM tip, the
resonant slice pattern also changes for different types of atoms on the
surface. The magnetic interactions between the tip and the atom, in
particular magnetic dipolar and exchange interactions help in acheiving
the additional resolution needed.

## Sources of Noise

1.  Thermal noise: Though the sample is cooled to ultra-low tempratures,
    the noise would be present nevertheless.

2.  The tunnel current induces a shot noise.

3.  Pink noise: Since the resonant conditions are typically acheived at
    low frequencies at ultra-cold temperatures, $1/f$ dependence of pink
    noise plays a major role in determining the resolutions of image
    obtained.

## Applications

The potential applications of atomic-scale MRI include imaging
biomolecules with unprecedented resolution, revealing the spin structure
of atoms, molecules and solids, and giving site-dependent control in
quantum simulators and spin networks.

## References

1.  [Willke, P., Yang, K., Bae, Y. et al. Magnetic resonance imaging of
    single atoms on a surface. Nat. Phys. 15, 1005-1010 (2019)](https://www.nature.com/articles/s41567-019-0573-x)

2.  [Photographing a Single Atom](https://klickverbot.at/blog/2018/02/photographing-a-single-atom/)
