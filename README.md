# **Dfam SVA Track Hub (hg38)**
## Overview

This repository provides a UCSC Genome Browser Track Hub containing annotations of SINE-VNTR-Alu (SVA) retrotransposons extracted from an updated Dfam RepeatMasker annotation of the human reference genome (hg38).

The purpose of this project is to facilitate visualization and exploration of SVA elements in the human genome and to compare updated Dfam annotations with the RepeatMasker track currently available in the UCSC Genome Browser.

## Data Source

The annotations were obtained from a Dfam-derived RepeatMasker annotation of the human genome assembly hg38.

Only entries corresponding to SVA elements were extracted and converted into a BigBed track for efficient visualization in the UCSC Genome Browser.
Track Contents

### The track contains genomic coordinates of:

- SVA_A
- SVA_B
- SVA_C
- SVA_D
- SVA_E
- SVA_F

and related SVA-derived annotations present in the Dfam release used to generate the dataset.

## __UCSC Genome Browser__

### To load this Track Hub in the UCSC Genome Browser, navigate to:

My Data -> Track Hubs -> My Hubs

and provide the following URL:

`https://raw.githubusercontent.com/JCPerez/SVA-trackhub/blob/main/hub.txt`
into here:

http://genome.ucsc.edu/cgi-bin/hgHubConnect#unlistedHubs


### Author:
Juan Carlos Pérez
