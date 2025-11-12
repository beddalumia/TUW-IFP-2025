---
colorSchema: light
color: rose
layout: cover
routerMode: hash
title: TU Wien - IFP (2025)
theme: neversink
neversink_slug: "TU Wien - IFP"
---

# Symmetry resolved `entanglement` in the _2d_ Hubbard model

**GABRIELE BELLOMIA**    
Post-Doc fellow at SISSA --- _Capone's group_    
Moving soon to TU Wien --- _Held's group_

<br />
    
<img src=/images/sissalight.svg width=110 class="float-right mr-10 mb-5">

:: note ::  
**Institute Seminar** --- November 12<sup>th</sup>, TU Wien --- _Institut für Festkörperphysik_

<!-- 
### Abstract

The strongly correlated materials community approaches the third quantum revolution under a two‐fold, bold assumption: strong inter-particle correlations are expected to grant richer quantum resources than what can be found in other platforms and these resources are presumed to be operationally accessible for next-generation technologies. We are thus compelled to faithfully assess these aspects, with appropriate measures of entanglement and correlations.

After a brief review of the intricate and highly incomplete theory of quantitative measures of entanglement between indistinguishable fermions, to which we have recently started to contribute [1], I will show how one can single out the inherent properties of strongly-correlated electrons even in the —much more developed— framework of orbital/mode entanglement. To this end, I will introduce the concept of symmetry resolved entanglement, which allows us to decompose the bipartite entanglement between two fermionic orbitals in three terms, labelled by orbital charge imbalance: the zero-imbalance contribution is associated to RVB singlets and so describes the entanglement associated to antiferromagnetic correlations; the 1-imbalance entanglement accounts for the trivial correlations induced by single-electron hopping processes, which are generally large even in noninteracting systems; finally, the 2-imbalance term describes the entanglement between an empty (holon) and a fully occupied (doublon) electronic orbital, intimately connected to the competition between kinetic energy and Coulomb repulsion.

Considering the simple, analytically known, ground state of an isolated Hubbard dimer I will compare different measures of full and symmetry resolved entanglement between the two sites. I will also draw a direct connection between the antiferromagnetic and holon-doublon contributions and the charge and parity superselection rules. These mathematical constraints to the fermionic orbital entanglement have been repeatedly shown to faithfully identify the portion of correlations that can be harnessed in realistic quantum information protocols. Furthermore, the superselected entanglement is determined by a significantly smaller subset of reduced density matrix elements, foreshadowing an easier bridge to experimental investigations.

Finally, I will present cluster dynamical mean-field theory (CDMFT) results for salient landmarks in the phase diagram of the two-dimensional Hubbard model at zero temperature, relevant to the physics of unconventional superconductivity in copper oxides. The symmetry resolution of our entanglement measures allows for a clear identification of Mottness, both in the half-filled insulator and in the bad metal found at small hole-doping fractions: in striking contrast with the phenomenology of the Hubbard dimer, a significant holon-doublon entanglement is manifested only in the intermediate coupling regime, where the competition between U and t drives the transition. Antiferromagnetic spin singlets instead dominate the entanglement content of both the Mott insulator and the under-doped metal, at large U. Remarkably, all contributions to the superselected two-site entanglement are suppressed by several orders of magnitude in the Fermi liquid regime found at weak interaction strengths and/or large doping fractions [2,3], whereas the hopping entanglement remains large [4]. This highlights the strong connection between superselection rules and the inherent quantum resources brought by inter-particle interactions. Our findings provide a formal validation to the early proposals of an RVB mechanism for unconventional superconductivity, while also capturing explicitly the role of nonlocal holon-doublon binding in driving the Mott transition—an aspect traditionally considered beyond the reach of CDMFT approaches [5].

[1] G. Bellomia, A. Amaricci and M. Capone, arXiv:2506.18709 (2025)
[2] G. Bellomia, C. Mejuto-Zaera, M. Capone and A. Amaricci, Phys. Rev. B 109, 115104 (2024)
[3] G. Bellomia, PhD Thesis, SISSA (2024)
[4] G. Bellomia, C. Mejuto-Zaera, M. Capone and A. Amaricci, in preparation
[5] See e.g. M. Capello, F. Becca, M. Fabrizio, S. Sorella, E. Tosatti, Phys. Rev. Lett. 94, 026406 (2005) -->


---
layout: image-right
image: /images/armitage_quanta.jpg
neversink_slug: Kristina Armitage for Quanta Magazine
---


# Why entanglement?

