---
title: "Introduction"
teaching: 5
exercises: 0
questions:
- "What is tag and probe method?"
- "Which efficiency?"
objectives:
- "Know what is tag and probe method."
- "Know what kind of efficiency we are looking for."
keypoints:
- "Tag and probe are labels for each muon of dimuon resonance."
- "Tag is a biased particle while probe are unbiased."
- "The efficiency we are looking in this exercise is for tracker muons."
---

## What is tag and probe method?

The tag and probe method consists calculating the efficiency of a dataset without depending on simulations. As it does not need simulations, there are necessary use known resonances as J/psi, Upsilon and Z Boson. This code is prepared to work with J/psi and Upsilon (1S) resonances.

## What is "tag" and "probe"?

In dimuons resonances we work with at least two muons which are labeled as tag and probe:

* Tag muon = well identified, triggered muon (tight selection criteria)
* Probe muon = unbiased set of the desired particle type with a very loose selection criteria

## How to get efficiency?

The simple efficiency definition worked so on in this code is:

<img width="300px" src="../fig/efficiency.svg" alt="Efficiency equation">

Passes particle in this workshop we will analyse is **Tracker muons** and this equation returns resonance reconstruction efficiency.

## CMS Muon identification reconstruction

Tracker muons are muons that are detected in cms inner trackers, but not necessarily only in this detector.

![CMS muon id](../fig/tracker_muon.png)

{% include links.md %}