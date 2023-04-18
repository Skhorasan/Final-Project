# Dataset Documentation 

This is the documentation of the dataset for the reference. 

| Variable | Name     | Column | Coding                                                                                                                                                                                    |
| -------- | -------- | ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1        | menopaus | 1      | 0 = premenopausal; 1 = postmenopausal or age>=55 ; 9 = unknown                                                                                                                            |
| 2        | agegrp   | 3-4    | Age group: 1 = 35-39; 2 = 40-44; 3 = 45-49; 4 = 50-54; 5 = 55-59; 6 = 60-64; 7 = 65-69; 8 = 70-74; 9 = 75-79; 10 = 80-84                                                                             |
| 3        | density  | 6      | BI-RADS breast density codes 1 = Almost entirely fat; 2 = Scattered fibroglandular densities; 3 = Heterogeneously dense; 4 = Extremely dense; 9 = Unknown or different measurement system |
| 4        | race     | 8      | 1 = white; 2 = Asian/Pacific Islander; 3 = black; 4 = Native American; 5 = other/mixed; 9 = unknown                                                                                       |
| 5        | Hispanic | 10     | 0 = no; 1 = yes; 9 = unknown                                                                                                                                                              |
| 6        | bmi      | 12     | Body mass index: 1 = 10-24.99; 2 = 25-29.99; 3 = 30-34.99; 4 = 35 or more; 9 = unknown                                                                                                    |
| 7        | agefirst | 14     | Age at first birth: 0 = Age < 30; 1 = Age 30 or greater; 2 = Nulliparous; 9 = unknown                                                                                                     |
| 8        | nrelbc   | 16     | Number of first degree relatives with breast cancer: 0 = zero; 1= one; 2 = 2 or more; 9 = unknown                                                                                         |
| 9        | brstproc | 18     | Previous breast procedure: 0 = no; 1 = yes; 9 = unknown                                                                                                                                   |
| 10       | lastmamm | 20     | Result of last mammogram before the index mammogram: 0 = negative; 1 = false positive; 9 = unknown                                                                                        |
| 11       | surgmeno | 22     | Surgical menopause: 0 = natural; 1 = surgical; 9 = unknown or not menopausal (menopaus=0 or menopaus=9)                                                                                   |
| 12       | hrt      | 24     | Current hormone therapy: 0 = no; 1 = yes; 9 = unknown or not menopausal (menopaus=0 or menopaus=9)                                                                                        |
| 13       | invasive | 26     | Diagnosis of invasive breast cancer within one year of the index screening mammogram: 0 = no; 1 = yes                                                                                     |
| 14       | cancer   | 28     | Diagnosis of invasive or ductal carcinoma in situ breast cancer within one year of the index screening mammogram: 0 = no; 1 = yes                                                         |
| 15       | training | 30     | Training data: 0 = no (validation); 1 = yes (training)                                                                                                                                    |
| 16       | count    | 32-37  | Frequency count of this combination of covariates and outcomes (all variables 1 to 15)                                                                                                    |
