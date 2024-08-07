------------------------------------------April 29 2024-----------------------------------------

**Making and setting up a gel:**

- mix agar and clean TBE buffer to generate a 2% agarose gel that will be large enough
- calculating gel density:
    - % = weight (g) / volume (mL)
- melt mixture (on hot plate with stir bar or microwave) until mixture has big bubbles and there's no floaters
    - do not pour into gel rig until flask is cool to touch
    - **add SyberSafe to gel once cool** (if you don't, you won't see your bands!!) (2 ul per 100 ml gel)
- Add gel comb for number of samples you need
    - pour gel until just underneath where the comb ends
- let gel cool - wells will break if not cooled down enough
- **turn rig so DNA will move towards the positive electrode (red)**
- load 2-3uL of DNA ladder (6X; 1:100 dilution) at beginning or end (or both if large rig) of the gel, and on each row
- load PCR product
- put cover on and turn on electric current - **run 90 volts for ~45 mins**
    - check to make sure bands aren't running off the gel
- turn off electric current _then_ remove lid
- take picture of gel and save where needed

| Tube # | Sample  | Replicate |
| ------ | ------- | --------- |
| 1      | R1      | 3         |
| 2      | R1      | 2         |
| 3      | R1      | 1         |
| 4      | M1      | 3         |
| 5      | M1      | 2         |
| 6      | M1      | 1         |
| 7      | K1      | 3         |
| 8      | K1      | 2         |
| 9      | K1      | 1         |
| 10     | G1      | 3         |
| 11     | G1      | 2         |
| 12     | G1      | 1         |
| 13     | E1      | 3         |
| 14     | E1      | 2         |
| 15     | E1      | 1         |
| 16     | C1      | 3         |
| 17     | C1      | 2         |
| 18     | C1      | 1         |
| 19     | neg (1) | 3         |
| 20     | neg (1) | 2         |
| 21     | neg (1) | 1         |
| Tube # | Sample  | Replicate |
| 22     | RA      | 3         |
| 23     | RA      | 2         |
| 24     | RA<br>  | 1         |
| 25     | MA      | 3         |
| 26     | MA      | 2         |
| 27     | MA      | 1         |
| 28     | KA      | 3         |
| 29     | KA      | 2         |
| 30     | KA      | 1         |
| 31     | GA      | 3         |
| 32     | GA      | 2         |
| 33     | GA      | 1         |
| 34     | EA      | 3         |
| 35     | EA      | 2         |
| 36     | EA      | 1         |
| 37     | CA      | 3         |
| 38     | CA      | 2         |
| 39     | CA      | 1         |
| 40     | neg (1) | 3         |
| 41     | neg (1) | 2         |
| 42     | neg (1) | 1         |
| Tube # | Sample  | Replicate |
| 43     | RP3     | 3         |
| 44     | RP3     | 2         |
| 45     | RP3     | 1         |
| 46     | MP3     | 3         |
| 47     | MP3     | 2         |
| 48     | MP3     | 1         |
| 49     | KP3     | 3         |
| 50     | KP3     | 2         |
| 51     | KP3     | 1         |
| 52     | GP3     | 3         |
| 53     | GP3     | 2         |
| 54     | GP3     | 1         |
| 55     | EP3     | 3         |
| 56     | EP3     | 2         |
| 57     | EP3     | 1         |
| 58     | CP3     | 3         |
| 59     | CP3     | 2         |
| 60     | CP3     | 1         |
|        |         |           |
------------------------------------------April 30 2024-----------------------------------------
#### I. PCR

