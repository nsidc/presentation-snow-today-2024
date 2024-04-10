---
title: "Snow Today Viewer demo"
subtitle: "2024 edition"
date: "2024-04-10"
format: revealjs
author:
  - name: "Matt Fisher"
---

## Overview

1. Review of front- and back-end design
2. New multi-region complexity: a specification to the rescue!
3. What's new in the GUI?


## Review of front- and back-end design

[View diagram](diagram.qmd)


## New multi-region complexity {.smaller}

* Previously, the data provider -> webapp interface was under-specified
    * We weren't always on the same page
    * We often needed to post-process data from providers. Confusing!
* 🦸‍♀️  **A specification to the rescue!**
    * Sebastien Lenard and I collaborated on GitHub to establish firm agreements about
      the interface.
    * Decisions and discussions result in specification changes.
    * Guided our development and issue resolution.

[Visit the specifications page in our docs](https://snow-today-webapp-server.readthedocs.io/interfaces/)


## What's new in the GUI?

1. User is greeted by splash-style super-region selector
    * Many more regions to come!
1. Recurse through sub-sub-regions indefinitely
1. UI usability tweaks
    * Plot and map titles now more consistent and complete
    * Legends now motionless and out of the way
    * Darker default basemap

[Visit the GUI](https://nsidc.org/snow-today/snow-viewer)
