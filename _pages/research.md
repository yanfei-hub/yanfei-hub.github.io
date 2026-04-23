---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on causal inference, target trial emulation, and longitudinal clinical modeling using real-world healthcare data such as electronic health records and claims. I am especially interested in building decision-relevant methodology that respects the structure of routine clinical care rather than assuming that observational data behave like idealized trial data.

## Research areas

### Target trial emulation with EHR
I develop target trial emulation frameworks for routine clinical data, with emphasis on how to reconstruct actions, define treatment strategies, align follow-up with decision time, and restrict evaluation to clinically supported regions of the observed data. This work aims to make longitudinal EHR-based analyses more faithful to real treatment decisions.

### Longitudinal treatment strategy evaluation
My work studies sustained treatment, switching, add-on therapy, discontinuation, restart, and delayed treatment effects. The goal is to define treatment histories and estimands that remain clinically meaningful when medication use evolves over time.

### Bias-aware real-world evidence
Because real-world data are shaped by care processes, I study confounding, censoring, irregular observation, selection bias, transportability, and support limitations. I am interested not only in estimation, but also in diagnosing when a comparison is and is not empirically reliable.

## Representative projects

### 1. Target Trial Emulation with EHR

<img src="/images/research/target-trial-ehr.png" alt="Target Trial Emulation with EHR" width="750">

This project develops an operational framework for reconstructing clinically meaningful target trials from electronic health records. The framework emphasizes action reconstruction from observed care data, decision-time aligned representations, support-aware estimation, and clinically interpretable longitudinal treatment comparisons.

Key ideas include:

- reconstructing treatment action from routine EHR records
- defining decision-time objects for longitudinal treatment evaluation
- identifying empirical support regions before comparing strategies
- aligning analysis with clinically meaningful treatment decisions rather than simplified baseline contrasts

**Related paper:** [An operational target trial simulation framework for clinical information using electronic health records](https://www.nature.com/articles/s41746-026-02563-z)  
**Code:** [EHR-Target-Trail-Emulation](https://github.com/yanfei-hub/EHR-Target-Trail-Emulation)

### 2. Longitudinal treatment strategies in routine care

<img src="/images/research/longitudinal-treatment-strategies.png" alt="Longitudinal treatment strategies" width="750">

This line of work studies add-on therapy, switching, persistence, gaps, restarts, and delayed treatment effects in longitudinal healthcare data. A central aim is to define strategy comparisons that better reflect how chronic treatment decisions are actually made in clinical care.

Representative topics include:

- add-on versus monotherapy strategies
- early versus delayed treatment intensification
- sustained exposure and lag-aware treatment effects
- treatment history definitions for chronic medication use

### 3. Interpretable disease progression and decision-oriented modeling

<img src="/images/research/disease-progression-modeling.png" alt="Disease progression modeling" width="750">

I also work on interpretable longitudinal modeling for disease progression, risk stratification, and treatment evaluation. This includes disease trajectory learning, uncertainty-aware modeling, and decision-facing representations that connect prediction with causal or policy questions.

Application areas include:

- Alzheimer’s disease and neurodegeneration
- cancer outcomes and treatment safety
- cardiovascular adverse events
- chronic disease progression
- drug repurposing using longitudinal clinical data
