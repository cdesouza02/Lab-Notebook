## Redo Samples
tried with 1 ul
1. 052022BELCBC_T3_19_MCAV (B32)
2. 52022BELCBCT3_13_MCAV (B35)
3. 52022BELCBCT3_8_PAST (B32)
4. 112023_BEL_CBC_T3_355 (B12)
5. 122023BELCBCT3526_SSID (B13)
6.  22024BelizeCBCT3851_PSTR (B13)

tried with 5 ul, newer versions worked but not older
1. 062019_BEL_CBC_T1_22_MCAV (penguin, B33)
2. 052022_BEL_CBC_T1_2_SSID (penguin, B33)


# I. What could be inhibiting my PCR? :')

## After 1st PCR (Jan 2 2025)
	note: I did one before this, but it was basically the same except I reduced the amount of PCR cycles from 30 to 28 and got the same results

| tubelabel_species         | row   | volume (ul) | concentration (ng/ul) | date_extracted | PCR worked | notes      |
| ------------------------- | ----- | ----------- | --------------------- | -------------- | ---------- | ---------- |
| 22024BelizeCBCT2_814_MCAV | 2-4   | 1           | 58.2                  | Nov 2024       | yes        |            |
| 062024_BELCBCT3_1433_PSTR | 5-7   | 1           | 18.6                  | Dec 2024       | yes        |            |
| 42024BELCBCT2_1144_MCAV   | 8-10  | 1           | 75.1                  | Dec 2024       | yes        |            |
| 052022BELCBC_T3_19_MCAV   | 11-13 | 1           | 17.4                  | 2022           | no         |            |
| 42024BELCBCT3_960_OFAV    | 16-18 | 1           | 31.8                  | Dec 2024       | yes?       | 2/3        |
| 52022BELCBCT3_13_MCAV     | 19-21 | 1           | 3                     | June 2022      | ?          | faint band |
| 52022BELCBCT3_8_PAST      | 21-24 | 1           | 4.032                 | 2022           | no         |            |
| neg                       | 25-27 | 1           | -                     | -              | yes        |            |

1. Already seeing issues with bands forming in some cases
	1. Believe that recently extracted samples are more successful
	2. also why are the triplicates not all at the same bp length
	3. yayy the negative control worked
	4.  **why was there a faint band for 052022_BEL_CBC_T3_13_MCAV (3 ng/ul) but not for 052022BELCBC_T3_19_MCAV (17.4 ng/ul)**
	
2. Duh
	1. higher concentration = more starting DNA in 1 ul. This is why the first triplicates has brighter bands than the second 58.2 ng/ul and 18.6 ng/ul respectively 
	2.  I should remeasure the 2022 concentrations that B hasn't remeasured yet
	
3. Potential solution: 
	1. use more starting DNA 
	2. Test out using 5 ul & 10 ul of starting DNA on accidental extractions/ duplicates

## After 2nd PCR (Jan 22 2025)
| tubelabel_species              | row      | volume (ul) | concentration (ng/ul) | date_extracted | PCR worked | notes                              |
| ------------------------------ | -------- | ----------- | --------------------- | -------------- | ---------- | ---------------------------------- |
| **092023_BEL_CBC_T1_175_PAST** | 1,2,3    | 5           | 0.14                  | Nov 2024       | Yes        | Extracted by C low conc.           |
| 092023_BEL_CBC_T1_175_PAST     | 4,5,6    | 10          | 2.3                   | Jan 2025       | Yes        | Extracted by C to remedy low conc. |
| **062019_BEL_CBC_T1_22_MCAV**  | 7,8,9    | 5           | 34.2                  | Nov 2024       | Yes        | C accidentally reextracted         |
| 062019_BEL_CBC_T1_22_MCAV      | 10,11,12 | 5           | 6.67                  | 2022           | No         |                                    |
| **052022_BEL_CBC_T1_2_SSID**   | 13,14,15 | 10          | 7.73                  | Dec 2024       | Yes?       | debatable whether it worked        |
| 052022_BEL_CBC_T1_2_SSID       | 16,17,18 | 10          | **Nanodrop**          | 2022           | No         |                                    |
| **062019_BEL_CBC_T3_10_PAST**  | 19,20,21 | 5           | 2.25                  | Nov 2024       | Yes        | reextraction by B                  |
| 062019_BEL_CBC_T3_10_PAST      | 22,23,24 | 10          | 2.25                  | Nov 2024       | Yes        | reextraction by B                  |
1. AhHa
	1. yes more starting DNA helps a lot 
	2. even the faint bands weren't as faint as the ones from 1.2.2025
	3. can tell that the ones extracted in 2022 did not work, while 2024 extractions of the same samples worked better 
	4. using 5 ul starting DNA, can visualize bands where the initial concentration was as low as 0.14 ng/ul
	
2. Action items for tomorrow
	1. rePCR the ones that worked here using 1 ul of starting DNA to see if 1 ul would have worked
	2. PCR the next 7 samples in my randomized list because all of those have been extracted recently by me
	3. 
## After 3rd PCR (Jan 23 2025)

| tubelabel_species          | row   | volume (ul) | concentration (ng/ul)          | date_extracted | PCR worked | notes            |
| -------------------------- | ----- | ----------- | ------------------------------ | -------------- | ---------- | ---------------- |
| 112023BELCBC_T4_399_MCAV   | 1-3   | 1           | 13.9                           | Nov 2024       | yes        |                  |
| 112023BELCBC_T3_355_PSTR   | 4-6   | 1           | 1.27                           | Nov 2024       | ?          | 2/3 faint bands  |
| 122023BELCBC_T3_526_SSID   | 7-9   | 1           | 16.4                           | Nov 2024       | no         |                  |
| 82024BELCBC_T4_1609_OFAV   | 10-12 | 1           | 61.2                           | Jan 2025       | yes        |                  |
| 22024BelizeCBC_T3_851_PSTR | 13-15 | 1           | 64.2                           | Nov 2024       | ?          | 1/3 band         |
| 82024BELCBC_T3_1554_OANN   | 16-18 | 1           | **nanodrop (too high for HS)** | Jan 2025       | yes        |                  |
| 42024BELCBC_T2_1018_PAST   | 19-21 | 1           | 25.9                           | Dec 2024       | ?          | 3/3 double bands |
| Negative                   | 22-24 | 1           |                                |                | yes        |                  |
| 092023_BEL_CBC_T1_175_PAST | 25    | 1           | 0.14                           | Nov 2024       | ?          |                  |
| 062019_BEL_CBC_T3_10_PAST  | 26    | 1           | 2.25                           | Nov 2024       | no?        |                  |
| 062019_BEL_CBC_T1_22_MCAV  | 27    | 1           | 34.2                           | Dec 2024       | yes        | very faint band  |
| 052022_BEL_CBC_T1_2_SSID   | 28    | 1           | 7.73                           | Dec 2024       | no?        |                  |
Issues:
1. 1 ul is not very reliable, especially for the ones that worked at 5 ul 
2. **bright band for 112023BELCBC_T4_399_MCAV (13.9 ng/ul) but much more difficult to visualize 82024BELCBC_T4_1609_OFAV (61.2 ng/ul) & 22024BelizeCBC_T3_851_PSTR (64.2 ng/ul)**
3. what's up with the double bands in 42024BELCBC_T2_1018_PAST
4. also got double dimers going for most samples

Action items:
1. maybe there is a DNA ng (volume*concentration) threshold to be met?
	1. test out one sample from 1-5 ul?
2. 

# II. Simple Fool's Guide to PCR
low dna concentration? older samples? unexpected discrepancies in samples that are similar in age but different concentrations
