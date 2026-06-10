Ho: bleaching and disease have no effect on changes in the coral host microbiome

- Kira recommended against psba next gen as there isn’t a universal primer across genera that works.
	- instead use sanger sequencing to sequence psba products
- caleb
	- lot of inter-generic variation (Senjie Lin has done papers on this, among others)
	- makes it difficult to compare abundance of species using ITS2
	- **Lajuenesse 2022** shows sequencing quality of course affects what gets amplified and shown in the resulting data, and that there's a significant margin of error in the arrangement of the ordering of the ITS2 variants in abundances even when working on the same symbiont lineage.
	- **idea** no one has examined background microbiome contaminants in the water column
	- **sequencing depth of ITS2 20-50K**
	- "universal" Durusdinium psba is commonly used for genus breviolum common in carribean
- sarah davies
	- pool ~120 ITS2 samples in a lane of miseq in a 1:3 concentration ratio with 16S
	- pool 1:3 based on molarity of the separate pools
- andrea suggestions
	- repeated measures for time series 
	- look at agricultural microbiome work for ideas on how to analyze time series 
		- bovine gut microbiome
	- other paper looking at oyster C virginica throughout experiment

**questions I have**
- are coral microbiomes different from their environment
	- they ingest symbionts, can do they choose?
- are coral microbiomes dictated by geographic location
- have coral microbiomes changed over time?
	- have they changed similarly throughout Belize
	- have their been differences during multistressor events
	- how do they cluster based on species and site

## ITS2 protocol notes

- [ ] ITS2 protocol (wed)
	- Mutualistic dinofagellates with big disparities in ribosomal DNA variation may confound estimates of symbiont diversity and ecology in the jellyfsh Cotylorhiza tuberculata

**Lajueness 2022** 
**(this MM will change because not using )**
25 uL final volume
5x High Fidelity Fusion RXN buffer, 0.02 uL phusion DNA polymerase
0.5 ng (2.5 uL) extracted DNA
0.5 uM each primer
3% DMSO??
200 uM dNTPs
Amplification was achieved using with an initial denaturation step at 98 °C for 30s, followed by 38 cycles including 10 s at 98 °C, 30 s of annealing at 57 °C, 30 s of elongation at 72 °C, and a final elongation step of 10 min at 72 °C

**Hume 2013**
50 uL final volume
0.5 Advantage 2 polymerase mix
200 uM dNTP
0.5 primer
50 ng DNA
The PCR encompassed an initial denaturation step of 1 min at 98 °C followed by 35 cycles of denaturation (95 °C/30 s), annealing (62 °C/30 s), and elongation (68 °C/1 min). A final elongation step of 2 min was performed at 68 °C.
## ITS2 PCR Questions
1. NEB recommends 1.25 uL primer, should I try 1 uL to save (primer dimer with 1.25 also migth be excessive)
	1. yes
2. Lajueness used 0.5 ng (2.5 uL) extracted dna. does this mean his concentrations were around 0.2? ours are better than that. if so I think we can standardize 1 ul of dna 
	1. Q5 requires DNA template of 1ng-1ug
	2. **start with 1 uL for annealing gradient** if any problems standardize with super low/high concentrations
3. start with 30 cycles?  lajueness 38 cycles, Hume did 35 cycles because of the primers they were using?
	1. yes
4. start with testing out the use of albumin?
	1. yes