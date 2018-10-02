# intragenomic_rrna_variability_in_plants

## initial reasoning
So I had this notion that intra-genomic variation in the ITS region of the rRNA cluster in plant genomes has to do with genome size, and that ITS in the rRNA should not be used as a marker for phylogenetic analyses. The former is known and published although in pieces (alvarez 2003 & prokopowhich 2003 & plenty more I’m sure). The latter is also commonly accepted, yet the ITS is commonly used in plant phylogenetic studies. What is missing is a bigger integrated study of plant rRNA cistrons including big plant genomes and an assessment of how this realistically can effect phylogenetic studies. I seem to remember I assessed this as a novel thing when a student report pointed me to the intragenomic variability of the ITS, but a quick search through literature indicates this is not the case. My guess is that the student at the time missed out on this quite simple literature search or I missed out on his literature research in his report. The initial students observations were (1) there is a big intra-genome variability in the Azolla ITS region (2) the variability has some pattern (3) this pattern is consistent among species of Azolla. Here I plan an open systematic look into this matter.

## Build-up
Meta-analysis part:
1.	Hypothesis: rRNA copy nr increases with genome size.
    *	Alternative hypothesis: phylogenetic pattern
    *	Yes, Prokopowich (2003) showed this for 68 plants and 94 animals in 2003. 
          *	How many more plant genomes and rRNA copy nrs are available these days, and is it worth redoing this 15 years after date.
          *  Prokopowhich: “It might be expected that the need for ribosomes would increase as genome size increases if the relative proportion of protein-coding genes remains constant. However, the number of protein-coding genes does not increase proportionately (reviewed in Cavalier-Smith 1985).”
2.	Do ITS lengths (and possibly functional content) relate to genome size
    *	Alternative hypothesis: phylogenetic pattern
    *	Or is it all over the place: Rogers 1987
    *	Really, we should be talking about a length distribution per genome
    
Assembly analysis part:

3.	Technical: How many rRNA copies are preserved in draft genomes
    * Sub: differentiate among sequencing strategies
    * Sub/comeback: are these rRNA clusters (or single rRNA cistrons) a consensus, identical, or do they diverge. (per assembly strategy)
           *	How do rRNA clusters end up in genomes (metagenomes) and how do these compare to sanger sequenced results.
    *	Sub: do these differentiate from rRNA PCR fragments sequenced in databases
  
Reads backmapping to rRNA fragments part:

4.	Intra genome variation of
      *	rRNA genes -> should be practically zero
            *	this seems not to be published
      *	ITS regions  
            *	This is published at least in non-plants
5.	Certain pattern in ITS variation
      *	Is there functional regions in ITS regions
      *	Similar in individuals of the same species
      *	Similar in the same genes
      *	Family…
  
Combine:

6.	Overall ITS variation as a function of genome size
    *	Alternative: phylogenetic
7.	Realistic worst case scenario’s when mis-base-calling such fragments.

## Data to be generated collected
List of plants with
* Plant
    * Name
    * Origin
    * Specimen
* Genome size
    * Size
    * Technique of size determination
* known rRNA copy nr
    * Technique
* raw sequencing data available
    * accession nr
* annotated genomes
    * accession nr
    * fasta
    * gff (including rRNA repeats)
    * assembly technique

## Novelties to be found:
Scripted redo of Prokopowhich with more genomes and more modern data, not truly novel but I will have to do this to get started anyhow.

How do rRNA clusters end up in genomes (metagenomes) and how do these compare to sanger sequenced results. <- implications for placing sequenced results in a tree.

Is there an (explainable pattern) of intragenomic variability in plant ITS regions. 

Simulate how bad variable base calls due to intragenomic variability can mess up a phylogeny.

What I miss… a more evolution central experiment/explanation of the data like Ganley 2007

Conclusion… ITS is not really trustworthy. Use single copy genomic genes. But that’s not a new advise is it. Perhaps we can give a more nuanced advise, how bad is it really in simulations and is it genome size (~copy nr) dependent.

###Questions I still have
Has the ITS some folding function in the self-assembly of the ribosome

Can we do phylogeny and alignment on a variable sequence; multiple sequence alignments of seqlogos/hmms… or is this black magic.

#Literature
alvarez 2003 Ribosomal ITS sequences and plant phylogenetic inference
Ganley 2007 Highly efficient concerted evolution in the ribosomal DNA repeats: Total rDNA repeat variation revealed by whole-genome shotgun sequence data
Prokopowich 2003 The correlation between rDNA copy number and genome size in eukaryotes
Rogers 1987 Ribosomal RNA genes in plants: variability in copy number and in the intergenic spacer


