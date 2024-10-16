### **Survey on Overseas Filipinos 2015**
Last October of 2015, the Philippine Statistics Authority (PSA) created a dataset on a Survey on Overseas Filipinos (SOF). The survey was designed to gather data on the amount of overseas Filipino workers (OFW) along with their socio economic characteristics and other information related to working abroad from April to September. The remittances of the OFWs were also taken into account for the specified period. 


### **Collection Process**
**Sampling Procedure** <br>
**The SOF used the sampling design of the 2003 Master Sample for Household Surveys.*
1. `Domain` - **each of the country's 17 administrative regions** were considered as a domain for this survey
2. `Sampling Frame` - the primary sampling units (PSU) were defined as a **barangay or a combination of barangays with at least 500 households**
3. `Sample Size` - **2,835 PSUs** (330 certainty PSUs, 2,505 non-certainty PSUs)
4. `Stratification` - the **17 regions** of the country were considered as the primary strata
5. `Sample Selection` - **divided into 4 sub-samples** with probability proportional to some estimated measure of size of the total number of households from the 2000 CPH

**Data Collection**
- `Dates of Collection` - 2015-10-08 (October 8, 2015) - 2015-10-30  (October 8, 2015)
- `Mode of Data Collection` - Face-to-face (F2F)
- `Data Collection Supervision` - **supervisors** are required to have an itinerary of travel for efficiency and security, a copy of the said itinerary is also available in the field office in case of emergencies. Supervisors are also the ones who are tasked with taking action in any problems that may arise hence regional directors and provincial statistical officers are encouraged to visit them to rate their progress.
- `Questionnaires` - **SOF Form 2** is the household (HH) control form and is the basis to determine households with members that is overseas. HHs with overseas members in the specified time period were given the SOF Form 1. The other questionnaire, SOF Form 1, is designed to gather data on the number of overseas Filipinos, their socio-economic characteristics, and their remittances.
- `Data Collectors` - Philippine Statistics Authority (PSA)
  


### **Data Collection Implications**
The data collection implies that the resulting conclusions and insights will be related to `socio-economic characteristics, the migration patterns of OFWs, and the OFWs' remittance behaviors`.<br>
There are some variables that are directly defines OFWs' socio-economic characteristics like RQ8_HGRADE (Highest Grade Completed) while some like RQ19_REASON (Reason for returning in the country) may suggest or prove their current standing.<br>
As for the migration patterns, variables starting with RQ10 to RQ20 are related to going abroad and their length of stay overseas. It also includes the reasons for leaving or returning to the country, the expected and actual dates of returning home, the kind of work abroad, and how long they worked for overseas.<br>
Lastly, for the remittance behaviors, variables starting with RQ21 to RQ24 are all remittance-related with 2 variables stating the amount received, the mode of remittance, and the amounts of remittance spent on certain categories. 


### **Dataset Structure**
The survey on overseas Filipinos' data structure contains the overseas Filipino (OF) identifier and his or her data related to the survey. There are exactly `5440 observations` in the dataset each representing `1 OF which is placed per row` of the data frame. Each row contains their personal information, information about leaving or staying abroad, and data on their remittances. On the other hand, `*each column represents the values of the OFs per variable`. This particular dataset contains `48 variables`, 2 of which are used as identifiers, namely RREG (Region) and HHNUM (Unique HH Serial Number).


### **Variables**
**Overseas Filipino Identification Variables**
- `RREG` - Region
- `HHNUM` - Unique HH Serial Number

**Survey Variables**
- `RRPL` - Replicate
- `RSTR` - Stratum
- `RPSU` - PSU NO
- `RROTATION` - Rotation Group
- `RQ1_LNO` - Line Number
- `RQ2_REL` - Relationship
- `RQ3_SEX` - Sex
- `RQ4_AGE` - Age
- `RQ5_TMSLEFT` - Times left
- `RQ6M_DTLEFT` - Date left (Month)
- `RQ6Y_DTLEFT` - Date left (Year)
- `RQ7_MSTAT` - Marital Status
- `RQ8_HGRADE` - Highest Grade Completed
- `RQ9_USOCC` - Usual occupation
- `RQ10_REASON` - Reason for leaving
- `RQ11_BASE` - Land-based or sea-based worker
- `RQ12_CTRY` - Country intend to stay
- `RQ13_STAY` - Months planning to stay
- `RQ14_INDWORK` - Had a job/business anytime
- `RQ15_OCCUP1` - Kind of work abroad 
- `RQ16_NOMONTH` - Number of months worked
- `RQ17_RET` - Has returned home
- `RQ18M_DTRET` - Date returned home (Month)
- `RQ18Y_DTRET` - Date returned home (Year)
- `RQ19_REASON` - Reason for returning in the country
- `RQ20M_DTEXP` - Date expected to return home (Month)
- `RQ20Y_DTEXP` - Date expected to return home (Year)
- `RQ21_CASHREM` - Remittance recieved
- `RQ22_CASHAMT` - Cash remittance receieved
- `RQ23_MODE` - Mode of remittance
- `RQ241C_CONSUM` - Remittance was spent for Consumption
- `RQ241P_CONSUM` - Percent of Remittance spent for Consumption 
- `RQ242C_INVEST` - Remittance was spent for Investments
- `RQ242P_INVEST` - Percent of Remittance spent for Investments
- `RQ243C_SAVINGS` - Remittance was spent for Savings
- `RQ243P_SAVINGS` - Percent of Remittance spent for Savings
- `RQ244C_GIFT` - Remittance was spent for Gifts
- `RQ244P_GIFT` - Percent of Remittance spent for Gifts
- `RQ245C_OTHERS` - Remittance was spent for Other reasons
- `RQ245P_OTHERS` - Percent of Remittance spent for Others
- `RQ25_RET6MOS` - Returned during the period April to September 2015
- `RQ26_CASHHOME` - Cash brought home
- `RQ27_INKIND` - Receive goods/products
- `RQ28_KINDAMT` - Total imputted value of goods/products
- `RSWGT` - Weight
- `RP6M_IND` - Past Six Months Indicator