Many-body entanglement has proven to

<v-clicks at="+1">

- be a central tool in statistical physics
- mark states of high quantum complexity

  
</v-clicks>

<v-clicks>

It is also expected to be a **resource for quantum technologies**, provided that

</v-clicks>

<v-clicks at="+1">

- it is operationally accessible
- it goes beyond (easy) classical simulation

  
</v-clicks>

---
layout: default
---

# Why symmetry resolved?

<br />

<div class="neversink-pink-light-scheme ns-c-bind-scheme"> 
&nbsp; Operationally accessible entanglement: parity superselection rule (P-SSR)
</div>  
  <v-clicks>

  - Fundamental rule of quantum mechanics :   
    -> No superpositions of states with different parity of the electron number<sup>1</sup>   
  - It surely applies to full and reduced states of a fermionic system   
    -> in practice it applies to any _local_ operation<sup>2</sup>
  - Even stronger (physical/formal) arguments for the local P-SSR:   
    -> It is needed by the no-signaling theorem<sup>3</sup>    
    -> It is required for mathematical consistency<sup>4</sup>    
    -> It ensures robustness against _typical_ evolution<sup>5</sup>  

  </v-clicks>


<hr>    


<kbd v-click="1"> <sup>1</sup> Wick _et al._, *The Intrinsic Parity of Elementary Particles*, Physical Review **88**, 101 (1952) </kbd>  
<kbd v-click="2"> <sup>2</sup> Ding _et al._, _Physical entanglement between localized orbitals_, Quantum Sci. and Tech. **9**, 015005 (2023) </kbd>  
<kbd v-click="3"> <sup>3</sup> Friis, _Reasonable fermionic quantum information theories require relativity_, New J. Phys. **18**, 033014 (2016) </kbd>  
<kbd v-click="3"> <sup>4</sup> Szalay _et al._, _Fermionic systems for quantum information people_, J. Phys. A: Math. Theor. **54**, 393001 (2021) </kbd>  
<kbd v-click="3"> <sup>5</sup> Parez _et al._, _The Fate of Entanglement_, arXiv:2402.06677 (2024) [submitted to SciPost Physics]</kbd>


---
layout: default
transition: slide-up
---

# Why symmetry resolved?

<br />

<div class="neversink-pink-light-scheme ns-c-bind-scheme"> 
&nbsp; Operationally accessible entanglement: parity superselection rule (P-SSR)
</div>  

&nbsp; <kbd>[...]</kbd>

<div class="neversink-sky-light-scheme ns-c-bind-scheme"> 
&nbsp; Removing trivial entanglement from charge fluctuations: Charge Super-Selection Rule (N-SSR) 
</div> 

<v-clicks>

- We expect a noninteracting metal to be very entangled in real space   
- But in momentum space it is trivially solved with Slater determinants!   
- At weak coupling it is well approximated by Hartree-Fock theory    

</v-clicks>  

<v-clicks>

&nbsp;&nbsp;&nbsp; -> Such real-space entanglement can be **simulated with a simple classical algorithm**   

&nbsp;&nbsp;&nbsp; -> ==Arguably not relevant for quantum technologies!==

<AdmonitionType type="tip" title="Idea" width="450px" v-drag="[495,432,450,73]">
Removing all charge superpositions, we may uncover nontrivial real-space entanglement (if any!)
</AdmonitionType>

</v-clicks>


---
layout: default
---


<div class="neversink-green-light-scheme ns-c-bind-scheme"> 


# &nbsp; Symmetries of a Hubbard dimer (in a general mixed state) 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_symmetries.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight two-site symmetries  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  <v-clicks>

  - The Hubbard model conserves the charge $N$ (and magnetization $m$)
  - Of course this does not imply a local conservation of $n_i$ and $n_j$
  - So in general we have quantum superpositions (off-diagonals)    
    ==**->** entanglement between $i$ and $j$==
    <div class="flex justify-center my-4">
    <img src="/images/dimer_entangled.svg" width="200" />
    </div>

  </v-clicks></div>

</div>

---


<div class="neversink-green-light-scheme ns-c-bind-scheme"> 

# &nbsp; Symmetries of a Hubbard dimer (in a general mixed state) 

