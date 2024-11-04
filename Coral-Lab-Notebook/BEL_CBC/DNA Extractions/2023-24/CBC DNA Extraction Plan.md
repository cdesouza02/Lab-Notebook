Goal: identify how symbiont communities change over time in different colonies
		colonies that got diseased, died from disease, bleached and recovered, died from bleaching, and stayed healthy throughout 
		how symbionts themselves change over time
	using MCAV and PSTR samples since 2019\
	
**Oct 29 meeting w/ Sarah** 
total exractions left to do ~260
	may be fewer depending on the recent Thijs extraction tubes that Brooke found 
if you want to see diseased and diseased tissue look at immune_samples_all.csv
confirm that rapid colonies only became diseased in 22024
- extractions from 260 extractions Nov 4-Dec 6
- pcr practice Dec 9-12

**calculation of Molarity**
concentration of DNA times size of dna fragment (from gel)
Oct 15-19
- Look at coral ribosomal internal transcribed spacer 2 (ITS2) metabarcoding studies and see methods number of reads per sample and or depth of sequencing
	symportal 
- **pull out april2024 data because it is for historical data??** **012024 added new transects** 

|                   |             |                 |                       |       |       |       |       |       |       |        |        |        |        |
| ----------------- | ----------- | --------------- | --------------------- | ----- | ----- | ----- | ----- | ----- | ----- | ------ | ------ | ------ | ------ |
| **Health_status** | **Species** | **Total_Count** | **Unextracted_Count** |       |       |       |       |       |       |        |        |        |        |
| Diseased_Margin   | MCAV        | 3               | 3                     |       |       |       |       |       |       |        |        |        |        |
| Diseased_Margin   | OANN        | 3               | 2                     |       |       |       |       |       |       |        |        |        |        |
| Diseased_Margin   | OFAV        | 0               | NA                    |       |       |       |       |       |       |        |        |        |        |
| Diseased_Margin   | PAST        | 1               | 1                     |       |       |       |       |       |       |        |        |        |        |
| Diseased_Margin   | PSTR        | 2               | 1                     |       |       |       |       |       |       |        |        |        |        |
| Diseased_Margin   | SSID        | 16              | 16                    |       |       |       |       |       |       |        |        |        |        |
| Diseased_Tissue   | MCAV        | 3               | 3                     |       |       |       |       |       |       |        |        |        |        |
| Diseased_Tissue   | OANN        | 3               | 2                     |       |       |       |       |       |       |        |        |        |        |
| Diseased_Tissue   | OFAV        | 0               | NA                    |       |       |       |       |       |       |        |        |        |        |
| Diseased_Tissue   | PAST        | 1               | 1                     |       |       |       |       |       |       |        |        |        |        |
| Diseased_Tissue   | PSTR        | 2               | 1                     |       |       |       |       |       |       |        |        |        |        |
| Diseased_Tissue   | SSID        | 21              | 21                    |       |       |       |       |       |       |        |        |        |        |
| Healthy           | MCAV        | 106             | 98                    |       |       |       |       |       |       |        |        |        |        |
| Healthy           | OANN        | 22              | 20                    |       |       |       |       |       |       |        |        |        |        |
| Healthy           | OFAV        | 53              | 45                    |       |       |       |       |       |       |        |        |        |        |
| Healthy           | PAST        | 80              | 70                    |       |       |       |       |       |       |        |        |        |        |
| Healthy           | PSTR        | 58              | 53                    |       |       |       |       |       |       |        |        |        |        |
| Healthy           | SSID        | 68              | 67                    |       |       |       |       |       |       |        |        |        |        |
|                   |             | 442             | 404                   |       |       |       |       |       |       |        |        |        |        |
|                   |             |                 |                       |       |       |       |       |       |       |        |        |        |        |
real unextracted is less than 404, I just have to put in the extraction_physical_locations for the extractions ive done/ make sure they are updated

RAPID Colonies
filter out immune yes colonies from CBC_ColonyData combine with CBC_Samples 
- is there anyway to color code the samples that have already been extracted?
- how to populate NA on the cells that are missing a sample (not_visited)

CODE
CBC_colonydata
filter "y" CBC_colonydat$Immune



| Species_Transect_Tag | 2019      | 052022 | 122022 | ... 12 time points |     |
| -------------------- | --------- | ------ | ------ | ------------------ | --- |
| PAST_T1_2            | SampleNum |        |        |                    |     |
| ...36 colonies       |           |        |        |                    |     |

