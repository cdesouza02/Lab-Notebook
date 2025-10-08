## Jupyter notes
- do not use cutadapt to trim sequences, that reduces the quality of the og reads
- cutadapt to split sequences
	- size of files should reflect 3:1 16S:ITS2 molarity
### Dada2
- trims, filters, merges and denoises R1 and R2 from each sample
- this sets up the sequences in a way that they can be compared to the silva file
- make .csv files with QC results from each step, and 16S ASV files
- do not need to compare species, it takes so much memory and is impossible to do all at once

### Phyloseq
- phyloseq has explicit settings for how the data (sample meta, 16S_asv_nonchim, taxa should combine together 
- form OTU table, and uses that to compare the samples with the taxa
- use "Order" instead of "Family" for the plot next time
## Physalia course
 euclidean distance- more abundant species will completely dominate 
 - because squaring the differences
 - **good to use for abundance measure**
manhattan distance- abundant species will have less domination, rare species shine more
- because not squaring
**bray-curtis**- treats all species with equal weight
- percentage dissimilarity method used for ordinance
- **default in vegan**- **because they are standardizing the data as relative abundance***
- but conflates abundance with composition 
- cant be sure that the ordination if reflecting the abundance alone

Species abundance paradox
- conceptually can see that sample sets are relatvely differnent 
	- euclidean
		- but this is not considered by euclidean distance because taking into account magnitude
	- chi-square
		- shows relative abundances of taxa better

dissimilarity 
- vegdist() can exclude double zeros 
- decostand() standardization 
```
data(varespec)
euc_dij = vegdist(varespec, method = "euclidean")

#default is braycurtis 
bc_dij = vegdist(varespec)

hell_dij = vegdist(decostand(varespec, method = "hellinger"), method = "euclidean"
```
##### Interperting clusters
silhouette widths 
- of each object: 
	(smallest distance b/w object i and any other cluster)Bi- (how far are each of the observation of i away from other objects in the same cluster) Ai
	- goal is for b to be large and a to be small, means that there are good clustering 
	- = big silhouette widths
- silhouette()

https://sites.ualberta.ca/~ahamann/teaching/renr690/labs/Lab5.pdf