[](https://github.com/GWLab-UML/Protocols/blob/main/16S_library_prep.md#i-pcr)

- **Repeat 3x for all samples that are to be included in the metabarcode library**
- _always include water (negative control - indication of no contamination) and very dilute positive controls (1-5ng of DNA) in every experiment_
- **Mix the following agents via vortex:** Buffer, MgCl2, primers
- **DO NOT vortex:** BSA or Taq
    - Taq should _never_ be left at room temperature - **stays in freezer or in freezer box**
- use aliquoted reagents (limits contamination)
- **all PCR prep is done in the bench top hood in the lab***

| Reagent         | Amount per 1 rxn (uL) | MasterMix Amount (uL) + 10% | Triplicate (uL) + 10% |
| --------------- | --------------------- | --------------------------- | --------------------- |
| Buffer          | 2.5                   | 57.75                       | 173.25                |
| dNTP (10mM)     | 0.5                   | 11.55                       | 34.65                 |
| MgCl2           | 1.5                   | 34.65                       | 103.95                |
| F Primer (10uM) | 1                     | 23.1                        | 69.3                  |
| R Primer (10uM) | 1                     | 23.1                        | 69.3                  |
| DNA             | 1                     | 23.1                        | 69.3                  |
| Polymerase      | 0.125                 | 2.8875                      | 8.6625                |
| Water           | 17.125                | 395.5875                    | 1186.7625             |
| Albumin         | 0.25                  | 5.775                       | 17.325                |
| Total           | 25                    | 577.5                       | 1732.5                |
**to dilute primers 10 ul stock primer 90 ul of water**

| For first PCR (adapters): | Pipette 24uL mastermix + 1uL DNA template to each well |     |
| ------------------------- | ------------------------------------------------------ | --- |
1. Create master mix for each sample
2. Pipette 25uL of master mix into each replicate tube (3 replicates per sample)
3. Run thermocycler program:
    1. 95C for 10 mins
    2. 35 cycles of:
        1. 95C for 15 seconds
        2. 50C for 1 minute
        3. 72C for 1 minute
    3. 72C for 10 mins (extension)
### **ALL POST-PCR DONE IN OTHER ROOM (aka the rest of this protocol)**

[](https://github.com/GWLab-UML/Protocols/blob/main/16S_library_prep.md#all-post-pcr-done-in-other-room-aka-the-rest-of-this-protocol)

#### II. Gel electrophoresis

#### III. PCR Pooling

[](https://github.com/GWLab-UML/Protocols/blob/main/16S_library_prep.md#iii-pcr-pooling)

1. using gel images - compare relative brightness of each band for sample replication across all 3 replicates
2. based on comparison - write out required volume to be pooled from each replicate
    1. band brightness generally has 3 levels: bright, faint, absent
    2. when **all bands have the same brightness** (regardless of level): take 5uL from each replicate
        1. Ex. R1 = Bright (5uL), R2 = Bright (5uL), R3 = Bright (5uL)
        2. Ex. R1 = absent (5uL), R2 = absent (5uL), R3 = absent (5uL)
    3. when **all bands are not equal brightness**, then take 10uL from the fainter replicates and pool with 5uL from the bright replicates
        1. Ex. R1 = faint (5uL), R2 = absent (10uL), R3 = absent (10uL)
3. obtain, label, cross-link new strip tubes - appropriate volumes from all 3 replicates are put in the same tube

| Pool Tube | Tube # | Sample  | Replicate | ul for pooling |
| --------- | ------ | ------- | --------- | -------------- |
| A         | 1      | R1      | 3         | 5              |
|           | 2      | R1      | 2         | 5              |
|           | 3      | R1      | 1         | 5              |
| B         | 4      | M1      | 3         | 10             |
|           | 5      | M1      | 2         | 10             |
|           | 6      | M1      | 1         | 5              |
| C         | 7      | K1      | 3         | 5              |
|           | 8      | K1      | 2         | 5              |
|           | 9      | K1      | 1         | 5              |
| D         | 10     | G1      | 3         | 5              |
|           | 11     | G1      | 2         | 5              |
|           | 12     | G1      | 1         | 10             |
| E         | 13     | E1      | 3         | 5              |
|           | 14     | E1      | 2         | 5              |
|           | 15     | E1      | 1         | 5              |
| F         | 16     | C1      | 3         | 5              |
|           | 17     | C1      | 2         | 5              |
|           | 18     | C1      | 1         | 5              |
| G         | 19     | neg (1) | 3         | 5              |
|           | 20     | neg (1) | 2         | 5              |
|           | 21     | neg (1) | 1         | 5              |
| H         | 22     | RA      | 3         | 10             |
|           | 23     | RA      | 2         | 5              |
|           | 24     | RA<br>  | 1         | 5              |
| I         | 25     | MA      | 3         | 10             |
|           | 26     | MA      | 2         | 10             |
|           | 27     | MA      | 1         | 5              |
| J         | 28     | KA      | 3         | 5              |
|           | 29     | KA      | 2         | 10             |
|           | 30     | KA      | 1         | 5              |
| K         | 31     | GA      | 3         | 10             |
|           | 32     | GA      | 2         | 10             |
|           | 33     | GA      | 1         | 5              |
| L         | 34     | EA      | 3         | 5              |
|           | 35     | EA      | 2         | 10             |
|           | 36     | EA      | 1         | 5              |
| M         | 37     | CA      | 3         | 5              |
|           | 38     | CA      | 2         | 10             |
|           | 39     | CA      | 1         | 5              |
| N         | 40     | neg (A) | 3         | 5              |
|           | 41     | neg (A) | 2         | 5              |
|           | 42     | neg (A) | 1         | 5              |
| O         | 43     | RP3     | 3         | 5              |
|           | 44     | RP3     | 2         | 5              |
|           | 45     | RP3     | 1         | 5              |
| P         | 46     | MP3     | 3         | 5              |
|           | 47     | MP3     | 2         | 5              |
|           | 48     | MP3     | 1         | 5              |
| Q         | 49     | KP3     | 3         | 5              |
|           | 50     | KP3     | 2         | 5              |
|           | 51     | KP3     | 1         | 5              |
| R         | 52     | GP3     | 3         | 5              |
|           | 53     | GP3     | 2         | 5              |
|           | 54     | GP3     | 1         | 5              |
| S         | 55     | EP3     | 3         | 5              |
|           | 56     | EP3     | 2         | 5              |
|           | 57     | EP3     | 1         | 5              |
| T         | 58     | CP3     | 3         | 5              |
|           | 59     | CP3     | 2         | 5              |
|           | 60     | CP3     | 1         | 5              |
| U         | 61     | neg(p3) | 3         | 5              |
|           | 62     | neg(p3) | 2         | 5              |
|           | 63     | neg(p3) | 1         | 5              |

------------------------------------------May 6 2024-----------------------------------------
#### IV. Indexing PCR

[](https://github.com/GWLab-UML/Protocols/blob/main/16S_library_prep.md#iv-indexing-pcr)

- each sample is indexed with a unique combination of i5 and i7 primers

using HotStart reagents for this protocol using the following combination of reagents:

- 1uL of pooled product as template in the indexing PCR
- indexing PCR done in 25uL total reaction volume using KAPA Ready Mix

**Steps:**

1. Use strip tubes to create a master mix for each i5 and i7 primer
2. use multi-channel pipette to dispense the master mixes into appropriate tube
    1. add 12uL of each i5 and i7 master mix to each reaction tube - following the template to track the combination of barcodes used for each sample
    2. 12uL i5 master mix + 12uL i7 master mix + 1uL template = 25uL total reaction
3. add DNA to individual reactions
4. run thermocycler program

PCR for indexing pooled products

  

| Reagent          | Amount per 1 rxn (uL) | MasterMix Amount (uL) + 10% | Done? |
| ---------------- | --------------------- | --------------------------- | ----- |
| Buffer           | 2.5                   | 57.75                       | x     |
| dNTP (10mM)      | 0.5                   | 11.55                       | x     |
| MgCl2            | 1.5                   | 34.65                       | x     |
| F Primer (10uM)  | 1                     | 23.1                        | -     |
| R Primer (10uM)  | 1                     | 23.1                        | -     |
| DNA              | 1                     | 23.1                        | -     |
| Polymerase       | 0.125                 | 2.8875                      | x     |
| Water            | 17.125                | 395.5875                    | x     |
| Albumin          | 0.25                  | 5.775                       | x     |
| indexing primers | 1                     |                             |       |

Indexing 

|        |     |      |      |      |
| ------ | --- | ---- | ---- | ---- |
| Group: | 0   | i7 - | i7 - | i7 - |
|        |     | 1    | 2    | 3    |
| i5 -   | A   | neg  | neg  | neg  |
| i5 -   | B   | R1   | RA   | RP3  |
| i5 -   | C   | M1   | MA   | MP3  |
| i5 -   | D   | K1   | KA   | KP3  |
| i5 -   | E   | G1   | GA   | GP3  |
| i5 -   | F   | C1   | CA   | CP3  |
| i5 -   | G   | E1   | EA   | EP3  |
| i5 -   | H   |      |      |      |

#### V. Gel electrophoresis

[](https://github.com/GWLab-UML/Protocols/blob/main/16S_library_prep.md#v-gel-electrophoresis)

perform steps as above with one addition:

- for each row in the gel, **include both a ladder and a non-indexed control**
- pre- and post-indexed samples should be different sizes
- **1uL product used to load gel to check indexing**
run 2% gel in 0.5xTBE - 90V for 40 mins - 100bp ladder with 3uL load - load indexed _and_ pooled pcr products (to be able to tell that something happened between steps - indexed should be longer than pooled products)

------------------------------------------May 8 2024-----------------------------------------
#### **VI. Purification with ampure beads**

[](https://github.com/GWLab-UML/Protocols/blob/main/16S_library_prep.md#vi-purification-with-ampure-beads)

obtain, label, and cross-link new strip tubes start with the manufacturer protocol using 1.8X-1.5X bead ratio and 10uL PCR product make fresh 70% ethanol in a 50mL tube (label and parafilm when not in use) _may need to re-clean samples if gel images show that multiple bands were not removed_1. Determine whether or not a plate transfer is necessary. If the PCR reaction volume multiplied by 2.8 exceeds the volume of the PCR plate, a transfer to larger tubes is required.
2. Gently shake the AxyPrep Mag PCR Clean-up bottle to resuspend any Magnetic particles that may have settled. Add AxyPrep Mag PCR Clean-up according to the PCR reaction volume table below: PCR Reaction Volume L) AxyPrep Mag PCR Clean-up Volume at 1.8X ( L) 10 18 20 36 50 90 Note: The volume of AxyPrep Mag PCR Clean-up for a given reaction can be determined from the following equation: (Volume of AxyPrep Mag PCR Clean-up per reaction) = 1.8 x (PCR Reaction Volume)
3. Mix reagent and PCR reaction thoroughly by pipette mixing 5 times.
4. Incubate the mixed samples for 5 minutes at room temperature for maximum recovery. This step allows the binding of PCR products 125bp and greater to the Magnetic beads. After mixing, the color of the mixture should appear homogenous.
5. Place the reaction plate onto a 96 well Magnet Plate for 3 minutes or wait until the solution is clear. Wait until the solution is clear before proceeding to the next washing step. Otherwise there may be beads loss.
6. Aspirate the cleared solution from the reaction plate and discard This step must be performed while the reaction plate is placed on the 96 Magnet Plate. Avoid disturbing the settled Magnetic beads. If beads are drawn into tips, leave behind a few microliters of solution.
7. Dispense 200 L of 70% ethanol to each well of the reaction plate and incubate for 30 seconds at room temperature. Aspirate out the ethanol and discard. Repeat for a total of two washes. It is important to perform these steps with the reaction plate on a 96 well Magnetic Plate. Do not disturb the settled Magnetic beads. Remove all of the ethanol from the bottom of the well to avoid ethanol carryover. NOTE: A 5 min air dry at room temperature is recommended for the evaporation of the remaining traces of ethanol. Do not overdry the beads (the layer of settled beads appears cracked) as this will significantly decrease elution efficiency.
8. Take off the plate from the Magnetic plate, add 40 uL of elution buffer (Reagent grade water, TRIS-HCl pH 8.0, or TE buffer) to each well of the reaction plate and pipette mix 5 times.

#### **VII. Gel electrophoresis**