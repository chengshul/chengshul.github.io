I am a PhD student of condensed matter theory working in the group of Prof. Marcel Franz.

# Research

I am broadly interested in strongly correlated systems and topological quantum states. 
My research is mainly focused on numerical investigation of low dimensional quantum systems.

## Numerical study of strongly correlated systems
![1](https://raw.githubusercontent.com/chengshul/chengshul.github.io/main/1.png)
For strongly correlated systems in general, analytical approaches are often limited, if not nonexistent. 
Thus numerical methods serve as an important tool, both to support analytical argument and conjectures, and to uncover and inspire new ideas. 
A significant example of the latter is the density matrix renormalization group (DMRG) \[[Schollwock2011](https://doi.org/10.1016/j.aop.2010.09.012)\], which along with other works underscores the entanglement entropy as a relevant parameter in identifying topological order and naturally generalizes to other tensor network constructions. 
Two classes of numerical methods, exact diagonalization (ED) and matrix product state (MPS) based algorithms including DMRG and time-evolving block decimal (TEBD) \[[Paecker2019](https://doi.org/10.1016/j.aop.2019.167998)\], are extensively exploited in my previous works. 
Despite being limited by the exponential growth of the Hilbert space, ED gives precise information and is applicable to systems that numerically converge poorly otherwise. 
Indeed, in Sachdev-Ye-Kitaev (SYK) \[[Sachdev1993](https://doi.org/10.1103/PhysRevLett.70.3339),[Kitaev2015](https://online.kitp.ucsb.edu/online/entangled15/kitaev/),[Maldacena2016](https://doi.org/10.1103/PhysRevD.94.106002)\] like models, the all-to-all nature of the interaction and the highly entangled ground state discourage an MPS ansatz, but enable an excellent approximation of the thermodynamic limit with a moderate system size using ED. 
In \[[Lantagne2018](https://doi.org/10.1103/PhysRevB.97.235124)\], we exploit this advantage and map out a phase diagram of a family of generalized SYK models, by characterizing properties including the spectral function, the level statistics, and the out-of-time-order correlator (OTOC). 
In \[[Li2019](https://doi.org/10.1103/PhysRevB.100.195146)\], supersymmetry (SUSY) is identified from a combination of ED and DMRG calculations.


For (quasi) 1D systems with local interactions, the area law dictates that the entanglement entropy of the ground state grows at most logarithmically with regard to the system size, and therefore the MPS is capable of approximating such states with high precision while using reasonable computation resources. 
Combining DMRG simulations with mean field and conformal field theoretical (CFT) arguments, we construct in \[[Li2020](https://doi.org/10.1103/PhysRevB.102.165123)\] a topological phase in 2D with tricritical Ising modes on its edges. I also implemented an MPS routine that fully incorporates the SU(2) symmetry, thus significantly reducing the computational cost compared to the usual U(1) realization for several ongoing projects.

## Emergent high-energy phenomena in condensed matter physics
![3](https://raw.githubusercontent.com/chengshul/chengshul.github.io/main/3.png)
Recent decades have witnessed a flourishing of high-energy ideas realized in condensed matter systems, from elusive particles like Majorana and Weyl fermions to deep principles including the AdS-CFT duality. One topic of great interest to me is supersymmetry (SUSY).
In the condensed matter literature, there are mainly two approaches that lead to SUSY -- either constructing an explicit SUSY Hamiltonian and asking whether the ground states spontaneously break the symmetry, or looking for ground states in non-SUSY systems that are described by a SUSY field theory. 
We explore the first approach in \[[Li2019](https://doi.org/10.1103/PhysRevB.100.195146)\] in a Majorana model on the kagome lattice, and the second in \[[Li2020](https://doi.org/10.1103/PhysRevB.102.165123)\] as a coupled wire construction of the Grover-Sheng-Vishwanash model \[[Grover2014](https://doi.org/10.1126/science.1248253)\].

## Quantum chaos and dynamics
![2](https://raw.githubusercontent.com/chengshul/chengshul.github.io/main/2.png)
Another topic I have been focused on is quantum chaos. 
While its classical counterpart is formulated with differential equations, quantum dynamics of closed systems is described by unitary evolution, complicating an application of classical chaos ideas to the quantum regime. 
One quantity that has drawn significant research interests recently is the out-of-time-order correlator (OTOC), which is a generalization of the classical idea of "dependence of later time motion on the variance at the initial time". 
From a quantum information point of view, OTOC characterizes how information is scrambled in the quantum system. The time dependence of OTOC further allows a definition of the quantum Lyapunov exponent, the classical counterpart of which plays a fundamental role in chaos theory. 
In \[[Lantagne2018](https://doi.org/10.1103/PhysRevB.97.235124)\], we calculate the OTOC in generalized SYK models and find similar behaviour as the original SYK model. 
In an ongoing project, we focus on the Heisenberg spin chains and calculate the OTOC with the SU(2) invariant TEBD mentioned above. We are able to map out the lightcone structure and extract the Lyapunov exponent for spin up to 5.

# Publications
Also see [Google Scholar](https://scholar.google.ca/citations?user=JAjlLSwAAAAJ&hl=en).  

* "Coupled wire construction of a topological phase with chiral tricritical Ising edge modes", **CL**, Hiromi Ebisu, Sharmistha Sahoo, Yuval Oreg, and Marcel Franz, [Phys. Rev. B **102**, 165123 (2020)](https://doi.org/10.1103/PhysRevB.102.165123), [arXiv:2008.04438](https://arxiv.org/abs/2008.04438).  
* "Supersymmetry in an interacting Majorana model on the kagome lattice", **CL**\*, Étienne Lantagne-Hurtubise\*, and Marcel Franz, [Phys. Rev. B **100**, 195146 (2019)](https://doi.org/10.1103/PhysRevB.100.195146), [arXiv:1811.06104](https://arxiv.org/abs/1811.06104).  
* "Majorana-Hubbard model on the honeycomb lattice", **CL** and Marcel Franz, [Phys. Rev. B **98**, 115123 (2018)](https://doi.org/10.1103/PhysRevB.98.115123), [arXiv:1806.06092](https://arxiv.org/abs/1806.06092).  
* "Family of Sachdev-Ye-Kitaev models motivated by experimental considerations", Étienne Lantagne-Hurtubise\*, **CL**\*, and Marcel Franz, [Phys. Rev. B **97**, 235124 (2018)](https://doi.org/10.1103/PhysRevB.97.235124), [arXiv:1803.07197](https://arxiv.org/abs/1803.07197).  

The asterisk (\*) denotes equal contribution.

# More about me
My name is written as 李成疏 in Chinese and it is pronounced as /li<sup>21(4)</sup> ʈ͡ʂʰɤŋ<sup>35</sup> ʂu<sup>55</sup>/. 
(Not familiar with these symbols? They are called [IPA](https://en.wikipedia.org/wiki/International_Phonetic_Alphabet) and can be used to describe any language in the world! Did you know that [Mandarin](https://en.wikipedia.org/wiki/Standard_Chinese), like many other languages in the world, is a [tonal language](https://en.wikipedia.org/wiki/Tone_(linguistics))?) 

I was born in [Zhangjiakou](https://en.wikipedia.org/wiki/Zhangjiakou), a city near [Beijing](https://en.wikipedia.org/wiki/Beijing), and moved to [Shanghai](https://en.wikipedia.org/wiki/Shanghai) at the age of 5.  I went to Beijing for my undergrad and have lived in [Vancouver](https://en.wikipedia.org/wiki/Vancouver) since 2015.

Apart from physics, I am interested in linguistics, language learning ([français](https://en.wikipedia.org/wiki/French_language) and [日本語](https://en.wikipedia.org/wiki/Japanese_language)), [classical music](https://youtu.be/yM8CFR01KwQ), and [animes](https://en.wikipedia.org/wiki/Puella_Magi_Madoka_Magica). 

# Contact
chengshu(at)phas(dot)ubc(dot)ca
