# Acadia
Solutions


## Requirements

To run this code in Google Colab, you'll need to install the necessary libraries. Here's a list of the libraries used:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`


## How to Run the Code in Google Colab

### 1. Open Google Colab
Go to [Google Colab](https://colab.research.google.com/).

### 2. Upload the Required Files
Upload the ```acadia.ipynb``` and ```data.xlsx``` file.

### 3. Press ```F9``` to run the code.

## Ouput
The code when executed gives the answers as:
1. List down all the columns with missing values.
   ```Missing Values Analysis:
   {
     'STATE': 59, 'TENURE_IN_MONTHS': 66, 'CLOSESTSTOREDISTANCE': 1545, 'AGE': 5945, 'INCOME': 3259, 'LENGTH OF RESIDENCE': 2872, 'NUMBER OF PERSONS IN LIVING UNIT': 2872, 'NUMBER OF ADULTS IN LIVING UNIT': 2872, 'MOSAIC': 1868, 'CAPE: AGE: POP: MEDIAN AGE': 2872, 'CAPE: AGE: POP: % 0-17': 2872, 'CAPE: AGE: POP: % 18-99+': 2872, 'CAPE: AGE: POP: % 65-99+': 2872, 'CAPE: ETHNIC: POP: % WHITE ONLY': 2872, 'CAPE: ETHNIC: POP: % BLACK ONLY': 2872, 'CAPE: ETHNIC: POP: % ASIAN ONLY': 2872, 'CAPE: ETHNIC: POP: % HISPANIC': 2872, 'CAPE: DENSITY: PERSONS PER HH FOR POP IN HH': 2872, 'CAPE: HHSIZE: HH: AVERAGE HOUSEHOLD SIZE': 2872, 'CAPE: TYP: HH: % MARRIED COUPLE FAMILY': 2872, 'CAPE: CHILD: HH: % WITH PERSONS LT18': 2872, 'CAPE: CHILD: HH: % MARR COUPLE FAMW- PERSONS LT18': 2872, 'CAPE: CHILD: HH: % MARR COUPLE FAMW-O PERSONS LT18': 2872, 'CAPE: LANG: HH: % SPANISH SPEAKING': 2872, 'CAPE: EDUC: POP25+: MEDIAN EDUCATION ATTAINED': 2872, 'CAPE: HOMVAL: OOHU: MEDIAN HOME VALUE': 2872, 'CAPE: BUILT: HU: MEDIAN HOUSING UNIT AGE': 2872, 'CAPE: TENANCY: OCCHU: % OWNER OCCUPIED': 2872, 'CAPE: TENANCY: OCCHU: % RENTER OCCUPIED': 2872, 'CAPE: EDUC: ISPSA': 2872, 'CAPE: EDUC: ISPSA DECILE': 2872, 'CAPE: INC: FAMILY INC STATE DECILE': 2872, 'CAPE: INC: HH: MEDIAN FAMILY HOUSEHOLD INCOME': 2872
   }
