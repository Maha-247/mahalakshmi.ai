---
title: 'Less is More: Benchmarking LLM Based Recommendation Agents'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - UC Santa Cruz Collaborator

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2026-04-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The ACM Web Conference 2026 (WWW 2026) — LARS Workshop*
publication_short: In *WWW 2026 LARS Workshop*

abstract: >
  Large Language Model (LLM) based recommendation agents have shown promising results but typically rely on large context windows filled with user history. In this paper, we benchmark multiple LLM-based recommendation agents across varying context lengths, investigating the relationship between context size, recommendation quality, and cost. Our experiments across DeepSeek V3, GPT-4o-mini, and Gemini 2.0 Flash on the REGEN and MovieLens datasets demonstrate that minimal context achieves comparable recommendation quality to full-history approaches, while yielding substantial cost savings. Our findings suggest that "less is more" — carefully curated, minimal context can match or exceed the performance of exhaustive context, with significant efficiency gains.

# Summary. An optional shortened abstract.
summary: >
  We benchmark LLM-based recommendation agents and show that minimal context achieves similar recommendation quality to large context windows, with significant cost savings across DeepSeek V3, GPT-4o-mini, and Gemini 2.0 Flash on REGEN and MovieLens datasets.

tags:
  - Large Language Models
  - Recommender Systems
  - LLM Agents
  - Benchmarking

# Display this page in the Featured widget?
featured: true

# Custom links
links:
  - type: pdf
    url: ""
  - type: code
    url: ""
  - type: slides
    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""
---

> [!NOTE]
> **Oral Presentation** at the LARS Workshop, ACM The Web Conference 2026 (WWW 2026).

This paper investigates the effect of context length on LLM-based recommendation agent performance and cost. Using a multi-model, multi-dataset experimental framework spanning DeepSeek V3, GPT-4o-mini, and Gemini 2.0 Flash across REGEN and MovieLens datasets, we find that minimal context achieves similar recommendation quality to full-history approaches — with significantly lower inference costs.

**Key findings:**
- Minimal context can match full-history recommendation quality
- Large cost savings are achievable without sacrificing accuracy
- Results are consistent across multiple LLMs and datasets