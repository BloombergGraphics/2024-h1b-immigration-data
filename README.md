# US H-1B Visa Lottery and Petition Data FY 2021 - FY 2024

Bloomberg News obtained data on all H-1B lottery registrations, selections, and petitions for fiscal years 2021 through 2024 after bringing a lawsuit against the Department of Homeland Security under the Freedom of Information Act. 

You can use this repository to reproduce findings featured in our story "[Thousands of US Work Visas Are Going to Middlemen Gaming the System](LINK)". Our methodology is described at the bottom of the article. 

This data was produced by the U.S. Citizenship and Immigration Services, an agency under DHS tasked with adjudicating H-1B petitions. Every April, the USCIS conducts a random lottery to determine which H-1B seekers can submit full visa petitions. 

Each row in the data represents a lottery registration, which may or may not correspond to a unique individual because each candidate can have multiple registrations submitted by different employers. Once selected, the employer can submit an H-1B petition on behalf of the beneficiary. In case of a visa petition, the data includes more information about the proposed job, including salary, location, etc. 

An approved H-1B petition is necessary for, but does not always result in, an H-1B visa, which is a travel document. After an applicant receives an H-1B approval from the USCIS, they can apply for either an H-1B visa at a US Consulate abroad or an Adjustment of Status with the USCIS if they're already in the US.

```

| file | description |
| ------------------------------------------------------------------- | ------------------------------------------------------------ |
| `TRK_13139_I129_H1B_Registrations_FY21_FY24_FOIA_FIN.xlsx` | Data Dictionary |
| `TRK_13139_FY2021.csv` | FY 2021 data (April 2020 lottery) |
| `TRK_13139_FY2022.csv` | FY 2022 data (April 2021 lottery) |
| `TRK_13139_FY2023.csv` | FY 2023 data (April 2022 lottery) |
| `TRK_13139_FY2024_single_reg.csv` | FY 2024 data (April 2023 lottery), single registrations |
| `TRK_13139_FY2024_multi_reg.csv` | FY 2024 data (April 2023 lottery), multiple registrations |

```
Please cite the data as sourced from USCIS and obtained by Bloomberg. Email Bloomberg reporter Eric Fan at `xfan134@bloomberg.net` if you have any questions.