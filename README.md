## Meta-repository: collection of my Nextflow pipelines

Toy pipelines for prototyping and testing platforms and functionalities:
- [toy-cowsay-nf](https://github.com/marcodelapierre/toy-cowsay-nf): Toy pipeline for simple Nextflow tests
- [toy-shpc-nf](https://github.com/marcodelapierre/toy-shpc-nf): Toy RNAseq pipeline, to test interplay of Nextflow with SHPC container modules
- [toy-acacia-nf](https://github.com/marcodelapierre/toy-acacia-nf): Toy pipeline to test Nextflow with Acacia (S3 Object Storage) at Pawsey
- [toy-gpu-nf](https://github.com/marcodelapierre/toy-gpu-nf): Toy pipeline to test Nextflow with Nvidia GPUs on Topaz at Pawsey
- [toy-quantum-qb-nf](https://github.com/marcodelapierre/toy-quantum-qb-nf): Toy pipeline to run Quantum Computing simulations using Qristal by Quantum Brilliance

Analysis pipelines for the life sciences:
- [eDNAFlow](https://github.com/mahsa-mousavi/eDNAFlow): Pipeline for analysis of environmental DNA, led by Mahsa Mousavi ([Scientific paper](https://doi.org/10.1111/1755-0998.13356))
- [trinity-nf](https://github.com/marcodelapierre/trinity-nf): Trinity assembly pipeline for BioCommons, ported from USydney Informatics Hub ([WorkflowHub entry](https://workflowhub.eu/workflows/114))
- [nanopore-nf](https://github.com/marcodelapierre/nanopore-nf): Nanopore pipeline for DPIRD
- [illumina-nf](https://github.com/marcodelapierre/illumina-nf): Illumina pipeline for DPIRD

Major contributions to the Nextflow codebase (Pawsey days, 2019-2023):
- Support for Spack package manager in Nextflow: [PR #3580](https://github.com/nextflow-io/nextflow/pull/3580) and [PR #3786](https://github.com/nextflow-io/nextflow/pull/3786)
- Support for Sarus container runtime (Nextflow): [PR #3470](https://github.com/nextflow-io/nextflow/pull/3470)
- (Prototype) Support for Spack package manager in Wave: [PR #3636](https://github.com/nextflow-io/nextflow/pull/3636)
