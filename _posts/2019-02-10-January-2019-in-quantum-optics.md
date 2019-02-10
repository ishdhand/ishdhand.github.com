---
layout: post
title: January 2019 in Quantum Optics
comments: true
---

Here are notes from the quantum optics preprints that I enjoyed reading in January 2019. For me, the highlights included a recipe for constructing linear optical circuits for a given quantum operation (by [Garcia-Escartin et al.](http://arxiv.org/abs/1901.06178)) and reports of Hong-Ou-Mandel interference from on-chip weak-coherent sources (by [Semenenko et al.](http://arxiv.org/abs/1901.05706) and [Agnesi et al.](http://arxiv.org/abs/1901.05707)). 

<!--more-->

- Magana-Loaiza, O. S., Leon-Montiel, R. de J., Perez-Leija, A., URen, A. B., You, C., Busch, K., Lita, A. E., Nam, S. W., Mirin, R. P., & Gerrits, T. [arXiv:1901.00122](http://arxiv.org/abs/1901.00122). _Multiphoton Quantum-State Engineering using Conditional Measurements_.
    > Generation of photon-subtracted two-mode squeezed vacuum states using postselection. A two-mode squeezed vacuum state can be made more correlated by subtracting the same numbers of photons from both the modes. Surprisingly, the photon statistics of the individual modes approach Poissonian distributions, so the resulting state approaches that of an entangled laser. The photon subtraction requires high-efficiency photon number resolving detectors. This experimental implementation is closely connected to an [earlier proposal](https://www.osapublishing.org/josab/abstract.cfm?uri=josab-29-9-2581) on photon-subtracted two-mode squeezed vacuum states.

- Menssen, A. J., Felce, D., Guan, J., Booth, M. J., & Walmsley, I. A. [arXiv:1901.04439](http://arxiv.org/abs/1901.04439). _A Photonic Majorana Bound State_.
    > Simulation of Majorana fermion binding to vortex defect realized in a photonic graphene analogue. The simulation uses the idea that a wavefunction evolving under a tight-binding Hamiltonian on crystal lattice is analogous to light propagating in a photonic crystal. A photonic crystal with an astounding 1192 waveguides forms the lattice and a spatial-light modulator is used to initialize the desired state.  

- Semenenko, H., Sibson, P., Thompson, M. G., & Erven, C. [arXiv:1901.05706](http://arxiv.org/abs/1901.05706). _Interference between independent photonic integrated devices for quantum key distribution_. and
- Agnesi, C., Da Lio, B., Cozzolino, D., Cardi, L., Bakir, B. Ben, Hassan, K., Della Frera, A., Ruggeri, A., Giudice, A., Vallone, G., Villoresi, P., Tosi, A., Rottwitt, K., Ding, Y., & Bacco, D. [arXiv:1901.05707](http://arxiv.org/abs/1901.05707). _Hong-Ou-Mandel interference between independent III-V on silicon waveguide integrated lasers_.
    > Indium phosphide and Silicon chips for generating indistinguishable weak coherent states. These preprints report two photonic chips with on-chip laser and Mach-Zehnder interferometer for pulse shaping. The resulting coherent states after attenuation are indistinguishable with Hong-Ou-Mandel visibilities at around 46% as compared to the maximum possible 50% values. These results on HOM interference, which is a building block for MDI-QKD, are a step forward from the QKD-enabling [earlier work](https://www.nature.com/articles/ncomms13984) on InP chips.

- Garcia-Escartin, J. C., Gimeno, V., & Moyano-Fernández, J. J. [arXiv:1901.06178](http://arxiv.org/abs/1901.06178). _A method to determine which quantum operations can be realized with linear optics with a constructive implementation recipe_.
    > A recipe for constructing the linear optical device to implement a given quantum operation on n-photon states. This preprint resolves an important open problem (and something that I was curious about for the longest time): given a unitary transformation acting on n photons in m modes, (1) is there a linear optical circuit that exactly implements it? and (2) if yes, then what is the circuit? The answer to the question (1) is: A quantum operation U can be implemented with linear optics if and only if its adjoint is an automorphism (i.e., for any element v in the image subalgebra d , the adjoint UvU† remains in the subalgebra). This can be checked by choosing a basis and checking the consistency of a resulting linear system. The answer to (2) is a constructive recipe of Theorem 2 (Equations 5 and 6) with helpful examples in the appendix. Of course, there might be situations where this algorithm says that the operator cannot be implemented but we could actually implement it using a suitable subset of states.

- Trivedi, R., Fischer, K., Vuckovic, J., & Muller, K. [arXiv:1901.06367](http://arxiv.org/abs/1901.06367). _Generation of non-classical light using semiconductor quantum dots_.
    > Thorough review on generating non-classical light with quantum dots. The review starts from the basics of quantum light and its interaction with matter. From there, it builds up to schemes for generating single photons, pairs of entangled photons and all the way till schemes for generating graph states. Great to see a detailed review on this fast growing topic!

- Chapman, J. C., Graham, T. M., Zeitler, C. K., & Kwiat, P. G. [arXiv:1901.07181](http://arxiv.org/abs/1901.07181). _Time-bin and Polarization Superdense Teleportation for Space Applications_.
    > A blueprint for superdense teleportation with ISS. This preprint proposes using time-bin and polarization together allow for superdense teleportation with a space-based station. It shows that 10^5 distinguishable states can be transmitted with an average fidelity of 94±2% and that states can be reconstructed using the light received from a single pass of the space station.

- Bozkurt, A. B., & Kocaman, S. [arXiv:1901.10369](http://arxiv.org/abs/1901.10369). _Linear Optical Deterministic and Reconfigurable SWAP Gate_.
    > A design of a SWAP/identity reconfigurable gate in dual-rail basis. Figure 2 is a simple setup of a SWAP gate on two dual-rail qubits. The gate uses two mode-swaps (aka waveguide crossings), two MZIs. The gate is deterministic and much simpler than what one would get by laying out three CNOTs in series.
