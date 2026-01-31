< Data Correction & Cleaning >

Error Corrections
1.purpose column
Fixed scanning errors:
SB → SE
Corrected duplicated / inverted values:
PNE/WR → WR/PNE
SE/WR → WR/SE
WE/WR → WR/WE
FMS/WR → WR/FMS
2.type column
Corrected inconsistent value:
WATER SU → WATERSUR

Format Changes
yield column
Replaced missing values with 0.
name column
Replaced empty cells with "UNKNOWN".
purpose column
Replaced empty cells with "UNKNOWN".
date_long colomn
Date formatting
Converted dates to European format (DD/MM/YYYY) and stored them in a new column date_DMY.

< Modified by Palladino Giovanni and Yang Siyu >
