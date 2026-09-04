---
layout: post
title: "Virtual sensing for nuclear safety: replacing accelerometers with a deep-learning model"
date: 2026-09-04 08:00:00 +0900
description: Why I work on deep-learning surrogate models for the seismic response of nuclear power plant structures — and what "virtual sensing" actually buys us.
tags: virtual-sensing seismic deep-learning nuclear-safety
categories: research
giscus_comments: false
related_posts: false
---

When an earthquake shakes a nuclear power plant, the question that matters is deceptively simple: **how did every floor of every safety-critical structure respond?** Those floor responses decide whether the reactor auxiliary building stayed within design limits, whether critical equipment saw accelerations it was never qualified for, and — in the hours after the event — what an operator should inspect first.

The classical answer is *more sensors*. Bolt accelerometers to enough locations and you can read the response directly. But dense instrumentation is expensive to install, hard to maintain over a plant's decades-long life, and — crucially — you never have a sensor exactly where you later wish you did.

## The idea: reconstruct, don't instrument

My research asks a different question: **can we reconstruct the full seismic response from very sparse measurements?** Concretely, from a *single* seismometer signal, a pretrained deep-learning model reconstructs the floor responses across the structure — a kind of *virtual sensing* that stands in for dozens of physical accelerometers.

The model is a surrogate: instead of running a full finite-element simulation for every ground motion (which is far too slow for real-time use), it learns the input→response mapping once, offline, and then predicts in milliseconds. This is the same regression idea taught in any machine-learning course — fit a function to data — scaled up to the structural dynamics of a real plant.

<div class="row justify-content-center">
    <div class="col-sm-9 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cacaie_virtual_sensing.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Virtual sensing: a single seismometer input is mapped to floor responses across the structure by a pretrained deep-learning surrogate.
</div>

## Why it matters downstream

Once you can reconstruct responses everywhere, useful things follow almost for free:

- **Rapid post-earthquake triage.** Reconstructed floor responses flag which critical equipment exceeded its safety thresholds, so inspection crews know *what to check first* instead of walking the whole plant blind.
- **Fewer physical sensors.** Sparse instrumentation, dense information.
- **A basis for reliability analysis.** With responses in hand, probabilistic assessment of the structure becomes tractable.

This line of work appeared in *Computer-Aided Civil and Infrastructure Engineering* ([CACAIE, 2025](https://doi.org/10.1111/mice.70051)).

## What I care about beyond accuracy

A model that is accurate but opaque is a hard sell in a safety-critical setting. So a recurring theme in my work is making these surrogates **interpretable and physics-consistent** — understanding *what* the network keys on, constraining it with physical structure where possible, and quantifying *how uncertain* a prediction is rather than reporting a single number. Accuracy earns you a demo; interpretability and uncertainty earn you trust.

That, in a sentence, is what this site is about: deep learning that a structural engineer can actually rely on. More notes to come.
