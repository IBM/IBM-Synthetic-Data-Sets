| Excel Column | Field Name | Sample Value | Comment 1 | Comment 2 | In Kaggle |
|:---|:---|:---|:---|:---|:---|
| A | User | 2374 | Card owner - Index into "users.csv" table | This value ranges from 0 to 1 less than the number of people modeled. As that suggests, it covers only people owning... | Yes |
| B | Entity_ID | 16E91A1B10 | Card owner - Unique ID among all entities, e.g. people, companies, etc |  | No |
| C | Card_Index | 2 | Index among all cards and retail instant payment services of *this" User. Range is [0, N-1]. Examples of retail... | This value ranges from 0 to 1 less than the number of cards owned by "User". The value includes credit, debit, and... | Yes |
| D | Card_Brand | Amex | Options: Visa, Mastercard, Amex, Discover |  | Yes |
| E | Card_Type | Credit | Options: Credit, Debit, Prepaid |  | Yes |
| F | Card_Currency | USD | USD = US Dollars. Typical value matches country of owner |  | No |
| G | Card_Number | 343091875500220 |  |  | Yes |
| H | Financial_Institution_ID | 1338CA510 | For Debit cards only, the ID of the financial institution holding the linked account from which funds are withdrawn... |  | No |
| I | Account_ID | 1140951206 | For Debit cards only, the account number of the linked account at the financial institution |  | No |
| J | Initial_Expiration_Date | 2028-12-01 00:00:00 | At start of transaction period |  | Yes |
| K | CVV | 979 |  |  | Yes |
| L | Has_Chip | YES | Probability depends on time period, e.g. 2005 -> No |  | Yes |
| M | Has_Tap | NO | Probability depends on time period, e.g. 2015 -> No |  | No |
| N | Cards_Issued | 2 | Number of cards issued on account |  | Yes |
| O | Initial_Balance | 0 | At start of transaction period |  | Yes |
| P | Final_Balance | 7819.44 | At end of transaction period | Normally the "Final Balance" will be less than the "Credit Limit", but as with real people, our simulated people... | No |
| Q | Credit_Limit | 11900 |  |  | No |
| R | Acct_Open_Date | 2022-01-01 00:00:00 |  |  | Yes |
| S | Last_Fraudulent_Use | NEVER |  |  | Yes |
| T | Year_Pin_Last_Changed | 2022 |  |  | Yes |
| U | Card_on_Dark_Web | No |  |  | Yes |
| V | Lifetime_Transactions | 315 | Over period of synthetic data |  | No |
| W | Fraudulent_Transactions | 0 |  |  | No |
| X | Mean_Transactions_per_Month | 13 |  |  | No |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
| NOTE | The schema described here for "cards.csv" files has a similar, but broader schema than the schema for "inst_pay.csv"... |  |  |  |  |
|  | See the description of retail instant pay services above in the comments for Column C, Card_Index. |  |  |  |  |
|  | The Card_Index value runs across files: the first entries, e.g. 0,1,2 are for cards, the next entries are for reetail... |  |  |  |  |
