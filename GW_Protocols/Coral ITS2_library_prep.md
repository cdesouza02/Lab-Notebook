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
2. Lajueness used 0.5 ng (2.5 uL) extracted dna. does this mean his concentrations were around 0.2? ours are better than that. if so I think we can standardize 1 ul of dna 
	1. Q5 requires DNA template of 1ng-1ug
3. start with 30 cycles,  did lajueness 38 cycles, Hume did 35 cycles because of the primers they were using?
4. start with testing out the use of albumin?

#### I. PCR

| Reagent             | Amount per 1 rxn (uL) | MasterMix Amount (uL) + 10% | Triplicate (uL) + 10% |
| ------------------- | --------------------- | --------------------------- | --------------------- |
| Q5 Buffer           | 5                     |                             |                       |
| dNTP (10mM)         | 0.5                   |                             |                       |
| F Primer (10uM)     | 1.25                  |                             |                       |
| R Primer (10uM)     | 1.25                  |                             |                       |
| DNA                 | 1                     |                             |                       |
| HotStart Polymerase | 0.25                  |                             |                       |
| Water               | 15.5                  |                             |                       |
| Albumin             | 0.25                  |                             |                       |
| Total               | 25                    |                             |                       |
1. Create master mix for each sample
2. Pipette 24uL of master mix into each replicate tube (3 replicates per sample)
3. Pipette 1uL of DNA into each replicate tube
	1. use new pipette tip for each replicate
4. run thermocycler program:
	1. 98 for 30 sec
	2. **98 for 10 sec**
	3. **69 for 30 sec**
	4. **72 for 20 sec** 
	*repeat 2-4 for 30 cycles (# of cycles varies depending on input)*
	5. 72 for 2 min

### **ALL POST-PCR DONE IN OTHER ROOM (aka the rest of this protocol)**

#### II. Gel electrophoresis
- **always use standard DNA ladder on every row of gel**, can dilute ladder to 1:5 in order to see relatively brighter bands

- TBE Buffer 'Recipe' https://github.com/jgmcdonough/GW-lab-notebook/blob/main/Protocols/TBE%20Buffer%20Protocol.md

**Making and setting up a gel:**
1. mix agar and clean TBE buffer to generate a 2% agarose gel that will be large enough for the gel mold
	1. higher percentage because ITS2 region (220bp) is smaller than 16S V4 region (254bp)
2. calculating gel density:
	- % = weight (g) / volume (mL)
3. melt mixture (on hot plate with stir bar or microwave) until mixture has big bubbles and there's no floaters
	-  **add GelRed to gel once cool** (if you don't, you won't see your bands!!)
	- do not pour into gel rig until flask is cool to touch
4. Add gel comb for number of samples you need
	- pour gel into the middle of mold and wait for even dispersion
	- enough gel to see that the wells are in it, not too thick
5. let gel cool - wells will break if not cooled down enough
	- 20 mins to be safe
	- during this time set up for loading gel (step 6)
6. Sample Prep
	- cut enough parafilm for all samples + ladders
	- pipette up 20uL of loading dye and place 1-2ul dots of loading dye on the parafilm for each well
7. **turn rig so DNA will move towards the positive electrode** run towards red!
8. load 2-3uL of DNA ladder (can make 1:5 dilution with molecular water) at beginning or end (or both if large rig) of the gel, and on each row
9. load 1uL PCR product 
10. put cover on and turn on electric current - **run 110 volts for ~35 mins**
	- check to make sure bands aren't running off the gel
	- time length depends on the size of gel 30-50 mins 
11. turn off electric current *then* remove lid
12. take picture of gel and save where need
	- turn lights off in room, put gel on the glass and lift the cover (45 degrees) so that there is no reflection from the gel, take photo parallel to gel 
	- editing: crop to be centered, brightness -100
13. in some cases may run for longer to get more separation in bands 
14. you may reuse gels up to 3 times, if so break the gel up into a glass container that can be covered and store at 2-8 °C

#### III. PCR Pooling
1. using gel images - compare relative brightness of each band for sample replication across all 3 replicates
2. based on comparison - write out required volume to be pooled from each replicate
	 - band brightness generally has 3 levels: bright, faint, absent
	 - when **all bands have the same brightness** (regardless of level): take 5uL from each replicate
		1. Ex. R1 = Bright (5uL), R2 = Bright (5uL), R3 = Bright (5uL)
		2. Ex. R1 = absent (5uL), R2 = absent (5uL), R3 = absent (5uL)
	 - when **all bands are not equal brightness**, then take 10uL from the fainter replicates and pool with 5uL from the bright replicates
		1. Ex. R1 = faint (5uL), R2 = absent (10uL), R3 = absent (10uL)
3. obtain, label, cross-link new strip tubes (or plate) - appropriate volumes from all 3 replicates are put in the same tube

#### IV. Indexing PCR 
- each sample is indexed with a unique combination of i5 and i7 primers 

1. using HotStart reagents for this protocol using the following combination of reagents:
	- 1uL of pooled product as template in the indexing PCR
	- indexing PCR done in 25uL total reaction volume using NEB Q5 Hot Start High Fidelity Master Mix
2. Make master Mix
	- mm_calculations

**Steps:**
1. Use strip tubes to create a master mix for each i5 and i7 primer
2. use multi-channel pipette to dispense the master mixes into appropriate tube
	- add 12uL of each i5 and i7 master mix to each reaction tube - following the template to track the combination of barcodes used for each sample
	- 12uL i5 master mix + 12uL i7 master mix + 1uL template = 25uL total reaction
3. add DNA to individual reactions 
4. run thermocycler program
	1. 98 for 30 sec
	2. **98 for 10 sec**
	3. **67 for 30 sec**
	4. **72 for 20 sec** 
	*repeat 2-4 for 7 cycles (# of cycles varies depending on input)*
	5. 72 for 2 min

#### V. Gel electrophoresis
perform steps as above with one addition:
- for each row in the gel, **include both a ladder and a non-indexed control**
- pre- and post-indexed samples should be different sizes
- **1uL product used to load gel to check indexing**