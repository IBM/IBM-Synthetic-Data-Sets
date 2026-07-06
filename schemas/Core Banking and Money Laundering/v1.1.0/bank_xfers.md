| Excel Column | Field Name | Sample Value | Comment 1 | Comment 2 | In Kaggle |
|:---|:---|:---|:---|:---|:---|
| A | Transaction_Number | 57 | Index of transaction among all transactions | First transaction is 1, second is 2, etc. | No |
| B | Transaction_Date | 2025-08-11 00:00:00 | Year - Month - Day |  | Yes |
| C | Transaction_Time | 14:32:17.6 | Kaggle to 1 minute. Enterprise to 0.1 second |  | Yes |
| D | Transaction_Day_of_Week | Monday | Day of the week corresponding to Transaction_Date |  | No |
| E | From_Bank_Name | XYZ Bank | Kaggle has no human-friendly Bank Names |  | No |
| F | From_Bank_ID | DBC8963C0 | Kaggle has only this numeric value |  | Yes |
| G | From_Account | 3020009543 | From Account Number |  | Yes |
| H | To_Bank_Name | ABC Bank | Kaggle has no human-friendly Bank Names |  | No |
| I | To_Bank_ID | DBC8948E0 | Kaggle has only this numeric value |  | Yes |
| J | To_Account | 1409286471 | To Account Number |  | Yes |
| K | Amount_Paid | 1.2 | 1.2 |  | Yes |
| L | Payment_Currency | USD | Standard 3-letter currency abbreviations | All 143 country currencies are supported, e.g. EUR and CNY. 13 of the leading crypto currencies are also supported,... | Yes |
| M | Amount_Received | 1.2 | 1.2 |  | Yes |
| N | Receiving_Currency | USD | Kaggle NOT standard abbreviations | As with "Payment Currency" there are 143 country currencies and 13 crypto currencies | Yes |
| O | Payment_Format | Debit Non-Prepaid | Could be ACH, Cheque, etc | Supported formats: Cash, Credit Card, Debit Card (Non-Prepaid), Debit (Prepaid), Cheque, ACH, Wire, Bitcoin +... | Yes |
| P | From_Initial_Balance | 1798 | 1798 |  | No |
| Q | From_End_Balance | 1796.8 |  |  | No |
| R | To_Initial_Balance | 75835545.32 | 75835545.32 | Large amounts typical for large companies | No |
| S | To_End_Balance | 75835546.52 |  |  | No |
| T | Transaction_Type | Personal Expense | Could be Salary, Bank Fee, Refund, etc. | Supported types: Higher Interest, Forced Savings, To IRA Account, From IRA Account, From 401k Account, Buy... | No |
| U | Laundering_Type |  | Could be Fan-In, Fan-Out, Cycle, etc. | Supported types: Fan-Out, Fan-In, Cycle, Bipartite, Stack, Random, Scatter-Gather, Gather-Scatter, Other | No |
| V | Is_Laundering | 0 | Is transaction part of a laundering operation? | 0 -> Not a laundering transaction, 1 -> Laundering | Yes |
| W | Is_Card_Fraud | 0 | Is transaction a case of credit or debit-card fraud? |  | No |
| X | Is_Instant_Payments_Fraud | 0 | Is transaction a case of retail instant payments fraud? | Similar to credit card fraud, but instead the criminal steals instant payment credentials, and uses them to make... | No |
| Y | Is_Cheque_Fraud | 0 | Is transaction a case of cheque fraud? |  | No |
| Z | Is_APP_Fraud | 0 | Is transaction a case of APP fraud? |  | No |
| AA | Card_Fraudster_ID | 6AA4F640 | Unique ID of Fraudster Committing the Card Fraud |  |  |
| AB | Instant_Payments_Fraudster_ID | 6AA4F780 | Unique ID of Fraudster Committing the Instant Payments Fraud | See comments above for Column V |  |
| AC | Cheque_Fraudster_ID | 6AA4F900 | Unique ID of Fraudster Committing the Cheque Fraud |  | No |
| AD | APP_Fraudster_ID | 6AA78E20 | Unique ID of Fraudster Committing the APP Fraud |  | No |
| AE | APP_Fraud_Sequence_Number | 2 | Valid only if "Is APP Fraud?" field is 1. In that case, value indicates which theft in a sequence of thefts of the... | When field is valid, the sequence number is sequential as thefts continue, e.g. 1, 2, 3, …. When field is not valid,... | No |
| AF | Sufficient_Funds | 1 | Not an overdraft | 0 -> From Account has sufficient fund, 1 -> Does not | No |
| AG | Overdraft_Okay | 1 | Overdraft permitted? | 0 -> From Account allows overdrafts, 1 -> Does not | No |
| AH | Is_All_Cash | 0 | Are both the "From Account" and "To Account" cash? | 1 -> Both accounts are cash, 1 -> Not both cash | No |
| AI | Is_Hold | 0 | Hold transaction, e.g. at hotel | 0 -> Not a hold transaction, 1 -> Hold | No |
| AJ | P2P_Reimb_Base_Transac_Format | Card | 4 Possible Values: Card, Cash, Instant Pay, and Bank Xfer. These values indicate the file with the original... | NOTE: In a small number of cases, the original transaction may not be in the data, e.g. occurring before or after the... | No |
| AK | P2P_Reimb_Base_Transac_ID | 6895049AV4DWM4VTQ | An ID based on the 4 format values above to enable finding the original transaction for which P2P reimbursement is... |  | No |
