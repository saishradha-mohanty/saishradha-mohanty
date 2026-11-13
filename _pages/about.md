---
layout: about
title: about
permalink: /
subtitle: PhD Student, <a href='https://www.cics.umass.edu/'>Manning College of Information and Computer Sciences</a>, University of Massachusetts Amherst

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true
  more_info: >
    <p>Amherst, MA</p>

selected_papers: false
social: true # icons configured in _data/socials.yml

announcements:
  enabled: false

latest_posts:
  enabled: false
---

I'm a PhD student in Computer Science at the University of Massachusetts Amherst, advised by
[Prof. Anna Green](https://sage.cs.umass.edu/) in the SAGE Lab. I work on machine learning for computational biology:
**biological foundation models**, **protein and genomic sequence modeling**, and **AI-driven biological discovery**,
with a particular interest in representation learning and mechanistic interpretability.

Much of my research is about antimicrobial resistance: predicting drug resistance from bacterial genomes, understanding
what protein language models have actually learned, and building agentic systems that help generate and test hypotheses
about new resistance mechanisms.

Before the PhD, I completed an MS in Computer Science at UMass Amherst (2024) and a B.Tech in Computer Science and
Engineering at IIT Tirupati (2020), where I received the Governor's Medal. In between, I spent two years as a machine
learning engineer at Mindbody, building recommender systems and ML infrastructure.

### Research

**Towards Sparse Causal Features for Zero-shot Mutation Effect Prediction in a Protein Language Model**<br>
**S. Mohanty**, M. Phutela, A. G. Green<br>
_bioRxiv preprint, 2026 (in submission)_ · [paper](https://doi.org/10.64898/2026.08.28.747907)

A causal feature-discovery framework for ESM-2 that combines sparse autoencoders with activation patching to find the
features driving its zero-shot mutation-effect predictions. Across 67 mutations in the DNAJA1 protein, sparse circuits
made of about 0.2% of the identified features recover model behavior in 88% of cases (15% for baselines), and many of
these features line up with conserved motifs and 3D residue contacts.

**BIG-TB: A Benchmark for Prediction and Interpretability of Sequence-Based Machine Learning Using _Mycobacterium tuberculosis_ Genomes**<br>
M. Tasmin\*, **S. Mohanty**\*, S. Kulkarni, M. R. Farhat, A. G. Green · \*equal contribution<br>
_bioRxiv preprint, 2026 (under revision)_ · [paper](https://doi.org/10.64898/2026.01.30.702134)

An open benchmark, built with Harvard Medical School, of 17,942 _M. tuberculosis_ genomes with drug-resistance
phenotypes across 11 antibiotics. We compare biological foundation models (Evo2, ESM-2) with traditional ML, including on
held-out lineages, and check model explanations against clinically established resistance mutations. Strong predictive
performance turns out not to guarantee biologically faithful explanations.

**Unifying Themes in Antibiotic Resistance: Towards Improving Predictive Machine Learning Models of Drug Resistance with Cross-Pathogen Insights**<br>
B. Reimer, H. Poonawala, **S. Mohanty**, A. G. Green<br>
_In submission to Antimicrobial Agents and Chemotherapy (AAC)_

Examines resistance themes that recur across pathogens and how these cross-pathogen insights can improve machine
learning models that predict drug resistance.
