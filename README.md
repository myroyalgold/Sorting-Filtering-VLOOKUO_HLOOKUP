# Sorting-Filtering With VLOOKUP and HLOOKUP

##  Problem Objective: Use the VLOOKUP and HLOOKUP reference functions
##  Dataset Used for VLOOKUP: https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0130EN-SkillsNetwork/Hands-on%20Labs/Lab%206%20-%20Filtering%20and%20Sorting%20Data%20using%20Functions%20for%20Data%20Analysis/indian_startup_funding_Lab6.xlsx
## Daraset Used for HlOOKUP: https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0130EN-SkillsNetwork/Hands-on%20Labs/Lab%206%20-%20Filtering%20and%20Sorting%20Data%20using%20Functions%20for%20Data%20Analysis/Personal_Monthly_Expenditure_Lab6.xlsx

# Using the VLOOKUP and HLOOKUP Functions
### Task A: Use of VLOOKUP to look up data in a table organized vertically
- Upload and Open the dataset downloaded.
- In cell K2,L2,M2, type VLOOKUP, Startup Name, Amount in USD respectively.
- Select and copy cells from C9 to C15 and paste in cell L3.
- In cell M3, type =VLOOKUP(L3, C2:I113, 7, FALSE) and press Enter
   Formula: =VLOOKUP (value, table, col_index, [range_lookup]).
- Hover over the bottom-right corner of cell M3, and drag the Fill Handle down to the cell M9.
- Select cells from M3 to M9 and select Number Format>Currency.

### Task B: Use of HLOOKUP to look up data in a table organized horizontally  
- Upload and open the dataset for Hlookup
- In cell J2,K2,L2,M2, type HLOOKUP, Month, Food & Dining, Health & Fitness respectively.
- Select and copy cells from A10 to A12 and paste in cell K3.
- In cell L3, type =HLOOKUP(D1, A1:H14, 10, FALSE) and press Enter.
    Formula: =HLOOKUP (value, table, row_index, [range_lookup]).
- Hover over the bottom-right corner of cell L3, and drag the Fill Handle down to the cell L5.
- Select cells from L3 to L5 and select Number Format>Currency.
- In cell M3, type =HLOOKUP(G1, A1:H14, 10, FALSE) and press Enter.
- Hover over the bottom-right corner of cell M3, and drag the Fill Handle down to the cell M5.
- Select cells from M3 to M5 and select Number Format>Currency.
    
    
