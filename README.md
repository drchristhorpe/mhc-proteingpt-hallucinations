#ProtGPT-2 MHC Class I hallucinations


## Software used

### ProtGPT-2

https://colab.research.google.com/drive/15ucZMtrAeFE_YOBQ9FdrWlAngvljJ4ss

#### Parameters used for experimental runs

All defaults, variation on sequence_min_length and sequence_max_length to try to find optimal length

#### Paramaters used for production runs

sequence_min_length = 370
sequence_max_length = 370
split_fasta = false
align_fasta = true


### ColabFold


### Multiple alignments

https://mafft.cbrc.jp/alignment/server/



### Sequence logos


### Visualisation


## References


### ProtGPT-2

https://www.biorxiv.org/content/10.1101/2022.03.09.483666v1

### MAFFT

https://academic.oup.com/bib/article/20/4/1160/4106928

https://academic.oup.com/nar/article/41/W1/W22/1099639

### ColabFold

https://www.nature.com/articles/s41592-022-01488-1

## Workflow

1. Sequences are created using ProtGPT-2 Google Colab Notebook using the sequence including the leader peptide.
2. The leader peptide is stipped and the sequence is pasted into the ColabFold notebook. 


## Experimental plan (and additions)


## Lab notebook


## Notes on the various sets of files

