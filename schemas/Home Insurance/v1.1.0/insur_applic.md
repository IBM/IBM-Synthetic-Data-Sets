| Excel Column | Field Name | Sample Value | Comment 1 | Comment 2 | In Kaggle |
|:---|:---|:---|:---|:---|:---|
| A | Index_to_Insurance_Policy_CSV | 235 | Claims use this value to refer back to the policy / applicant | Value is same in "policy.csv", i.e. rows of "policy.csv" logically continue the corresponding "applic.csv" row | No |
| B | Insurance_Policy_ID | GR6E91F89B | Unique ID among all policies issued by company (and actually across all companies) |  | No |
| C | Index_Applicant_1 | 17 | Index to Applicant in users.csv file -> Allows info in the two files and others to be cross-linked | If the value is not in the users.csv file, it indicates that applicant is not a "primary" person in the simulation,... | No |
| D | Entity_ID_Applicant_1 | 1282396C0 | Unique Identifier for Applicant_1 |  | No |
| E | Name_Applicant_1 | Cayson Hayes |  |  | No |
| F | Date_of_Birth_Applicant_1 | 1987-04-01 00:00:00 | Month / Day / Year format |  | No |
| G | Social_Security_Num_Applic_1 | 786-38-7809 |  |  | No |
| H | Drivers_License_Num_Applic_1 | Z979-3439-5902-75 |  |  | No |
| I | Drivers_License_State_Applic_1 | Wisconsin | Currently the 50 US states are supported |  | No |
| J | Drivers_License_Country_Appl_1 | United States | Currently only the United States is supported -- but this field facilitates adding other countries in the future |  | No |
| K | Marital_Status_Applicant_1 | Married | 6 Values are supported: Married, Separated, Always Single, Divorced, Widowed, Cohabiting |  | No |
| L | Education_Level_Applicant_1 | Associates | 9 Values are supported: None, High School, Associates, Some College, Bachelors, Masters, PhD, MD, JD |  | No |
| M | Personal_Phone_Number_Applic_1 | 414-633-6424 |  |  | No |
| N | Email_Address_Applicant_1 | Hayes.7934@googlemail.com | Like other aspects of IBM SDS, email addresses are fake, but realistic |  | No |
| O | Property_ID_To_Be_Insured | 12B41A1B10 | Unique Identifier for Property at address below |  | No |
| P | Street_Address_To_Be_Insured | 945 Federal Street |  |  | No |
| Q | Unit_Number_To_Be_Insured |  |  |  | No |
| R | City_To_Be_Insured | Milwaukee |  |  | No |
| S | State_To_Be_Insured | WI |  |  | No |
| T | Postal_Code_To_Be_Insured | 53214 |  |  | No |
| U | Country_To_Be_Insured | United States |  |  | No |
| V | Months_at_this_Address | 61 |  |  | No |
| W | Prev_Addr_If_less_than_36_mos |  | When no previous address is needed, e.g. more than 36 months at current address, no values are provided for previous... |  | No |
| X | Prev_Unit_Number_Applicant_1 |  |  |  | No |
| Y | Prev_City_Applicant_1 |  |  |  | No |
| Z | Prev_State_Applicant_1 |  |  |  | No |
| AA | Prev_Postal_Code_Applicant_1 |  |  |  | No |
| AB | Prev_Country_Applicant_1 |  |  |  | No |
| AC | Current_Employer_Applicant_1 | Hilton |  |  | No |
| AD | Street_Addr_Employer_Applic_1 | 36532 Eighth Drive |  |  | No |
| AE | Unit_Number_Employer_Applic_1 |  |  |  | No |
| AF | City_Employer_of_Applicant_1 | Milwaukee |  |  | No |
| AG | State_Employer_of_Applicant_1 | WI |  |  | No |
| AH | Postal_Code_Employer_Applic_1 | 53214 |  |  | No |
| AI | Country_Employer_of_Applic_1 | United States |  |  | No |
| AJ | Type_of_Employer_Applicant_1 | Hotels |  |  | No |
| AK | Position_at_Employer_Applic_1 | Interviewer |  |  | No |
| AL | Are_Self_Employed_Applicant_1 | No |  |  | No |
| AM | Years_on_Job_Applicant_1 | 3 |  |  | No |
| AN | Years_in_Profession_Applic_1 | 18 |  |  | No |
| AO | Business_Phone_Applicant_1 | 414-280-7042 |  |  | No |
| AP | Index_Applicant_2 | 17 | Index to Applicant in users.csv file -> Allows info in the two files and others to be cross-linked | If the value is not in the users.csv file, it indicates that applicant is not a "primary" person in the simulation,... | No |
| AQ | Entity_ID_Applicant_2 | 1282399C0 | Unique Identifier for Applicant_2 |  | No |
| AR | Name_Applicant_2 | Zoey Hayes |  |  | No |
| AS | Date_of_Birth_Applicant_2 | 1976-01-07 00:00:00 |  |  | No |
| AT | Social_Security_Num_Applic_2 | 392-56-6826 |  |  | No |
| AU | Drivers_License_Num_Applic_2 | G407-2062-5784-12 |  |  | No |
| AV | Drivers_License_State_Applic_2 | Wisconsin |  |  | No |
| AW | Drivers_License_Country_Appl_2 | United States |  |  | No |
| AX | Marital_Status_Applicant_2 | Married |  |  | No |
| AY | Education_Level_Applicant_2 | Bachelors |  |  | No |
| AZ | Personal_Phone_Number_Applic_2 | 414-312-2984 |  |  | No |
| BA | Email_Address_Applicant_2 | hare3216@icloud.com |  |  | No |
| BB | Current_Employer_Applicant_2 | Katelyn's Bank |  |  | No |
| BC | Street_Addr_Employer_Applic_2 | 358 Madison Boulevard |  |  | No |
| BD | Unit_Number_Employer_Applic_2 |  |  |  | No |
| BE | City_Employer_of_Applicant_2 | Milwaukee |  |  | No |
| BF | State_Employer_of_Applicant_2 | WI |  |  | No |
| BG | Postal_Code_Employer_Applic_2 | 53215 |  |  | No |
| BH | Country_Employer_of_Applic_2 | United States |  |  | No |
| BI | Type_of_Employer_Applicant_2 | Financial Institution |  |  | No |
| BJ | Position_at_Employer_Applic_2 | Loan Officer |  |  | No |
| BK | Are_Self_Employed_Applicant_2 | No |  |  | No |
| BL | Years_on_Job_Applicant_2 | 1 |  |  | No |
| BM | Years_in_Profession_Applic_2 | 27 |  |  | No |
| BN | Business_Phone_Applicant_2 | 414-705-2426 |  |  | No |
| BO | Foreclose_repossess_bankruptcy | No |  |  | No |
| BP | Insur_decline_cancel_no_renew | No |  |  | No |
| BQ | Convict_arson_fraud_prop_crime | No |  |  | No |
| BR | Residence_Type_to_be_Insured | Single Family House |  |  | No |
| BS | Number_of_Units | 1 |  |  | No |
| BT | Year_Built | 2022 |  |  | No |
| BU | House_Value | 251573 | US Dollars |  | No |
| BV | Distance_to_Fire_Hydrant | 350 |  |  | No |
| BW | Distance_to_Fire_Station | 1 |  |  | No |
| BX | Distance_to_Tidal_Water | 700 |  |  | No |
| BY | Angle_of_Slope_with_House | 0 |  |  | No |
| BZ | Lot_Size | 21903 |  |  | No |
| CA | Living_Area | 2633 |  |  | No |
| CB | Basement_Area | 0 |  |  | No |
| CC | Garage_Area | 420 |  |  | No |
| CD | Garage_Capacity | 2 |  |  | No |
| CE | Basement_Finished | 0 |  |  | No |
| CF | Number_of_Stories | 2 |  |  | No |
| CG | Construction_Style | Wood Frame |  |  | No |
| CH | Number_of_Bedrooms | 4 |  |  | No |
| CI | Number_of_Full_Baths | 2 |  |  | No |
| CJ | Number_of_Half_Baths | 1 |  |  | No |
| CK | Bathroom_Quality | High |  |  | No |
| CL | Kitchen_Quality | High |  |  | No |
| CM | Fireplace_Count | 1 |  |  | No |
| CN | Wood_Stove_Count | 0 |  |  | No |
| CO | Electrical_Service | 150 |  |  | No |
| CP | Roof_Last_Update_Year | 2022 |  |  | No |
| CQ | Roof_Type_of_Update |  |  |  | No |
| CR | Wiring_Electrical_Update_Year | 2022 |  |  | No |
| CS | Wiring_Electrical_Update_Type |  |  |  | No |
| CT | Heating_Last_Update_Year | 2022 |  |  | No |
| CU | Heating_Type_of_Update |  |  |  | No |
| CV | Plumbing_Last_Update_Year | 2022 |  |  | No |
| CW | Plumbing_Type_of_Update |  |  |  | No |
| CX | Foundation_Type | 1 | 1 = Concrete Slab; 2 = Crawlspace; 3 = Cinderblock Basement; 4 = Poured Concrete Basement; 5 = Stone Basement; 6 =... |  | No |
| CY | Exterior_Wall_Type | 1 | 1 = Brick; 2 = Wood Siding; 3 = Vinyl Siding; 4 = Aluminum Siding; 5 = Stucco; 6 = Concrete Board; 7 = Wood Shingles;... |  | No |
| CZ | Roof_Shape | 4 | 1 = A-Frame; 2 = Flat; 3 = Gable with Valler; 4 = Gable with Dormer; 5 = Bonnet; 6 = Butterfly; 7 = Gambrel; 8 =... |  | No |
| DA | Roof_Material | 1 | 1 = Asphalt Shingles; 2 = Shake - Wood; 3 = Shake - Cement; 4 = Aluminum / Metal; 5 = Copper; 6 = Clay Tiles; 7 =... |  | No |
| DB | Roof_Anchor | 1 | 1 = Toe Nailing; 2 = Clips; 3 = Single Straps; 4 = Double Straps; 5 = Structural; 6 = Unknown |  | No |
| DC | Wind_Protection | 6 | 1 = Strong Glass; 2 = Wooden Storm Shutters; 3 = Electric Metal Shutters; 4 = Manual Metal Shutters; 5 = None; 6 =... |  | No |
| DD | Protection_Class | 1 | 1 = Great to 10 = Horrible |  | No |
| DE | Is_Manufactured_Home | No |  |  | No |
| DF | Is_Historic | No |  |  | No |
| DG | Has_Historic_Tours | No |  |  | No |
| DH | Is_Garage_Attached | Yes |  |  | No |
| DI | Is_Garage_Heated | No |  |  | No |
| DJ | Has_Automated_Garage_Doors | Yes |  |  | No |
| DK | Has_Carport | No |  |  | No |
| DL | Has_Screen_Enclosure | No |  |  | No |
| DM | Has_Walkout_Basement | No |  |  | No |
| DN | Has_Walkup_Attic | Yes |  |  | No |
| DO | Has_T_Lock_Shingles | No |  |  | No |
| DP | Has_Asbestos_Shingles | No |  |  | No |
| DQ | Is_Under_Construction | No |  |  | No |
| DR | Is_Bolted_To_Foundation | No |  |  | No |
| DS | Has_Visible_Damage | No |  |  | No |
| DT | Has_Deadbolt_Locks | Yes |  |  | No |
| DU | Has_Sprinklers | No |  |  | No |
| DV | Has_Smoke_Detectors | Yes |  |  | No |
| DW | Has_Carbon_Monoxide_Detectors | Yes |  |  | No |
| DX | Has_Local_Theft_Alarm | No |  |  | No |
| DY | Has_Central_Theft_Alarm | No |  |  | No |
| DZ | Has_Central_Fire_Alarm | No |  |  | No |
| EA | Has_Video_Surveillance | No |  |  | No |
| EB | Has_Video_Monitoring | No |  |  | No |
| EC | Has_Leak_Defense_System | Yes |  |  | No |
| ED | Has_Motion_Lighting | Yes |  |  | No |
| EE | Is_Teardown | No |  |  | No |
| EF | Is_Gutted_and_Remodeled | No |  |  | No |
| EG | Is_Visible_from_Road | Yes |  |  | No |
| EH | Is_Visible_to_Neighbors | Yes |  |  | No |
| EI | Occupied_Daily | Yes |  |  | No |
| EJ | Has_Flood_Insurance | No |  |  | No |
| EK | Has_Knob_and_Tube_Wiring | No |  |  | No |
| EL | Has_Fuses | No |  |  | No |
| EM | Has_FPE_Electric_Panel | No |  |  | No |
| EN | Has_Lead_Pipes | No |  |  | No |
| EO | Has_Iron_Pipes | No |  |  | No |
| EP | Has_Polybutylene_Pipes | No |  |  | No |
| EQ | Has_Lead_Paint | No |  |  | No |
| ER | Has_Asbestos | No |  |  | No |
| ES | Has_Fuel_Tank_Underground | No |  |  | No |
| ET | Has_Fuel_Tank_above_Ground | No |  |  | No |
| EU | Has_Fuel_Tank_in_Basement | No |  |  | No |
| EV | PrivateHome_Convert_from_Other | No |  |  | No |
