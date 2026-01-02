# Massive-free-field-on-dynamical-lattice-
Numerical study of a free massive scalar field coupled to a one-dimensional dynamical lattice, using both **brute-force** enumeration and **importance sampling** techniques.

🌟 Overview

This repository contains the numerical codes in Julia and created as part of my [Master's thesis](https://www.db-thueringen.de/receive/dbt_mods_00067834) to study a background-independent toy model consisting of a free massive scalar field defined on a dynamical, irregular one-dimensional lattice with periodic boundary conditions.

The lattice geometry is encoded in variable edge lengths, which are weighted by a Gaussian distribution. This setup provides a simplified, spin-foam-inspired model of fluctuating geometry that preserves the essential features of matter–geometry coupling while allowing explicit numerical evaluation.

At the core of the analysis is the relational (diffeomorphism-invariant) two-point **correlation function ⟨ϕϕ(R)⟩** defined as a function of the geodesic distance 
**R** measured along the dynamical lattice.

Both implementations evaluate:

*Partition function*

Z=∑{ℓi}1det⁡K(ℓ)
Z={ℓi} ∑ detK(ℓ)

*Geometric expectation values*

Mean edge length ⟨ℓ⟩ and ⟨ℓ²⟩

Mean lattice volume ⟨V⟩ and ⟨V²⟩

Relational two-point correlation function
 ⟨ϕϕ(R)⟩​


binned as a function of the geodesic distance R
