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

#  GEO-OPEN-HACK-2024

**Big Geospatial Data Hackathon with Open Infrastructure and Tools**

+++ {"part":"abstract"}

% The article should include an abstract block at the beginning. The block is delimited by `+++` before and after, and you must specify `"part": "abstract"` as JSON metadata on the block opener. This metadata is required for recognizing the content of this cell as the abstract.
% The abstract should begin with a short description of the problem addressed, briefly describe the new data or analyses, then briefly state the main conclusion(s) and how they are supported, and address any uncertainty.

[GEO-OPEN-HACK-2024](https://iiasa.ac.at/events/jun-2024/geo-open-hack-2024-big-geospatial-data-hackathon-with-open-infrastructure-and-tools) is a comprehensive and informative event designed for advanced geo-coders to explore various open tools and approaches for upscaling geospatial analysis on open High-Performance Computing (HPC) infrastructure.

The event is organised by the [International Institute of Applied Systems Analysis (IIASA)](https://iiasa.ac.at) in collaboration with [Spatial Ecology](https://spatial-ecology.net/). 

+++

## Overview
 
This Pangeo tutorial is part of GEO-OPEN-HACK-2024 and will provide a comprehensive introduction along with hands-on examples to help you understand how these technologies can be used for Earth science data analysis and interpretation.

In this tutorial, participants will learn how to 1) navigate the Pangeo ecosystem for scalable Earth Science workflows on Pangeo@EOSC, and 2) exploit Earth Observation (EO) data.

:::{tip}
[Pangeo-EOSC](https://github.com/pangeo-data/pangeo-eosc/) has benefited from services and resources provided by the [EGI-ACE project](https://www.egi.eu/project/egi-ace/) (funded by the European Union’s Horizon 2020 research and innovation programme under Grant Agreement no. 101017567), and the [C-SCALE project](https://c-scale.eu/) (funded by the European Union's Horizon 2020 research and innovation programme under grant agreement no. 101017529), with the dedicated support of [CESNET](https://www.cesnet.cz/en/).
:::

## Tutorial Learning Objectives

By the end of this tutorial, learners will be able to:

- Learn about the European Open Science Cloud (EOSC)
- Understand the Pangeo ecosystem and Pangeo@EOSC;
- Learn to access, load, and analyse data using Xarray, visualising data with Hvplot, and scaling workflows with Dask;

## Prerequisites

Before starting this tutorial, learners should have:

- Good knowledge of Python or another programming language;
- Good knowledge of geospatial data structures;

## Set up

If you are participating in this training as part of the GEO-OPEN-HACK-2024, you will need to register yourself to [Pangeo@EOSC](https://pangeo-data.github.io/pangeo-eosc/). The set up instructions are given at [getting started with Pangeo@EOSC](https://pangeo-data.github.io/geo-open-hack-2024/setup/users-getting-started.html).

