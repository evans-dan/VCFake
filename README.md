# VCFake - a Python 3 package to create synthetic Variant Call Format files, of varying complexities.

# Overview

This package will be used to create random Variant Call Format (VCF) files, commonly created as the output of 
genetic sequencing projects.  It will be species-agnostic, taking a referene genome as the single required 
input.  Its output will be standards-compliant VCF file(s).

# Objective:
- Create single VCFs with a random number of variants in random positions (according to the positions 
available in the reference genome); variants will be single nucleotide to start, and the number will be 
controlled by a mutation rate (will have an overridable default frequency).  Only the genotype tag (GT) will 
be present.

- Create single VCFs as above, but with read depths and strand distributions matching an overridable default 
distribution.

More objectives will be added as the project progresses (and as thoughts occur).
