# Transcription-Factor-Modes

## Description
This repository contains work done for the [Dowell Allen Laboratory](http://dna.colorado.edu/index.html) during a research rotation between 1/1/2019 and 3/15/2019 as part of the CU Ph.D. biochemistry program. 

## Aims in brief
The principal goal of this research is to investigate and develop means of classifying and describing a Transcription Factor's regulational behavior based upon experimental GRO-seq data. To this aim, a data set containing nearly 500 unique experiments was compiled and used to define the relationship between the abundance of a particular transcription factor and its percieved activity as measured by MD score. The Motif-Displacement, or MD score of a particular Transcription factor is a meteric that infers TF activity from the co-localiztion of Transcription Factor binding motifs with eRNA origins. TF abudance was inferred from the number of nascent or mRNA copies of that TF taken from the same experiment as the MD score. 


## Results in brief
This research concludes that it is possible to accurately predict Transcription Factor regulational behavior based upon a collection of GRO-seq data. This includes binning each TF as a either promoter or repressor of transcription and defining the nature of its regulation as positive, negative, or non-regulatory. This research demonstrates the possibility of leveraging large-scale GRO-seq data to study TF mechanisms and behavior from an individual level up to scale. 

## Files description

### linear regression sorting
Shows the classifying of individual TF's as promoter/repressors and negative/positive/unregulated at scale from the relationship between lfpkm(abundance of TF) and MD score.

### Visualizing TF regulation.
Helps visualize the relationship between lfpkm and MD score and demonstrate how this may be leveraged to infer information about the TF.

### Comparing lfpkm distribution (covariance, std. dev, and IQR)
Compares TFs by GC content
