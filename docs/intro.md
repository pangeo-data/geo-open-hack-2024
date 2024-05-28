---
# File metadata may be provided as frontmatter YAML
title: Big Geospatial Data Hackathon with Open Infrastructure and Tools
subtitle: GEO-OPEN-HACK-2024
description: GEO-OPEN-HACK-2024 is a comprehensive and informative event designed for advanced geo-coders to explore various open tools and approaches for upscaling geospatial analysis on open High-Performance Computing (HPC) infrastructure.
date: 2024-05-28
authors:
  - id: annefou
    name: Anne Fouilloux
    orcid: 0000-0002-1784-2920
    corresponding: false
    roles:
      - Pangeo
    affiliations:
      - simula
  - id: tinaok
    name: Tina Erica Odaka
    orcid: 0000-0002-1500-0156
    corresponding: false
    roles:
      - Pangeo
    affiliations:
      - ifremer
affiliations:
  - id: simula
    name: Simula Research Laboratory
    city: Oslo
    country: Norway
    url: https://www.simula.no
    ror: https://ror.org/00vn06n10
  - id: ifremer
    name: IFREMER
    city: Brest
    country: France
    url: https://www.ifremer.fr
    ror: https://ror.org/044jxhp58
tags:
  - pangeo
  - stac
  - machine-learning
thumbnail: images/pangeo-logo.png
---

#  GEO-OPEN-HACK-2024: Big Geospatial Data Hackathon with Open Infrastructure and Tools

+++ {"part":"abstract"}

% The article should include an abstract block at the beginning. The block is delimited by `+++` before and after, and you must specify `"part": "abstract"` as JSON metadata on the block opener. This metadata is required for recognizing the content of this cell as the abstract.
% The abstract should begin with a short description of the problem addressed, briefly describe the new data or analyses, then briefly state the main conclusion(s) and how they are supported, and address any uncertainty.

This tutorial will provide a comprehensive introduction along with hands-on examples to help you understand how these technologies can be used for Earth science data analysis and interpretation.

+++

# Overview
 
In this tutorial, participants will learn how to 1) navigate the Pangeo ecosystem for scalable Earth Science workflows and 2) exploit Earth Observation (EO) data.

## Tutorial Learning Objectives

By the end of this tutorial, learners will be able to:

- Understand the Pangeo ecosystem
- Learn to access, load, and analyse data using Xarray, visualising data with Hvplot, and scaling workflows with Dask.

## Prerequisites

Before starting this tutorial, learners should have:

- Good knowledge of Python or another programming language;
- Good knowledge of geospatial data structures;

## Set up

If you are participating in this training as part of the GEO-OPEN-HACK-2024, you will need to register to [Pangeo@EOSC](https://pangeo-data.github.io/pangeo-eosc/) register yourself following the instructions given at [getting started for users](https://pangeo-data.github.io/pangeo-eosc/users/users-getting-started.html).
