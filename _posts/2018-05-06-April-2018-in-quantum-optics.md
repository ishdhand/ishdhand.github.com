---
layout: post
title: "April 2018 in Quantum Optics"
date: 2018-05-14
comments: true
---
Following up from [the March post]({{ site.baseurl }}{% post_url 2018-04-17-March-2018-in-quantum-optics %}), April 2018 in quantum optics was just as exciting: from integrated photonics for random number generation and for continuous variable quantum information, to new witnesses of multi-photon indistinguishability and of entanglement, and the release of an open-source photonics front-end/simulator. Here are my reading notes.

<!--more-->

- Bose, S. & Sanjay Kumar, M. [arXiv:1804.00190](https://arxiv.org/abs/1804.00190). _Quantum Teleportation with a Class of Non-Gaussian Entangled Resources_.

  > Two-mode quadrature squeezing is probably necessary for quantum teleportation. This work brings us closer to identifying the resource states for continuous variable quantum teleportation, i.e., what attributes are necessary and sufficient for a, generally non-Gaussian, continuous variable state to be useful for quantum teleportation. Two reasonable candidates have been rejected earlier:  EPR correlations are neither necessary nor sufficient and squeezed vacuum affinity is not necessary. This work tests two-mode quadrature squeezing as a necessary condition and provides numerical evidence that two representative classes of non-Gaussian states (de-Gaussified two-mode squeezed vacuum state and beam-splitter generated non-Gaussian states) require two-mode squeezing as a necessary condition for quantum teleportation. Section V provides a proof that for the specific case of quantum teleportation using symmetric Gaussian states, the two-mode quadrature squeezing is a necessary condition.

- Lee, J. P., Wells, L. M., Villa, B., Kalliakos, S., Stevenson, R. M., Ellis, D. J. P., Farrer, I., Ritchie, D. A., Bennett, A. J., & Shields, A. J. [arXiv:1804.00713](https://arxiv.org/abs/1804.00713). _Controllable photonic time-bin qubits from a quantum dot_.

  > Arbitrary deterministic time-bin photonic qubits from quantum dots. Quantum dots can use Raman scattering to generate near-deterministic time-bin photonic qubits as shown [earlier](https://iopscience.iop.org/article/10.1088/2058-9565/aaa7b7/meta) but without full control over the relative phase of the outgoing time bins. This work demonstrates control of the relative phase without resorting to lossy phase modulation on the outgoing light. Instead, control of the phase difference between the outgoing time bins is achieved by modulating the relative phase of the driving pulses. Coupled with the control of the relative amplitude (obtained by modulating the power of the driving pulses), this phase control means that arbitrary qubit (and maybe qudit?) states of time-bin photons can be generated.

- Brod, D. J., Galvão, E. F., Viggianiello, N., Flamini, F., Spagnolo, N., & Sciarrino, F. [arXiv:1804.01334](https://arxiv.org/abs/1804.01334). _Witnessing genuine multi-photon indistinguishability_.

  > An interferometer to test the presence of genuine n-photon indistinguishability. Theory and experiment to test whether a photonic state contains contributions from n-indistinguishable-photon terms and to bound their amplitudes. The very elegant test is based on a linear interferometer that bunches together indistinguishable photons; the degree of bunching indicates the degree of indistinguishability.

- Killoran, N., Izaac, J., Quesada, N., Bergholm, V., Amy, M., & Weedbrook, C. [arXiv:1804.03159](https://arxiv.org/abs/1804.03159). _Strawberry Fields: A Software Platform for Photonic Quantum Computing_.

  > Open-source photonic quantum computing front-end and simulator. Well tested (201 tests, 96% coverage!) and well [documented](https://strawberryfields.readthedocs.io/en/latest/) photonic quantum computing front end and simulator. I had fun playing around with the example [notebooks](https://github.com/XanaduAI/strawberryfields/tree/master/examples) and look forward to spending more time [grokking](https://en.wikipedia.org/wiki/Grok) the package.


- Schneeloch, J., Tison, C. C., Fanto, M. L., Alsing, P. M., & Howland, G. A. [arXiv:1804.04515](https://arxiv.org/abs/1804.04515). _Quantifying entanglement in a 68-billion dimensional quantum system_.

  > Improved entanglement witness and compressed measurements reveal >7 ebits of entanglement in SPDC output. A [recent entanglement witness](https://arxiv.org/abs/1709.03626) relies on measuring correlations between pairs of complementary observables. This work shows that the entanglement witness also works if the joint distributions are replaced by compressed distributions. This replacement is then exploited to get similar results with far fewer measurements that are chosen using an image compression approach. Another advance is a less tight witness that is quadratically easier to measure. Together, this allows for witnessing 7.1 ( ebits (bell-pair equivalents) of entanglement, all this without resorting to computational recovery black magic.

- Raffaelli, F., Sibson, P., Kennard, J. E., Mahler, D. H., Thompson, M. G., & Matthews, J. C. F. [arXiv:1804.05046](https://arxiv.org/abs/1804.05046). _A SOI Integrated Quantum Random Number Generator Based on Phase fluctuations from a Laser Diode_.

  > Integrated photonics for quantum random number generation. A laser output operating just above the threshold demonstrates random phase fluctuation [because of spontaneous emission](https://www.osapublishing.org/ol/abstract.cfm?uri=ol-35-3-312). This random fluctuating phase is converted into fluctuating light intensity via interferometry. The intensity fluctuations are next converted into voltage fluctuations via a transimpedence amplified and finally digitalized on an oscilloscope into random bits. Integrated optics trades off good quantum-to-classical-noise ratio (~3.4 as compared to [~21 for fiber](https://www.osapublishing.org/oe/abstract.cfm?uri=oe-20-11-12366)) for high stability (>50 minutes) among other advantages.

- Mancino, L., Sbroscia, M., Roccia, E., Gianani, I., Cimini, V., Paternostro, M., & Barbieri, M. (https://arxiv.org/abs/1804.06472). _Realism-information complementarity in photonic weak measurements_.

  > Photonic demonstration of duality between realism and information extraction. For a given initial state, the degree of irreality of an observable is quantified by how much its measurement changes the state. For a weak-measurement setting (i.e., the system interacts with an ancilla, which is later measured), irreality and information extraction [are complementary](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.97.022107). Basically, changes in the irreality of an observable are coupled to changes to the system-ancilla mutual information and the ancilla marginal information content. The weak measurement setting is simulated as the interaction of two photons on a polarization beam splitter (like [so](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.73.012113)) and information content is measured by full state tomography on the output photons.

- Korzh, B. A., Zhao, Q., Frasca, S., Allmaras, J. P., Autry, T. M., Bersin, E. A., Colangelo, M., Crouch, G. M., Dane, A. E., Gerrits, T., Marsili, F., Moody, G., Ramirez, E., Rezac, J. D., Stevens, M. J., Wollman, E. E., Zhu, D., … Berggren, K. K. [arXiv:1804.06839](https://arxiv.org/abs/1804.06839). _Demonstrating sub-3 ps temporal resolution in a superconducting nanowire single-photon detector_.

  > A demonstration of 3ps jitter in nanowire detectors. This work shows a 5x improvement in photodetector time resolution (jitter), which is the distribution width of the lag between photon arrival time and the signal output time. This is achieved by keeping the nanowire short, so there is less fluctuation in the position along the nanowire at which photons arrive and consequently less fluctuation in the time at the which slow (v = 0.02c) RF pulses reach the amplifiers at the ends of the nanowire. Short nanowires also mean high internal efficiency, which too improves the jitter. This improved resolution comes at the cost of low overall efficiency. Changing the photon wavelength or device temperature changes the jitter, which indicates that the jitter is intrinsic to the detector and not resulting from the instrumentation.

- Lenzini, F., Janousek, J., Thearle, O., Villa, M., Haylock, B., Kasture, S., Cui, L., Phan, H.-P., Dao, D. V., Yonezawa, H., Lam, P. K., Huntington, E. H., & Lobino, M. [arXiv:1804.07435](https://arxiv.org/abs/1804.07435). _Integrated photonic platform for quantum information with continuous variables_.

  > Integrated waveguide with two-mode squeezed vacua source and electro-optic phase shifters and beamsplitters. Two-mode squeezed vacua are generated in an on-chip periodically poled waveguide. The on-chip fast electro-optic phase shifters and beamsplitters enable the manipulation of the generated nonclassical light and also the interferometric stage of the homodyne detection. The high operational temperature of the waveguide (125°C) allows for large (up to 160 mW) coupled pump power inside the waveguides. Exciting to see where this goes in the future!

- Combes, J., & Brod, D. J. [arXiv:1804.08531](https://arxiv.org/abs/1804.08531). _Two-photon self-Kerr nonlinearities for quantum computing and quantum optics_.

  > Self-Kerr interaction can be approximated by a sequence of cross-Kerr interactions. Real-world self-Kerr interaction [cannot be used](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.73.062305) to [generate large phases](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.81.043823) at the relevant few-photon level. This work proposes an approximate self-Kerr interaction to circumvent the restriction. The approximation is realized by a mirror at the end of a chain of cross-Kerr interaction sites. Many powerful tools developed here, so I need to re-read this!

- Kwon, H., Tan, K. C., Volkoff, T., & Jeong, H. [arXiv:1804.09355](https://arxiv.org/abs/1804.09355). _Nonclassicality of Light as a Quantifiable Resource for Quantum Metrology_.

  > Nonclassicality of light (i.e., negativity in its P function) is a resource for quantum metrology. Preposition 1 is a strong claim about pure states: a pure quantum state outperforms all classical states in optical or mean metrological power if and only if the state contains negativity in its P function. Theorem 1 tells us that nonclassicality (in the sense of [monotonicity under linear optics operations](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.119.190405)) is a resource for the mean metrological power of the state. This means that metrology is yet another way of looking at the classical non-classical divide for light states.

- Lee, J. P., Villa, B., Bennett, A. J., Stevenson, R. M., Ellis, D. J. P., Farrer, I., Ritchie, D. A., & Shields, A. J. [arXiv:1804.11311](https://arxiv.org/abs/1804.11311). _Towards a source of multi-photon entangled states for linear optical quantum computing_.

  > Scheme for generating entangled photonic states using quantum dots. A modification of the [Lindner and Rudolph cluster-state generation scheme](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.103.113602) from polarization to time-bin encoded photons. The modification also makes the scheme compatible with enhanced Raman scattering, which promises higher indistinguishability. A proof-of-principle demonstration shows that the emitted photons are correlated with the quantum dot.