</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_ssr.svg" class="h-full w-auto ml-3.5 " />   
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight single-site symmetries  </kbd></div>

  <div class="grid-item grid-col-span-2 ml-7"> 

  - So in general we have quantum superpositions (off-diagonals)    
    ==**->** entanglement between $i$ and $j$==
    <div class="flex justify-left my-4 ml-17 ">
    <img src="/images/dimer_entangled.svg" width="150" />
    </div>  

  <v-clicks depth=2>

  - But **local** SSRs inhibit all quantum superpositions except:
    - holon-doublon coupling   
      ${\color{#F43F5E}\rho_{_\mathrm{hd}} \!\!=\, \mid \uparrow\downarrow \rangle\langle \bullet\!\mid \otimes \mid\!\bullet \rangle\langle \uparrow\downarrow \mid}$ 
    - antiferro fluctuations  
      ${\color{#81C9FC}\rho_{_{\uparrow\downarrow}} \!\!=\, \mid \uparrow \rangle\langle \downarrow \mid \otimes \mid\downarrow\rangle\langle \uparrow\mid}$ 

  </v-clicks></div>

</div>

---
layout: default
transition: view-transition
---


<div class="neversink-fuchsia-light-scheme ns-c-bind-scheme"> 


# &nbsp; Detecting entanglement via partial transposing 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_pretranspose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Rotated to highlight single-site symmetries  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  Thanks to the _Peres-Horodecki_ criterion we can quantify the entanglement encoded in off-diagonal elements by **partial transposing**

  <v-click>

  $$\rho = \begin{pmatrix} A_{11} & A_{12} & \dots & A_{1n} \\ A_{21} & A_{22} & & \\ \vdots & & \ddots & \\ A_{n1} & & & A_{nn} \end{pmatrix}$$
  &nbsp;&nbsp;&nbsp;&nbsp;where $n = \dim \mathcal{F}_\mathrm{A}$, and $\dim A_{ij} \equiv \dim \mathcal{F}_\mathrm{B}$

  </v-click>

  </div>

</div>

---
layout: default
---


<div class="neversink-fuchsia-light-scheme ns-c-bind-scheme"> 


# &nbsp; Detecting entanglement via partial transposing 
</div>

<div class="grid w-full h-fit grid-cols-4 grid-rows-1 mt-10 mb-auto">

  <div class="grid-item grid-col-span-2 h-91"><img src="/images/cdmft_partial_transpose.svg" class="h-full w-auto ml-3.5" />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <kbd> Partial tranposed on one of the two sites  </kbd></div>
  
  <div class="grid-item grid-col-span-2 ml-7"> 

  Thanks to the _Peres-Horodecki_ criterion we can quantify the entanglement encoded in off-diagonal elements by **partial transposing**

  $$\rho = \begin{pmatrix} A_{11} & A_{12} & \dots & A_{1n} \\ A_{21} & A_{22} & & \\ \vdots & & \ddots & \\ A_{n1} & & & A_{nn} \end{pmatrix}$$
  &nbsp;&nbsp;&nbsp;&nbsp;where $n = \dim \mathcal{F}_\mathrm{A}$, and $\dim A_{ij} \equiv \dim \mathcal{F}_\mathrm{B}$

$$\rho^{\color{#D848EE}T\!_{_{_\mathrm{B}}}} = \begin{pmatrix} A_{11}^{\color{#D848EE}T} & A_{12}^{\color{#D848EE}T} & \dots & A_{1n}^{\color{#D848EE}T} \\ A_{21}^{\color{#D848EE}T} & A_{22}^{\color{#D848EE}T} & & \\ \vdots & & \ddots & \\ A_{n1}^{\color{#D848EE}T} & & & A_{nn}^{\color{#D848EE}T} \end{pmatrix}$$

  </div>

</div>

---
layout: default
---


<div class="neversink-fuchsia-light-scheme ns-c-bind-scheme"> 


# &nbsp; Detecting entanglement via partial transposing 
</div>

<br /><br />

&nbsp; &nbsp; &nbsp;
To account for ==$\mathrm{fermionic}$== anticommutation rules the partial transpose is best written as

<br />

<v-clicks>

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
$\rho^{\color{#D848EE}T\!_{_{_\mathrm{B}}}} = \displaystyle\sum_{\Psi^\mathrm{A}_\lambda}\sum_{\Psi^\mathrm{A}_\nu}\sum_{\Psi^\mathrm{B}_\lambda}\sum_{\Psi^\mathrm{B}_\nu}
    \langle{\Psi^\mathrm{A}_\lambda\Psi_\lambda^\mathrm{B}}|{\rho}|{\Psi^\mathrm{A}_\nu\Psi_\nu^\mathrm{B}} \rangle
    |{\Psi^\mathrm{A}_\lambda}\rangle\langle{\Psi^\mathrm{A}_\nu}| \otimes 
    \Bigl(|{\Psi^\mathrm{B}_\lambda}\rangle\langle{\Psi^\mathrm{B}_\nu}|\Bigr)^{\color{#D848EE}\!\!T}$
<br />

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
$\,\,=\displaystyle\sum_{\Psi^\mathrm{A}_\lambda}\sum_{\Psi^\mathrm{A}_\nu}\sum_{\Psi^\mathrm{B}_\lambda}\sum_{\Psi^\mathrm{B}_\nu}
    \langle{\Psi^\mathrm{A}_\lambda\Psi^\mathrm{B}_{\color{#D848EE}\nu}}|{\rho}|{\Psi^\mathrm{A}_\nu\Psi^\mathrm{B}_{\color{#D848EE}\lambda}}\rangle
    |{\Psi^\mathrm{A}_\lambda}\rangle\langle{\Psi^\mathrm{A}_\nu}| \otimes |{\Psi^\mathrm{B}_\lambda}\rangle\langle{\Psi^\mathrm{B}_\nu}|$ ==$\exp\!\left(i\pi\phi_{\lambda\nu}^\mathrm{AB}\right)$==
<br />    <br />

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
where ==$\small \color{#D8760E} \phi_{\lambda\nu}^\mathrm{AB} = \tfrac{1}{2}{\left(\mathrm{P}(\Psi^\mathrm{B}_\lambda)+\mathrm{P}(\Psi^\mathrm{B}_\nu)\right)} + {\left(\mathrm{P}(\Psi^\mathrm{A}_\lambda)+\mathrm{P}(\Psi^\mathrm{A}_\nu)\right)}\times{\left(\mathrm{P}(\Psi^\mathrm{B}_\lambda)+\mathrm{P}(\Psi^\mathrm{B}_\nu)\right)} + \mathrm{P}(\Psi_\lambda^\mathrm{B})$==    
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
and $\small \mathrm{P}(|n_1, n_2, \dots \rangle) = \biggl(\displaystyle\sum_i n_i \biggr)\!\!\!\!\!\mod 2\,$ is the parity of the given Fock state $|n_1, n_2, \dots \rangle$.

</v-clicks>

<!-- $$
\rho^{\color{#D848EE}T\!_{_{_\mathrm{B}}}}
    = \sum_{\Psi^\mathrm{A}_\lambda}\sum_{\Psi^\mathrm{A}_\nu}\sum_{\Psi^\mathrm{B}_\lambda}\sum_{\Psi^\mathrm{B}_\nu}
    \langle{\Psi^\mathrm{A}_\lambda\Psi_\lambda^\mathrm{B}}|{\rho}|{\Psi^\mathrm{A}_\nu\Psi_\nu^\mathrm{B}} \rangle
    |{\Psi^\mathrm{A}_\lambda}\rangle\langle{\Psi^\mathrm{A}_\nu}| \otimes 
    \Bigl(|{\Psi^\mathrm{B}_\lambda}\rangle\langle{\Psi^\mathrm{B}_\nu}|\Bigr)^{\color{#D848EE}\!\!T} \\
    = \sum_{\Psi^\mathrm{A}_\lambda}\sum_{\Psi^\mathrm{A}_\nu}\sum_{\Psi^\mathrm{B}_\lambda}\sum_{\Psi^\mathrm{B}_\nu}
    \langle{\Psi^\mathrm{A}_\lambda\Psi^\mathrm{B}_{\color{#D848EE}\nu}}|{\rho}|{\Psi^\mathrm{A}_\nu\Psi^\mathrm{B}_{\color{#D848EE}\lambda}}\rangle
    |{\Psi^\mathrm{A}_\lambda}\rangle\langle{\Psi^\mathrm{A}_\nu}| \otimes |{\Psi^\mathrm{B}_\lambda}\rangle\langle{\Psi^\mathrm{B}_\nu}|  \colorbox{#FDE589}{\color{#D8760E}$\exp{i\pi\phi_{nm}^\mathrm{AB}}$}
$$ -->

---
layout: section
color: rose
title: Results
---

# Results from Cluster-DMFT


Across both the `interaction-driven` and `density-driven` Mott transitions

---
layout: full
color: white
title: CDMFT
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Cluster Dynamical Mean-Field Theory at zero temperature

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-2 mt-20 mb-auto">
<div v-click=1 class="grid-item grid-col-span-1"><img src="/images/cdmft.svg" /></div>
<div v-click=2 class="grid-item grid-col-span-1"><img src="/images/cdmft_bath.svg" /></div>
<div v-click=3 class="grid-item grid-col-span-1"><img src="/images/cdmft_ed.svg" /></div>

<div v-click=1 class="grid-item grid-col-span-1 text-center h-fit m-3">   
<hr/>

We tile the lattice in real space

</div> 

<div v-click=2 class="grid-item grid-col-span-1 text-center h-fit m-3">   
<hr/>

Then map to an impurity model

</div>

<div v-click=3 class="grid-item grid-col-span-1 text-center h-fit m-3">   
<hr/>

&nbsp; Finally we discretize the bath

</div>

</div>


---
layout: full
title: MIT
transition: slide-left
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Interaction-driven paramagnetic MIT

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 mb-3"><img src="/images/half_sym.svg" width=700/></div>
<div class="grid-item grid-col-span-1 text-center">
<v-click at=0>

<img src="/images/4x2_ladder.svg" class="w-50 ml-15 mt-0.5" />
<img src="/images/shells_inkscaped.svg" class="w-150 ml-3 mt-5 mb-5" />

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <kbd> G.Bellomia _et al._, PRB **109**, 115104 </kbd>

</v-click>
</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Symmetry-resolved versus full entanglement between sites $\langle i j \rangle$

</div>
</div>



---
layout: full
title: Doping
transition: slide-up
---

<div class="neversink-rose-scheme ns-c-bind-scheme"> 

# &nbsp; Doping-driven delocalization

</div>

<div class="grid w-full h-fit grid-cols-3 grid-rows-1 mt-7 mb-auto">
<div class="grid-item grid-col-span-2 mb-4.5"><img src="/images/doped_sym.svg" width=700/></div>
<div class="grid-item grid-col-span-1 ml-15">
<v-clicks at=0>

  - We dope the Mott insulator found at $U/D=2.3$
  - Both $E_{\langle ij \rangle}^\mathrm{hd}$ and $E_{\langle ij \rangle}^{\uparrow\downarrow}$ decrease in the bad metal up to $\delta\simeq0.2$
  - The spin-singlet $E_{\langle ij \rangle}^{\uparrow\downarrow}$ vanishes in the normal Fermi liquid, while there is some residual $E_{\langle ij \rangle}^\mathrm{hd}$...

</v-clicks>
</div>
<div class="grid-item grid-col-span-2 text-center h-fit">

<hr/>

Symmetry-resolved versus full entanglement between sites $\langle i j \rangle$

</div>
</div>

---
layout: full
title: Phase Diagram
color: slate-light
---

<div class="neversink-slate-scheme ns-c-bind-scheme"> 

# &nbsp; $(U\text{-}\mu)$ phase diagram in $E_{\langle ij \rangle}^\mathrm{hd}$ and $E_{\langle ij \rangle}^{\uparrow\downarrow}$

</div>

<div class="grid w-full h-fit grid-cols-2 grid-rows-1 mt-10 mb-auto">
<div class="grid-item grid-col-span-1"><img src="/images/HDphases.svg" class="w-80 ml-15"/></div>
<div class="grid-item grid-col-span-1"><img src="/images/RVBphases.svg" class="w-80 ml-15" /></div>

</div>




---
layout: iframe-right
title: Advertisement
url: 
slide_info: true
transition: view-transition
---

# Experimental measures?

<br/>

<v-click>

  Unfortunately hard to directly access it...

  <br/>  

</v-click>

<v-click>

  We **just announced on arxiv** an indirect witness of nonlocal quantum correlations  

</v-click>

<v-click>

  ==**->** Easily measured in cold-atom lattices== 

</v-click>
  
<v-click>

  ==**->** Directly accessible in local theories== 

  <br/>

</v-click>


---
layout: iframe-right
title: Web-View
url: https://arxiv.org/html/2506.18709v1#abstract
slide_info: false
---

# Experimental measures?

<br/>



  Unfortunately hard to directly access it...

  <br/>  





  We **just announced on arxiv** an indirect witness of nonlocal quantum correlations  





  ==**->** Easily measured in cold-atom lattices== 



  ==**->** Directly accessible in local theories== 

  <br/>



  Please read it, if interested! 🤠
  <QRCode value="https://arxiv.org/abs/2506.18709" :size="100" render-as='svg' class="float-right mr-7 mt-2"/>


---
layout: image
image: /images/Venice.jpg
slide_info: false
---
