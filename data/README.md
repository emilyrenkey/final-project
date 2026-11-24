# Menu data

Keep the file(s) you use and delete the rest. If you bring your own data,
describe them here the same way: source, license, what one row is, column
meanings, units, and how missing values are coded. `NA` marks a missing value
in every file below. All of these data are CC0 (public domain).

## survdata.csv (annual information on birth, death, reproduction, etc for each individual in each colony)
9598 rows, one row is one individual in a given year
-year_uid: Combination of the year given data (such as age) was collected/calculated, with the uid of the individual
-uid: the unique identifier of a given marmot
-colony: The colony where the individual lived during that breeding season
-age: Calculated using the function 'fn_age', which returns an animals age in that year [@ybamaRmot]

Source: Martin and Blumstein (2026), the entire database is an R package 'ybamaRmot'. 
BibTeX keys: ybamaRmot

## allogroom_raw.csv (raw dataset on allogrooming behavior)
5627 rows; one row is one interaction. 
-year
-date
-col_area: the colony where the social interaction occurred
-uid_ini: the unique identifier of the marmot who initiated the allogrooming
-uid_rec: the unique identifier of the marmot who received the allogrooming
-interac_type: the type of social interaction that occurred; should all be allogrooming
-comments: any additional comments about the interaction

Source: Martin and Blumstein (2026), the entire database is an R package 'ybamaRmot'. 
BibTeX keys: ybamaRmot

## blood_raw.csv (raw dataset on blood smears)
2660 rows; each row is one individuals blood smear
*slides were scored by counting white blood cells until a total of 100 white blood cells were counted or until 30 min had passed, whichever occurred first
-date_time_uid: capture date, time, and unique identifier for the marmot captured (MMDDYYYY.HHMM.uid)
-neutrophils: Number of neutrophils counted on the slide
-lymphocytes: Number of lymphocytes counted on the slide
-eosinophils: Number of eosinophils counted on the slide
-monocytes: Number of monocytes counted on the slide
-basophils: Number of basophils counted on the slide
-trypanosomes: Number of trypanosome parasites counted on the slide

Source: Martin and Blumstein (2026), the entire database is an R package 'ybamaRmot'. 
BibTeX keys: ybamaRmot
