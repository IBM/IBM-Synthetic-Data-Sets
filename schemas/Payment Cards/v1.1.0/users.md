| Excel Column | Field Name | Sample Value | Comment 1 | Comment 2 | In Kaggle |
|:---|:---|:---|:---|:---|:---|
| A | Person_Index | 179 | Index of Person in Column C | Range: [0, N-1] where N = # of People | No |
| B | Entity_ID | 16E91A1B10 | Alternate Unique ID for Person in Column C | Entity_ID values can be used when entity may be either a person or company | No |
| C | Person | Cayson Hayes | Card Owner |  | Yes |
| D | Start_Age | 34 | Age of "Person" at the start of the period where transactions are generated |  | Yes |
| E | End_Age | 36 | Age of "Person" at the end of the period where transactions are generated |  | Yes |
| F | Retirement_Age | 67 |  |  | Yes |
| G | Birth_Date | 1987-04-09 00:00:00 |  |  | Yes |
| H | Gender | Male |  |  | Yes |
| I | Home_Property_ID | 12B41A1B10 | Unique Identifier for Property at address below |  | No |
| J | Address | 945 Federal Street |  |  | Yes |
| K | Apartment | 4314 |  |  | Yes |
| L | City | Milwaukee |  |  | Yes |
| M | State | WI |  |  | Yes |
| N | Postal_Code | 53214 |  |  | Yes |
| O | Country | United States |  |  | No |
| P | Latitude | 43.06 |  |  | Yes |
| Q | Longitude | -87.96 |  |  | Yes |
| R | Currency | USD | USD = US Dollars. Value typically matches country of user |  | No |
| S | Is_Criminal | 0 | 0 -> Not Criminal, 1 -> Criminal |  | No |
| T | Per_Capita_Income_Postal_Code | 20311 | In the Postal Code (Zipcode) above |  | Yes |
| U | Yearly_Income_Person | 49130 | In the Postal Code (Zipcode) above |  | Yes |
| V | Total_Initial_Debt | 148612 | At start of transaction period |  | Yes |
| W | Credit_Score | 722 | At start of transaction period |  | Yes |
| X | Num_Card_Accounts | 5 | Number of different credit or debit accounts |  | Yes |
| Y | Num_Retail_Instant_Payment_Accts | 1 | Number of retail instant payment accounts | E.g. UPI in India or Pix in Brazil | No |
|  |  |  |  |  |  |
| NOTE |  |  |  |  |  |
|  | In Kaggle, there is no Column A with "Person Index". |  |  |  |  |
|  | To compute it, use Excel row number in "users.csv" -> User Index in "cards.csv" and "trans.csv" files |  |  |  |  |
|  | Row 2 -> User 0 |  |  |  |  |
|  | Row 3 -> User 1 |  |  |  |  |
|  | Row 4 -> User 2 |  |  |  |  |
|  | Etc |  |  |  |  |
