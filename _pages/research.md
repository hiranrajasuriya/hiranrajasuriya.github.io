---
layout: archive
title: "Selected Research Projects"
permalink: /research/
author_profile: True
---

## Deep Geometric Framework to Predict Antibody-Antigen Binding Affinity
The efficacy of a drug depends on the extent to which the constituent molecules interact with the target molecules. Accordingly, the binding affinity must be evaluated during the drug design phase to achieve the desired efficacy levels. Our study focused on Antibody (Ab)-Antigen (Ag) binding, which is a subclass of proteins. Currently, techniques such as Molecular Docking and Molecular Dynamics (MD) simulation are employed to determine the binding affinity at different binding poses. However, Molecular docking overlooks the temporal behaviour and hence, could be less accurate. On the other hand, MD simulations are accurate but computationally expensive and time-consuming in general, and these complexities rise exponentially with the number of atoms in the molecules.

Due to the limitations of the existing simulation techniques, we developed a novel deep geometric network that consists of a geometric model that could process the 3D structures and a sequence model that could handle the amino acid sequences of the input proteins. We employed attention mechanisms in both models to ensure that atomistic level information as well as evolutionary information are incorporated into neighbour embeddings.

Currently, we are drafting a research paper and it is <b>to be submitted to Nature Biotechnology.</b>
<!-- <p align="center"><img src="../images/COMPLETEMODEL.png" width="1000"/></p> -->
[![](../images/COMPLETEMODEL.png){width=800px}](../images/COMPLETEMODEL.png)

For more details: <a href = 'https://drive.google.com/file/d/1NkxO8fNq3UGV0jqNu1U2A8QNA0jpSgeo/view?usp=sharing'>Report</a>