# LPS harmonised demographic dataset (reduced)
>Last modified: 17 Jul 2025
<div style="background-color: rgba(0, 178, 169, 0.3); padding: 5px; border-radius: 5px;"><strong>UK LLC has created a harmonised dataset of key demographic variables across the partner LPS.</strong></div>  

## 1. Summary
The reduced LPS harmonised demographic dataset contains harmonised variables for **sex, gender, year of birth** and **ethnic group**.  

>**Note** UK LLC has not changed the original LPS data for these variables.  

This dataset retains only the **most recent response** provided by a participant for each variable.  

>Researchers are encouraged to use the **reduced dataset**:  
>* To have the most recent, valid, definition of a participant’s demographic characteristics 
>* To have comparable data on ethnicity and gender for the maximum number of participants
>* To be able to compare LPS data with data from NHS England using the [**NHSE demographics dataset**](../../../linked_health_data/NHS_England/Registration%20datasets/DEMOGRAPHICS/DEMOGRAPHICS.ipynb).  

 Where different levels of granularity can be derived for variables (objects), i.e. ethnic group and gender, all possible levels of the variables have been derived and included in the dataset.

**Missing data** have been removed from the reduced dataset.

## 2. Variables
<br>

| Variable name | Variable description |  
|---|---|
| LLC_xxxx_stud_id | Individual identifier (unique to each project in the TRE) |
| cohort | LPS name |
| source | LPS dataset holding the original demographic variable(s) for each participant (e.g. ALSPAC_wave1y) |
| object | Label indicating which of the harmonised variables is represented by the value (e.g. llc_sex, llc_gender) |
| value | Numeric value for each of the objects |
| label | Description of what each of the values represents |  
| llc_timestamp | Date (month and year) on which the information was provided by the participant to the LPS |  

## 3. Updates to dataset  
Whenever a new LPS joins UK LLC, demographic variables provided by the LPS will be harmonised and added to the UK LLC demographic datasets. These Guidebook pages will be updated to reflect these changes.