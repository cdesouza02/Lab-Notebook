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

#### I. PCR

| Reagent         | Amount per 1 rxn (uL) | MasterMix Amount (uL) + 10% | Triplicate (uL) + 10% |
| --------------- | --------------------- | --------------------------- | --------------------- |
| Buffer          | 5                     | 0                           | 0                     |
| dNTP (10mM)     | 0.5                   | 0                           | 0                     |
| F Primer (10uM) | 1                     | 0                           | 0                     |
| R Primer (10uM) | 1                     | 0                           | 0                     |
| DNA             | 1                     | 0                           | 0                     |
| Polymerase      | 0.25                  | 0                           | 0                     |
| Water           | 16                    | 0                           | 0                     |
| Albumin         | 0.25                  | 0                           | 0                     |
| Total           | 25                    | 0                           | 0                     |
1. Create master mix for each sample
	1. after adding Buffer, dNTP, and Primers vortex master mix
	2. DO NOT vortex polymerase or albumin, pipette up and down to mix
2. Pipette 24uL of master mix into each replicate tube (3 replicates per sample)
3. Pipette 1uL of DNA into each replicate tube
	1. use new pipette tip for each replicate
4. briefly centrifuge pcr tubes before thermal cycler
5. run thermocycler program:
	1. 98 for 30 sec
	2. **98 for 10 sec**
	3. **69 for 30 sec**
	4. **72 for 20 sec** 
	*repeat 2-4 for 28 cycles (# of cycles varies depending on input)*
	5. 72 for 2 min
	6. 8 for Forever
	

### **ALL POST-PCR DONE IN OTHER ROOM (aka the rest of this protocol)**

#### II. Gel electrophoresis
- **always use standard DNA ladder on every row of gel**, can dilute ladder to 1:5 in order to see relatively brighter bands

- TBE Buffer 'Recipe' https://github.com/jgmcdonough/GW-lab-notebook/blob/main/Protocols/TBE%20Buffer%20Protocol.md

**Making and setting up a gel:**
1. mix agar and clean TBE buffer to generate a 1.5% agarose gel that will be large enough for the gel mold
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

#### **VI. Purification with ampure beads**
obtain, label, and cross-link new strip tubes
start with the manufacturer protocol using 1.8X-1.0X bead ratio and 10uL-25uL PCR product
- ratio of beads will change the size you select for 
	*1.0x will get rid of <200 bp dimers, 1.8X will get rid of dimer <100 bp*

make fresh 80% ethanol in a 50mL tube (label and parafilm when not in use)
	 *may need to re-clean samples if gel images show that multiple bands were not removed*
	
| total volume ml |     |
| --------------- | --- |
| volume EtOH     |     |
| Volume H2O      |     |

1. Determine whether or not a plate transfer is necessary. If the PCR reaction volume multiplied by 2.8 exceeds the volume of the PCR plate, a transfer to larger tubes is required.
2. Gently shake the Clean NGS Mag PCR Clean-up aliquot to resuspend any Magnetic particles that may have settled. 
	1. Add CleanNGS Mag PCR Clean-up according to the PCR reaction volume table below: 

| Bead Volume         |     |               |                   |
| ------------------- | --- | ------------- | ----------------- |
| final concentration | 1.0 |               |                   |
| PCR volume          |     | total samples | Total bead volume |
| Added Beads         |     | 96            |                   |
	
Note: The volume of CleanNGS Mag PCR Clean-up for a given reaction can be determined from the following equation:  

	(Volume of Mag Beads per reaction) = 1.0 x (PCR Reaction Volume)
	
3. Mix reagent and PCR reaction thoroughly by pipette mixing 5 times.
4. Incubate the mixed samples for 5 minutes at room temperature for maximum recovery. This step allows the binding of PCR products 125bp (based on concentration) and greater to the Magnetic beads.  After mixing, the color of the mixture should appear homogenous.
5. Place the reaction plate onto a 96 well Magnet Plate for 3 minutes or wait until the solution is clear.  Wait until the solution is clear before proceeding to the next washing step. Otherwise there may be beads loss.
6. Aspirate the cleared solution from the reaction plate and discard This step must be performed while the reaction plate is placed on the 96 Magnet Plate. Avoid disturbing the settled Magnetic beads. If beads are drawn into tips, leave behind a few microliters of solution.
7. Dispense **180 uL of 80% ethanol** to each well of the reaction plate and incubate for **1 min** at room temperature.  Aspirate out the ethanol and discard.  Repeat for a total of two washes.  It is important to perform these steps with the reaction plate on a 96 well Magnetic Plate. Do not disturb the settled Magnetic beads. 
	1. Remove all of the ethanol from the bottom of the well to avoid ethanol carryover. **Bump pipette tip up to 200 uL, may need to use p20 multichannel** 
	2. NOTE: A 5 min air dry at room temperature is recommended for the evaporation of the remaining traces of ethanol. Do not overdry the beads (the layer of settled beads appears cracked) as this will significantly decrease elution efficiency.

8. Take off the plate from the Magnetic plate, add 40 uL of elution buffer (Reagent grade water, TRIS-HCl pH 8.0, or TE buffer) to each well of the reaction plate and pipette mix 5 times. 
	1. look at tubes to make sure no beads on wall
9. Incubate at room temperature for 10 minutes. 
10. Place the plate on a magnetic separation device to magnetize the CleanNGS particles. Incubate at room temperature until the CleanNGS particles are completely cleared from solution. 
11. Transfer the cleared supernatant containing purified DNA and/or RNA to a new (RNase-free) 96-well microplate and seal with non-permeable sealing film. 
12. Store the plate at 2-8°C if storage is only for a few days. For long-term storage, samples should be kept at -20°C.

#### **VII. Gel electrophoresis**

Quibit to figure out the concentration of each sample
 
 Pool all indexed according to concentration

Gel purification for pooled 

qubit to figure out the molarity
