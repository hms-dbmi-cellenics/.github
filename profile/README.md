# Cellenics

[Cellenics](https://scp.biomage.net/) is an open-source platform aimed at empowering research biologists to analyze their own single-cell RNA sequencing (scRNA-seq) datasets. In collaboration with the [HMS Single Cell Core](https://singlecellcore.hms.harvard.edu/), the [Harvard Chan Bioinformatics Core](https://bioinformatics.sph.harvard.edu/), input from the [Biopolymers Facility](https://genome.med.harvard.edu/) and the [Center for Computational Biomedicine](https://computationalbiomed.hms.harvard.edu/), we developed a user-facing application for project management as well as data processing, quality control, and visualization (Fig. 1). These modules enable in-depth data exploration through differential expression and pathway analyses as well as the generation of fully customizable plots for publication. 

Cellenics consists of multiple repositories - the codebase of the platform itself, as well as repositories that define the AWS infrastructure and provide various utilities. 

**Want to contribute to our open source community efforts?** [Open an issue](https://github.com/hms-dbmi-cellenics/issues/issues) or [contact us!](mailto:alex_pickering@hms.harvard.edu)

## Repositories


### Bioinformatics


- **[pipeline](https://github.com/hms-dbmi-cellenics/pipeline)** - Bioinformatics repository for the Data Processing module.
- **[worker](https://github.com/hms-dbmi-cellenics/worker)** - Bioinformatics repository for running analyses on processed datasets.

### Front-end and Infrastructure
- **[ui](https://github.com/hms-dbmi-cellenics/ui)** - User interface for the platform built with React/Redux.
- **[api](https://github.com/hms-dbmi-cellenics/api)** - A nodejs service that sits in between the UI and the Cellenics backends (pipeline, worker).
- **[iac](https://github.com/hms-dbmi-cellenics/iac)** - AWS Infrastructure as Code and GitOps repository.

# 

![Cellenics Platform](https://user-images.githubusercontent.com/15719520/168172809-6dc19248-3e4d-4814-911c-92f12dded8f2.png)


**Figure 1: Cellenics Platform.** Cellenics is an open-source, cloud-based platform developed in the [Department of Biomedical Informatics](https://dbmi.hms.harvard.edu/). A. Current Cellenics Modules developed in Phases 1 & 2. B. Data Processing module. C. Data Exploration module. D. Differential expression tool within the Data Exploration module. E. Plots and Tables module.

## Getting Help

**Need help with your analysis?** Here are some brief tutorials:
- [Full Demo](https://www.youtube.com/watch?v=LXIhiIyxHME)
- [Data Upload and Management](https://www.youtube.com/watch?v=aTkBEK3L-KI)
- [Data Processing](https://www.youtube.com/watch?v=0pwXUMMGnlA)
- [Data Exploration](https://www.youtube.com/watch?v=JKd_nhroAUc)
- [Plots and Tables](https://www.youtube.com/watch?v=0pwXUMMGnlA)

There is also a more in-depth [recorded workshop](https://harvard.zoom.us/rec/share/6RMnOKMu25_UL_HrmJ8MNLekwRMPviviaCeo6qytKYFzRGApwnyvleTUOCGr_3jU.OGQCZ2mfgJZnQReC) (~2 hours).
