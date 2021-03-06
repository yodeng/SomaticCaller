# Somatic Variant Calling Pipeline

![version](https://img.shields.io/badge/Version-0.0.1-red.svg?style=flat-square)

This pipeline is based on GATK best practices for somatic variant calling Tumor matched Normal NGS dataset.

## Workflow

![Workflow from GATK](img/BP_somatic_workflow_M2.png)

## Dependencies

|Software|Databases|
|:-------|:--------|
|![GATK](https://img.shields.io/badge/GATK-3.x-brightgreen.svg?style=flat-square)|![Genome](https://img.shields.io/badge/Genome-GRCh37-blue.svg?style=flat-square)|
|![QUEUE](https://img.shields.io/badge/QUEUE-3.x-brightgreen.svg?style=flat-square)|![Hapmap](https://img.shields.io/badge/Hapmap-3.3-blue.svg?style=flat-square)|
|![Picard](https://img.shields.io/badge/Picard-2.1x-brightgreen.svg?style=flat-square)|![COSMIC](https://img.shields.io/badge/Cosmic-82-blue.svg?style=flat-square)|
|![JAVA](https://img.shields.io/badge/JDK-8.x-brightgreen.svg?style=flat-square)|![dbSNP](https://img.shields.io/badge/dbSNP-138-blue.svg?style=flat-square)|

## Bash version

### Flowchart

![Flowchart (draw.io)](img/flowchart.svg)

## TODO

- [ ] Bash version
	- [x] Make it works
	- [x] Make flowchart
	- [ ] Defined options
	- [ ] Make usage/Help
	- [ ] Expand from fastq
	- [ ] Add cpt for warning, error...
- [ ] Documentation
	- [x] List dependencies
	- [ ] How to install dependencies
	- [ ] PDF
- [ ] SnakeMake

## Ressources

- [Best Practices for Somatic SNV and Indel Discovery in Whole Genome and Exome Sequence (BETA)](https://software.broadinstitute.org/gatk/best-practices/mutect2.php)

- [GATK workshop : 2017 Feb workshop presentation slides and tutorial materials](https://software.broadinstitute.org/gatk/blog?id=9044)
	- [Call somatic SNVs and indels using GATK MuTect2](https://drive.google.com/file/d/0BwTg3aXzGxEDdXRsY1hWdzU5TzQ/view)
