Samples 17,49

#### IV. Indexing PCR 
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

Master Mix
mm_calculations

| Lab-made master mix |                       |                             |
| ------------------- | --------------------- | --------------------------- |
| Reagent             | Amount per 1 rxn (uL) | MasterMix Amount (uL) + 10% |
| Buffer              | 5                     | 88                          |
| dNTP (10mM)         | 0.5                   | 8.8                         |
| DNA                 | 1                     | 17.6                        |
| Polymerase          | 0.25                  | 4.4                         |
| Water               | 15.25                 | 268.4                       |
| Total               | 22                    | 387.2                       |
adding primers to mastermix using multichannel pipette

|   |   |   |
|---|---|---|
|Index master mix rows (vertical)|||
|Reagent|MM amount|Divided by two (if needed)|
|Big master mix|24.2|12.1|
|N50xx index|2.2|1.1|
|Total|26.4|13.2|
||||
|Index master mix columns (horizontal)|||
|Reagent|Amount per 1 rxn (uL)|Divided by two (if needed)|
|Big master mix|96.8|48.4|
|N50xx index|8.8|4.4|
|Total|105.6|52.8|


##### Annealing Gradient
- Thermocycler splits the temperture range into 8 different temperatures this means when looking at the open thermocycler from a front view each samples should be in its own column.
- I don't have to utilize all 8 temperatures but in the older thermocycler (the one we use for indexing it automatically disperses the temperature range into all 8)


Thermocycler program:
1. 95 for 5 mins
2. **98 for 20 sec**
##### Annealing Gradient
3. **60-72 for 45 sec*
4. **72 for 45 sec** 
*repeat 2-4 for **7 cycles** (# of cycles varies depending on input)*
5. 72 for 5 min

##### 3/18/25

| GEL |       |     |     |     |     |     |     |
| --- | ----- | --- | --- | --- | --- | --- | --- |
| L   | 17p+i | A+B | C+D | E+F | G+H |     | L   |
| L   | 49p+i | A+B | C+D | E+F | G+H |     | L   |
![[mar192025.heic]]

best results at 62.8 degrees cel, but this gel only showed the primer dimer from first row