| 2     | PAST |
| ----- | ---- |
| 3     | SSID |
| 12    | PSTR |
| 24    | MCAV |
| 99    | SSID |
| 55    | MCAV |
| 57    | PAST |
| 60    | MCAV |
| 63    | PAST |
| 68    | PAST |
| 69    | MCAV |
| 72    | SSID |
| 72    | SSID |
| 73    | SSID |
| 76    | OFAV |
| 79    | OFAV |
| 2     | MCAV |
| 2     | MCAV |
| 5     | SSID |
| 10    | PAST |
| 14    | MCAV |
| 20    | PSTR |
| 21    | MCAV |
| 33    | SSID |
| 34    | PAST |
| 38    | OFAV |
| 39    | OFAV |
| 70    | PSTR |
| 66/41 | OFAV |
| 28    | MCAV |
| 30    | MCAV |
| 76    | MCAV |
| 78    | OFAV |
| 79    | PSTR |
| 98    | PSTR |
| 25    | OANN |

**SCTLD Meeting Notes Oct 10**
- just focus on 36 rapid corals since 2019 
	PAST, SSID, PSTR, MCAV, OFAV(maybe)
- positive control  in the lane to normalize the concentrations of symbiont
- randomized order of extraction
- include some of 2019 suseptible, but only the rapid colonies 
- Where to sequence? argonne or utaustin or smithsonian 


|        | Healthy | Diseased_Tissue | Diseased_Margin |
| ------ | ------- | --------------- | --------------- |
| 092023 | 64      | 19              | 26              |
| 112023 | 36      | 0               | 0               |
| 122023 | 36      | 0               | 0               |
| 012024 | 69      | 0               | 0               |
| 022024 | 32      | 2               | 2               |
| 042024 | 126     | 15              | 18              |
| 062024 | 31      | 4               | 2               |
| 082024 | 34      | 0               | 0               |
|        | 428     | 40              | 48              |


16S 100 samples will all go on one run, so **organize by species?** all in one run? one lane?


| Health_Status   | Species  | Total_Count |
| --------------- | -------- | ----------- |
| Diseased Margin | DLAB     | 1           |
| Diseased Margin | MCAV     | 2           |
| Diseased Margin | ORBI     | 8           |
| Diseased Margin | PSTR     | 3           |
| Diseased Margin | SSID     | 34          |
| Diseased Tissue | DLAB     | 1           |
| Diseased Tissue | MCAV     | 2           |
| Diseased Tissue | ORBI     | 10          |
| Diseased Tissue | PSTR     | 3           |
| Diseased Tissue | SSID     | 24          |
| Healthy         | CNAT     | 1           |
| Healthy         | DLAB     | 15          |
| **Healthy**     | **MCAV** | **102**     |
| Healthy         | ORBI     | 107         |
| Healthy         | PAST     | 80          |
| Healthy         | PSTR     | 62          |
| Healthy         | SSID     | 61          |
Week of October 15
	diseased margin DNA extractions?? prioritize ssids since they have the most diseased margin?

|                 |         |       |       |       |       |       |       |        |        |
| --------------- | ------- | ----- | ----- | ----- | ----- | ----- | ----- | ------ | ------ |
| Health_Status   | Species | 12024 | 22024 | 42024 | 62024 | 82024 | 92023 | 112023 | 122023 |
| Diseased Margin | DLAB    | 0     | 0     | 0     | 0     | 0     | 1     | 0      | 0      |
| Diseased Margin | MCAV    | 0     | 1     | 0     | 1     | 0     | 0     | 0      | 0      |
| Diseased Margin | ORBI    | 0     | 0     | 0     | 0     | 0     | 8     | 0      | 0      |
| Diseased Margin | PSTR    | 0     | 0     | 2     | 0     | 0     | 1     | 0      | 0      |
| Diseased Margin | SSID    | 0     | 1     | 16    | 1     | 0     | 16    | 0      | 0      |
| Diseased Tissue | DLAB    | 0     | 0     | 0     | 0     | 0     | 1     | 0      | 0      |
| Diseased Tissue | MCAV    | 0     | 1     | 0     | 1     | 0     | 0     | 0      | 0      |
| Diseased Tissue | ORBI    | 0     | 0     | 2     | 0     | 0     | 8     | 0      | 0      |
| Diseased Tissue | PSTR    | 0     | 0     | 2     | 0     | 0     | 1     | 0      | 0      |
| Diseased Tissue | SSID    | 0     | 1     | 11    | 3     | 0     | 9     | 0      | 0      |
| Healthy         | CNAT    | 0     | 0     | 0     | 0     | 0     | 1     | 0      | 0      |
| Healthy         | DLAB    | 0     | 0     | 8     | 0     | 0     | 7     | 0      | 0      |
| Healthy         | MCAV    | 15    | 9     | 25    | 9     | 10    | 14    | 10     | 10     |
| Healthy         | ORBI    | 20    | 7     | 41    | 7     | 7     | 11    | 7      | 7      |
| Healthy         | PAST    | 11    | 6     | 19    | 7     | 6     | 15    | 8      | 8      |
| Healthy         | PSTR    | 11    | 5     | 18    | 5     | 5     | 8     | 5      | 5      |
| Healthy         | SSID    | 12    | 5     | 15    | 3     | 6     | 8     | 6      | 6      |














