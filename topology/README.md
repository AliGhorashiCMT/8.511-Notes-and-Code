# Topology in condensed matter 

## General description 

The notes and code here concern a range of topological concepts in the context of condensed matter physics: the SSH model/Peierls instability in one dimensional solids, the Haldane model, 
numerical computation of the Berry curvature and the Chern number in time-reversal broken systems, symmetry indicators, Berry phase winding, Thouless pumping, and the Rice-Mele model. 
Also included are links to hackmd documents with solutions to problem sets 9, 10 and 11.

## Problem set solutions
  **Problem set 9 solutions**:
    https://hackmd.io/@aligho/Bylu6bZNWkx
  
  **Problem set 10 solutions**:
    https://hackmd.io/@aligho/BJoXatvm1x
  
  **Problem set 11 solutions**:
    https://hackmd.io/@aligho/r1tyZnsXye

## Hackmd notes on topological concepts
  **Notes on the intraband and interband matrix elements of the position operator and their relationships with the Berry connection**:
    https://hackmd.io/@aligho/BkVpBDAMJx
  
  **Notes on sum rules**:
    Local limit: https://hackmd.io/@aligho/HksXTPsXkg
    Nonlocal limit: https://hackmd.io/@aligho/rJSMoJ5NJg
  
  **Notes on conductivity through four different gauge conventions, and how the intraband position operator gives the Hall conductivity**:
    https://hackmd.io/@aligho/SJLbTu1Q1g
  
  **Notes on finding the Chern number through C3 symmetry eigenvalues**:
    https://hackmd.io/@aligho/S1zowSzXJe (These correspond to the two notebooks on symmetry indicators for the Haldane model and the Kagome lattice)
  
  **Notes on the Hall conductivity of Landau levels in length gauge**: 
    https://hackmd.io/@aligho/Sk0cpVBQ1g

## Description of jupyter notebooks
  **Peierls.ipynb**: Calculation of the Peierls instability in the exact limit and in the Dirac cone approximation (see page 140 of the book by Girvin and Yang). 
  
  **Filling anomaly.ipynb**: Realization of the filling anomaly and edge states at the boundary of two SSH chains. 
  
  **Haldane.ipynb**: Calculation of the electronic dispersion, Berry curvature, Chern number, edge states, and Berry phase winding for the Haldane model.
  **Reference:** *Haldane, F. Duncan M. "Model for a quantum Hall effect without Landau levels: Condensed-matter realization of the" parity anomaly"." Physical review letters 61.18 (1988): 2015.*

  **Kagome without TR.ipynb**: Calculation of the electronic dispersion, Berry phase winding, and edge states for a Kagome lattice in which time reversal symmetry is broken. 

  **Haldane symmetry indicators.ipynb** and **Kagome symmetry indicators.ipynb**: Calculating the Chern numbers of the Haldane and Kagome lattices above using $C_3$ rotational symmetry indicators.
  See *Vaidya, Sachin, et al. "Topological phases of photonic crystals under crystalline symmetries." Physical Review B 108.8 (2023): 085116.* for a good tutorial on how this works. 

  **Rice Mele.ipynb**: The Rice-Mele model. 

