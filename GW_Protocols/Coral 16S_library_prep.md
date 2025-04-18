**NOTE**: adapted from: [SOP_MDE_Metabarcoding Standard Genetic Methods (November2021).pdf](https://github.com/SERCCoastalDisease/Protocols/blob/main/SOP_MDE_Metabarcoding%20Standard%20Genetic%20Methods%20(November2021).pdf)

**NOTE**: all calculations can be done here: https://docs.google.com/spreadsheets/d/1l1ROib1xUoKOvusw5yShw5e5KsiRvz8F_r2zNBwmhAM/edit#gid=0


#### I. PCR
- **Repeat 3x for all samples that are to be included in the metabarcode library**
- *always include water (negative control - indication of no contamination) and very dilute positive controls (1-5ng of DNA) in every experiment*
- **Mix the following agents via vortex:** Buffer, MgCl2, primers
- **DO NOT vortex:** BSA or Hot Start Polymerase
	-  Polymerase should *never* be left at room temperature - **stays in freezer or in freezer box**
- use aliquoted reagents (limits contamination)
- **all PCR prep is done in the bench top hood in the lab***

copy & paste table off of mm_calculations, note which primer you are using each day (0N,1N...)

| Reagent              | Amount per 1 rxn | MasterMix Amount | # Samples | Triplicate |
| -------------------- | ---------------- | ---------------- | --------- | ---------- |
| Buffer               | 2.5              |                  |           |            |
| dNTP (10mM)          | 0.5              |                  |           |            |
| MgCl2                | 1.5              |                  |           |            |
| F Primer (10uM)      | 1                |                  |           |            |
| R Primer (10uM)      | 1                |                  |           |            |
| DNA                  | 1                |                  |           |            |
| Hot Start Polymerase | 0.125            |                  |           |            |
| Water                | 17.125           |                  |           |            |
| BSA                  | 0.25             |                  |           |            |
*taken from Sarah's evernote 02/02/21 16S*
**if using Q5 buffer reassess if I need MgCl**

1. Create master mix for each sample
2. Pipette 24uL of master mix into each replicate tube (3 replicates per sample)
3. Pipette 1uL of DNA into each replicate tube
	1. use new pipette tip for each replicate
4. Run thermocycler program:
	1. 95C for 10 mins
	2. **28 cycles** (reduced from 30 cycles to ) of:  
		1. 95C for 15 seconds
		2. 50C for 1 minute
		3. 72C for 1 minute
	3. 72C for 10 mins (extension)
### **ALL POST-PCR DONE IN OTHER ROOM (aka the rest of this protocol)**

#### II. Gel electrophoresis
- **always use standard DNA ladder on every row of gel**, can dilute ladder to 1:5 in order to see relatively brighter bands

- TBE Buffer 'Recipe' https://github.com/jgmcdonough/GW-lab-notebook/blob/main/Protocols/TBE%20Buffer%20Protocol.md

**Making and setting up a gel:**
1. mix agar and clean TBE buffer to generate a 1.5% agarose gel that will be large enough 
2. calculating gel density:
	- % = weight (g) / volume (mL)
3. melt mixture (on hot plate with stir bar or microwave) until mixture has big bubbles and there's no floaters
	-  **add GelRed to gel once cool** (if you don't, you won't see your bands!!)
	- do not pour into gel rig until flask is cool to touch
4. Add gel comb for number of samples you need
	- pour gel into the middle of mold and wait for even dispersion
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

#### III. PCR Pooling
1. using gel images - compare relative brightness of each band for sample replication across all 3 replicates
2. based on comparison - write out required volume to be pooled from each replicate
	 - band brightness generally has 3 levels: bright, faint, absent
	 - when **all bands have the same brightness** (regardless of level): take 5uL from each replicate
		1. Ex. R1 = Bright (5uL), R2 = Bright (5uL), R3 = Bright (5uL)
		2. Ex. R1 = absent (5uL), R2 = absent (5uL), R3 = absent (5uL)
	 - when **all bands are not equal brightness**, then take 10uL from the fainter replicates and pool with 5uL from the bright replicates
		1. Ex. R1 = faint (5uL), R2 = absent (10uL), R3 = absent (10uL)
3. obtain, label, cross-link new strip tubes - appropriate volumes from all 3 replicates are put in the same tube

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
start with the manufacturer protocol using 1.8X-1.5X bead ratio and 10uL PCR product
make fresh 80% ethanol in a 50mL tube (label and parafilm when not in use)
	 *may need to re-clean samples if gel images show that multiple bands were not removed*
1. Determine whether or not a plate transfer is necessary. If the PCR reaction volume multiplied by 2.8 exceeds the volume of the PCR plate, a transfer to larger tubes is required.
2. Gently shake the AxyPrep Mag PCR Clean-up bottle to resuspend any Magnetic particles that may have settled. 
Add  AxyPrep Mag PCR Clean-up according to the PCR reaction volume table below: 
	PCR Reaction Volume L) AxyPrep Mag PCR Clean-up Volume at 1.8X ( L) 10 18 20 36 50 90 
	
Note: The volume of AxyPrep Mag PCR Clean-up for a given reaction can be determined from the following equation:  

	(Volume of AxyPrep Mag PCR Clean-up per reaction) = 1.8 x (PCR Reaction Volume)
	
3. Mix reagent and PCR reaction thoroughly by pipette mixing 5 times.
4. Incubate the mixed samples for 5 minutes at room temperature for maximum recovery. This step allows the binding of PCR products 125bp and greater to the Magnetic beads.  After mixing, the color of the mixture should appear homogenous.
5. Place the reaction plate onto a 96 well Magnet Plate for 3 minutes or wait until the solution is clear.  Wait until the solution is clear before proceeding to the next washing step. Otherwise there may be beads loss.
6. Aspirate the cleared solution from the reaction plate and discard This step must be performed while the reaction plate is placed on the 96 Magnet Plate. Avoid disturbing the settled Magnetic beads. If beads are drawn into tips, leave behind a few microliters of solution.
7. Dispense **180 uL of 80% ethanol** to each well of the reaction plate and incubate for **1 min** at room temperature.  Aspirate out the ethanol and discard.  Repeat for a total of two washes.  It is important to perform these steps with the reaction plate on a 96 well Magnetic Plate. Do not disturb the settled Magnetic beads. Remove all of the ethanol from the bottom of the well to avoid ethanol carryover.  NOTE: A 5 min air dry at room temperature is recommended for the evaporation of the remaining traces of ethanol. Do not overdry the beads (the layer of settled beads appears cracked) as this will significantly decrease elution efficiency.
8. Take off the plate from the Magnetic plate, add 40 uL of elution buffer (Reagent grade water, TRIS-HCl pH 8.0, or TE buffer) to each well of the reaction plate and pipette mix 5 times. 
	1. look at tubes to make sure no beads on wall
9. Incubate at room temperature for 10 minutes. 
10. Place the plate on a magnetic separation device to magnetize the CleanNGS particles. Incubate at room temperature until the CleanNGS particles are completely cleared from solution. 
11. Transfer the cleared supernatant containing purified DNA and/or RNA to a new (RNase-free) 96-well microplate and seal with non-permeable sealing film. 
12. Store the plate at 2-8°C if storage is only for a few days. For long-term storage, samples should be kept at -20°C.

#### **VII. Gel electrophoresis**

Pool all indexed 

Gel purification for pooled 

qubit to figure out the molarity
