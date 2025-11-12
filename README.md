# Slides for my invited talk at the Institute of Solid State Physics (IFP) $-$ TU Wien
[![Netlify Status](https://api.netlify.com/api/v1/badges/8ddadb84-e2ef-49fb-a703-881a4f67ccc7/deploy-status)](https://app.netlify.com/projects/tuw-ifp-2025/deploys)

You can view the slides hosted at [netlify](https://fismat2025bellomia.netlify.app/#/1), or...

To start the slide show locally:

- `pnpm install`
- `pnpm dev`
- visit <http://localhost:3030>

Edit the [slides.md](./slides.md) to see the changes.

Learn more about Slidev at the [documentation](https://sli.dev/).

## Abstract

The strongly correlated materials community approaches the third quantum revolution under a two‐fold, bold assumption: strong inter-particle correlations are expected to grant richer quantum resources than what can be found in other platforms and these resources are presumed to be operationally accessible for next-generation technologies. We are thus compelled to faithfully assess these aspects, with appropriate measures of entanglement and correlations.

After a brief review of the intricate and highly incomplete theory of quantitative measures of entanglement between indistinguishable fermions, to which we have recently started to contribute [1], I will show how one can single out the inherent properties of strongly-correlated electrons even in the —much more developed— framework of orbital/mode entanglement. To this end, I will introduce the concept of symmetry resolved entanglement, which allows us to decompose the bipartite entanglement between two fermionic orbitals in three terms, labelled by orbital charge imbalance: the zero-imbalance contribution is associated to RVB singlets and so describes the entanglement associated to antiferromagnetic correlations; the 1-imbalance entanglement accounts for the trivial correlations induced by single-electron hopping processes, which are generally large even in noninteracting systems; finally, the 2-imbalance term describes the entanglement between an empty (holon) and a fully occupied (doublon) electronic orbital, intimately connected to the competition between kinetic energy and Coulomb repulsion.

Considering the simple, analytically known, ground state of an isolated Hubbard dimer I will compare different measures of full and symmetry resolved entanglement between the two sites. I will also draw a direct connection between the antiferromagnetic and holon-doublon contributions and the charge and parity superselection rules. These mathematical constraints to the fermionic orbital entanglement have been repeatedly shown to faithfully identify the portion of correlations that can be harnessed in realistic quantum information protocols. Furthermore, the superselected entanglement is determined by a significantly smaller subset of reduced density matrix elements, foreshadowing an easier bridge to experimental investigations.

Finally, I will present cluster dynamical mean-field theory (CDMFT) results for salient landmarks in the phase diagram of the two-dimensional Hubbard model at zero temperature, relevant to the physics of unconventional superconductivity in copper oxides. The symmetry resolution of our entanglement measures allows for a clear identification of Mottness, both in the half-filled insulator and in the bad metal found at small hole-doping fractions: in striking contrast with the phenomenology of the Hubbard dimer, a significant holon-doublon entanglement is manifested only in the intermediate coupling regime, where the competition between U and t drives the transition. Antiferromagnetic spin singlets instead dominate the entanglement content of both the Mott insulator and the under-doped metal, at large U. Remarkably, all contributions to the superselected two-site entanglement are suppressed by several orders of magnitude in the Fermi liquid regime found at weak interaction strengths and/or large doping fractions [2,3], whereas the hopping entanglement remains large [4]. This highlights the strong connection between superselection rules and the inherent quantum resources brought by inter-particle interactions. Our findings provide a formal validation to the early proposals of an RVB mechanism for unconventional superconductivity, while also capturing explicitly the role of nonlocal holon-doublon binding in driving the Mott transition—an aspect traditionally considered beyond the reach of CDMFT approaches [5].

[1] G. Bellomia, A. Amaricci and M. Capone, arXiv:2506.18709 (2025)    
[2] G. Bellomia, C. Mejuto-Zaera, M. Capone and A. Amaricci, Phys. Rev. B 109, 115104 (2024)    
[3] G. Bellomia, PhD Thesis, SISSA (2024)   
[4] G. Bellomia, C. Mejuto-Zaera, M. Capone and A. Amaricci, in preparation   
[5] See e.g. M. Capello, F. Becca, M. Fabrizio, S. Sorella, E. Tosatti, Phys. Rev. Lett. 94, 026406 (2005)

