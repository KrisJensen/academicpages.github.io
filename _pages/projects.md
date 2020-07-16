---
layout: archive
title: "Projects past & present"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---

{% include base_path %}

## Manifold Gaussian process latent variable models

<img src="https://krisjensen.github.io/images/concept.png" alt="pretty picture" width="30%" style="float: top">

{: style="text-align: justify" }
Methods for dimensionality reduction such as PCA, tSNE, GPFA, LFADS etc. are frequently used in neuroscience to try to decipher what low-dimensional quantities are represented by high-dimensional neural activity.
However, these methods implicitly assume Euclidean latent states which is at odds with how the brain is thought to represent quantities such as head direction and certain motor plans.
With Calvin Kao and Guillaume Hennequin in the CBL, we build on work by Anqi Wu in Jonathan Pillow's lab to extend the Gaussian Process Latent Variable Model originally developed by Neil Lawrence to cases where the latent space is no longer Euclidean.
We expect this framework to be useful for querying spatial representations in the brain ranging from navigation circuits to cognitive processes and motor control.
Current work-in-progress includes extending the probabilistic mGPLVM framework to a Poisson noise model, adding a prior over the temporal smoothness of neural activity, and further applying the framework to experimental data.
We are also working on a general-purpose python implementation which we will release shortly, but until then please contact us if you want access to our partially-finished codebase.

## Stability of motor memories

{: style="text-align: justify" }
<img src="https://krisjensen.github.io/images/stability.png" alt="pretty picture" width="31.5%" style="padding-right: 1%; padding-top: 0.5%; float: left;">
Motor memories such as the ability to serve in tennis can last for many months and years even without further practice, but it remains unclear how such memories are stored at the circuit level.
The literature on this topic has seen conflicting results, but most of these suffer partly from an inability to record the same neurons for long periods of time during complex motor behaviors.
In this work with Bence Ölveczky at Harvard Center for Brain Science, we investigate the stability of the neural correlates of two motor behaviors, one learned and one innate.
We record from both motor cortex and dorslateral striatum and find stable correlates of behavior in both brain regions.
This suggests that stable single-neuron activity can underlie persistent memories which in turn suggests an underlying circuit with a stable core that is largely unperturbed after learning.

## Head direction circuits in the <i>Drosophila</i> central complex

{: style="text-align: justify" }
<img src="https://krisjensen.github.io/images/cx.png" alt="pretty picture" width="40%" style="padding-right: 1%; padding-top: 0.5%; float: left;">
Head direction circuits have been characterized in organisms ranging from insects to mammals and are important for navigation.
The head direction circuit in <i>Drosophila melanogaster</i> has been characterized in an effort led by Vivek Jayaraman in a series of papers between 2015 and now.
This circuit exists in the so-called central complex of the fly which consists of multiple recurrently connected neuropils.
In this work with Daniel Turner-Evans and Vivek Jayaraman at Janelia Reseaerch Campus, we characterize the fly head direction at molecular, synaptic, functional and behavioral levels in the context of Ben-Yishai's canonical ring-attractor model.
We verify that the features of the circuit are consistent with such a ring-attractor model as previously hypothesized.
However, we also find additional local connectivity and distributed functions which we hypothesize might help increase the robustness of the circuit.

## <i>ab initio </i> modelling of electron transfer reactions

{: style="text-align: justify" }
<img src="https://krisjensen.github.io/images/ET.png" alt="pretty picture" width="35%" style="padding-right: 1%; padding-top: 0.5%; float: left;">
Electron transfers are ubiquitous in the world around us, taking place in proceesses ranging from solar cells to photosynthesis and respiration.
However, such electron transfer reactions are notoriously hard to model computationally, in part due to the relative difficulty of modelling excited states of molecular systems.
In this work with Alex Thom in the Cambridge Department of Chemistry, we used Hartree-Fock based methods to formulate electron transfer reactions as paths on the HF energy surface.
This builds on work by Alex Thom and Martin Head-Gordon showing that multiple Hartree-Fock solutions of the same molecule resemble adiabatic electronic states.
We can therefore model an electron transfer as a trajectory between local minima on the HF energy surface, where we find the optimal reaction trajectory in geometry space using a constrained optimization on the hyperplane where the reactant and product states have the same energy.

## Efficiency of CRISPR/Cas9-mediated genome editing

{: style="text-align: justify" }
<img src="https://krisjensen.github.io/images/crispr.png" alt="pretty picture" width="12.75%" style="padding-right: 1%; padding-top: 0.5%; float: left;">
CRISPR/Cas9 has revolutionized the biomedical sciences since it was first introduced for reprogrammable genome editing in 2012.
However, much remains to be understood about the system and how it operates in mammalian cells.
In this research project with Yonglun Luo at Aarhus University, we used assays in HEK293 cells to investigate which biochemical factors affect the efficiency with which we can edit the human genome.
We found two major contributors to the gene editing efficiency.
First, we found that the chromatin state at the target site was important with editing being less efficient in heterochromatin were the DNA is more tightly bound to histones.
Secondly, we found the capacity for RNA secondary structure formation of the guide sequence to affect editing, which we expect to be due to its effect on the strength of binding to the target DNA.