2. Categotize the columns based upon their data type and print, for ex: print all the numeric variables and other data types as well.
   ```
   Column Categorization:
   {
     'Numeric': ['CUSTOMERID', 'LCPCOUNT', 'TENURE_IN_MONTHS', 'CLOSESTSTOREDISTANCE', 'FEMALE', 'AGE', 'HS_DIPLOMA', 'SOME_COLLEGE', 'BACH_GRAD_DEG', 'LT_HS_DIPLOMA', 'MARRIED', 'MNGMNT_OFFICEADMIN', 'TECH_PROF', 'SALES_JOB', 'BLUE_COLLAR', 'FARMER', 'RETIRED', 'SFDU', 'MFDU', 'HOMEOWNER', 'INCOME', 'MAIL_RESP_MULTI', 'MAIL_RESP_SINGLE', 'LENGTH OF RESIDENCE', 'NUMBER OF PERSONS IN LIVING UNIT', 'NUMBER OF ADULTS IN LIVING UNIT', 'METRO', 'URBAN', 'MOR BANK: UPSCALE MERCHANDISE BUYER', 'MOR BANK: MALE MERCHANDISE BUYER', 'MOR BANK: FEMALE MERCHANDISE BUYER', 'MOR BANK: CRAFTS-HOBBY MERCHANDISE BUYER', 'MOR BANK: GARDENING-FARMING BUYER', 'MOR BANK: BOOK BUYER', 'MOR BANK: COLLECT-SPECIAL FOODS BUYER', 'MOR BANK: GIFTS AND GADGETS BUYER', 'MOR BANK: GENERAL MERCHANDISE BUYER', 'MOR BANK: FAMILY AND GENERAL MAGAZINE', 'MOR BANK: FEMALE ORIENTED MAGAZINE', 'MOR BANK: MALE SPORTS MAGAZINE', 'MOR BANK: RELIGIOUS MAGAZINE', 'MOR BANK: GARDENING-FARMING MAGAZINE', 'MOR BANK: CULINARY INTERESTS MAGAZINE', 'MOR BANK: HEALTH AND FITNESS MAGAZINE', 'MOR BANK: DO-IT-YOURSELFERS', 'MOR BANK: NEWS AND FINANCIAL', 'MOR BANK: PHOTOGRAPHY', 'MOR BANK: OPPORTUNITY SEEKERS AND CE', 'MOR BANK: RELIGIOUS CONTRIBUTOR', 'MOR BANK: POLITICAL CONTRIBUTOR', 'MOR BANK: HEALTH AND INSTITUTION CONTRIBUTOR', 'MOR BANK: GENERAL CONTRIBUTOR', 'MOR BANK: MISCELLANEOUS', 'MOR BANK: ODDS AND ENDS', 'MOR BANK: DEDUPED CATEGORY HIT COUNT', 'MOR BANK: NON-DEDUPED CATEGORY HIT COUNT', 'MORTGAGE-HOME PURCHASE: HOME PURCHASE PRICE', 'CHILDREN', 'CAPE: AGE: POP: MEDIAN AGE', 'CAPE: AGE: POP: % 0-17', 'CAPE: AGE: POP: % 18-99+', 'CAPE: AGE: POP: % 65-99+', 'CAPE: ETHNIC: POP: % WHITE ONLY', 'CAPE: ETHNIC: POP: % BLACK ONLY', 'CAPE: ETHNIC: POP: % ASIAN ONLY', 'CAPE: ETHNIC: POP: % HISPANIC', 'CAPE: DENSITY: PERSONS PER HH FOR POP IN HH', 'CAPE: HHSIZE: HH: AVERAGE HOUSEHOLD SIZE', 'CAPE: TYP: HH: % MARRIED COUPLE FAMILY', 'CAPE: CHILD: HH: % WITH PERSONS LT18', 'CAPE: CHILD: HH: % MARR COUPLE FAMW- PERSONS LT18', 'CAPE: CHILD: HH: % MARR COUPLE FAMW-O PERSONS LT18', 'CAPE: LANG: HH: % SPANISH SPEAKING', 'CAPE: EDUC: POP25+: MEDIAN EDUCATION ATTAINED', 'CAPE: HOMVAL: OOHU: MEDIAN HOME VALUE', 'CAPE: BUILT: HU: MEDIAN HOUSING UNIT AGE', 'CAPE: TENANCY: OCCHU: % OWNER OCCUPIED', 'CAPE: TENANCY: OCCHU: % RENTER OCCUPIED', 'CAPE: EDUC: ISPSA', 'CAPE: EDUC: ISPSA DECILE', 'CAPE: INC: FAMILY INC STATE DECILE', 'CAPE: INC: HH: MEDIAN FAMILY HOUSEHOLD INCOME', 'FREQUENCY', 'QUANTITY', 'TOTALSALES', 'FREQUENCY_2Y', 'QUANTITY_2Y', 'TOTALSALES_2Y', '1-Engagement Spend', '2-Wedding Bands Spend', '3-Fashion Diamonds Spend', '4-Fashion Jewelry Spend', '5-Close Out Spend', '6-Promotional Items Spend', '7-Cost Only Spend', '8-Marketing Premium SKUs Spend', '9-Repairs & Appraisals Spend', '10-Pre Owned Spend', '11-Watches Spend', '12-Misc Merchandise Spend', '15-Store Events Spend', '16-Single Stone Jewelry Spend', 'MDAYREV_L1Y', 'MDAYREV_L2Y', 'MDAYREV_L3Y', 'MDAYREV_L4Y', 'MDAYQTY_L1Y', 'MDAYQTY_L2Y', 'MDAYQTY_L3Y', 'MDAYQTY_L4Y', 'MDAYSHOPPER_L1Y', 'MDAYSHOPPER_L2Y', 'MDAYSHOPPER_L3Y', 'MDAYSHOPPER_L4Y'],
     'Categorical': ['STATE', 'PRIVATELABELTENDERFLAG', 'MOSAIC'],
     'DateTime': []
   }
3. List the columns with duplicates a) Remove them b) Print before and after.
   ```
   Duplicate Column Analysis:
   {
     'duplicate_columns': ['CHILDREN', 'CAPE: HHSIZE: HH: AVERAGE HOUSEHOLD SIZE', '7-Cost Only Spend'],
     'original_shape': (10000, 117),
     'new_shape': (10000, 117)
   }
4. List the constant columns a) Remove them b) Print before and after.
   ```
   Constant Column Analysis:
   {
     'constant_columns': ['MARRIED', 'CHILDREN', '7-Cost Only Spend'],
     'original_shape': (10000, 117), 'new_shape': (10000, 117)
   }
5. Create box plot to visualise the outliers of all the numeric columns.
   ![](https://github.com/singhashu7887/acadia/blob/main/outliers_boxplot.png)
6. Create charts for any 6 columns and show their distribution.
    ![](https://github.com/singhashu7887/acadia/blob/main/distributions.png)
