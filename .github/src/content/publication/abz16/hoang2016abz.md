---
title: "Validating the Requirements and Design of a Hemodialysis Machine Using iUML-B, BMotion Studio, and Co-Simulation"

authors:
  - Thai Son Hoang
  - Colin F. Snook
  - Lukas Ladenberger
  - Michael J. Butler

date: 2016-05-01

# Schedule page publish date (NOT publication's date).
# publishDate: 2020-06-19T16:42:07+02:00

publication_types:
  - 1 # conference paper

publication: "5th International Conference on ASM, Alloy, B, TLA, VDM, and Z (ABZ'16)"
publication_short: "ABZ'16"

tags:
  - ABZ'16

categories: []

featured: false

projects:
  - abz16

links:
  - name: Digital
    url: https://eprints.soton.ac.uk/394742/1/HDMachine-final.pdf
    icon_pack: fas
    icon: file-pdf
  - name: Printed
    url: https://doi.org/10.1007/978-3-319-33600-8_31
    icon_pack: fas
    icon: book
  - name: Abstract
    url: "publication/hoang2016abz/#abstract"
    icon_pack: fas
    icon: file-alt
  - name: View
    url: "publication/hoang2016abz/#document"
    icon_pack: fas
    icon: glasses
  - name: Cite
    url: "publication/hoang2016abz/#reference"
    icon_pack: fas
    icon: quote-right
  - name: Source
    url: "publication/hoang2016abz/#sources"
    icon_pack: fas
    icon: database

slides: ""
---

## Abstract

We present a formal specification of a hemodialysis machine (HD machine) using Event-B. We model the HD machine using iUML-B state-machines and class diagrams and build a corresponding BMotion Studio visualisation. We focus on validation using (i) diagrams to aid the modelling of the sequential properties of the requirements, and (ii) ProB-based animation and visualisation tools to explore the system’s behaviour. Some of the safety properties involve dynamic behaviour which is difficult to verify in Event-B. For these properties we use co-simulation tools to validate against a continuous model of the physical behaviour.

## Document

{{< embed-pdf url="https://eprints.soton.ac.uk/394742/1/HDMachine-final.pdf" >}}

## Reference

```
% BibTex
@InProceedings{10.1007/978-3-319-33600-8_31,
author="Hoang, Thai Son
and Snook, Colin
and Ladenberger, Lukas
and Butler, Michael",
editor="Butler, Michael
and Schewe, Klaus-Dieter
and Mashkoor, Atif
and Biro, Miklos",
title="Validating the Requirements and Design of a Hemodialysis Machine Using iUML-B, BMotion Studio, and Co-Simulation",
booktitle="Abstract State Machines, Alloy, B, TLA, VDM, and Z",
year="2016",
publisher="Springer International Publishing",
address="Cham",
pages="360--375",
isbn="978-3-319-33600-8"
}
```

## Sources

- **Model Archive:**
  Please contact <a href ="mailto:t.s.hoang@ecs.soton.ac.uk;cfs@ecs.soton.ac.uk">authors</a>
- **Presentation:**
  Not available
- **Used formal method:**
  [Event-B](/method/event-b)
- **Resources and tools:**
  ProB
- **Required OS:**
  Not available
- **Website:**
  Not available
- **Remarks and recommendation:**
  Not available
