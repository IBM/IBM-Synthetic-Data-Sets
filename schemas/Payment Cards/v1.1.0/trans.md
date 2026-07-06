| Excel Column | Field Name | Sample Value | Comment 1 | Comment 2 | In Kaggle |
|:---|:---|:---|:---|:---|:---|
| A | User | 0 | Index to user info in "users.csv" table | Range is [0, Num People - 1] | Yes |
| B | Entity_ID | 16E91A1B10 | Alternate Unique ID for User in Column A | Entity_ID values can be used when entity may be either a person or company | No |
| C | Card | 0 | Index to card info in "cards.csv" table or "inst_pay.csv" table | Range is [0, Num Cards of User - 1] | Yes |
| D | Transaction_Date | 2025-02-03 00:00:00 | Year - Month - Day |  |  |
| E | Transaction_Day_of_Week | Monday | Day of the week corresponding to the Transaction_Date |  | No |
| F | Transaction_Time | 20:12:31.700000 | HH:MM:SS with hours (HH) in 24-hour format |  | Yes |
| G | Transaction_Ref_ID | 91699769A4DUH1CSG | Standard Format |  | No |
| H | Payment_to_Merchant | 98.48 |  |  | Yes |
| I | Merchant_Currency | USD |  |  | No |
| J | Charge_to_Buyer | 98.48 |  |  | No |
| K | Buyer_Currency | USD |  |  | No |
| L | Method | Swipe | Can be Swipe, Chip, Tap, or Online for purchases in "*card_trans.csv" files. Can be only Cash for purchases in... |  | Yes |
| M | Digital_Wallet | GooglePay | Notes the digital wallet -- if any -- used to make the payment. | If no digital wallet is used, the value listed is "NO DIGITAL WALLET" | No |
| N | Merchant_Name | Exxon | Unlike in IBM Synthetic Data Sets, the Merchant_Name is numerically encoded in Kaggle |  | Yes |
| O | Merchant_ID | 10A3D1540 | Unique Identifier of Merchant Company where sale is made. | Allows cross-referencing other files where merchant ID are used, e.g. in insurance, B2B, etc | No |
| P | Merchant_Location_ID | 10C13A360 | Unique Identifier of Merchant Location where sale is made. | Many large companies have multiple locations, e.g. McDonalds. This ID allows separating these locations. | No |
| Q | Merchant_City | Milwaukee | Kaggle: Not provided for online purchases |  | Yes |
| R | Merchant_State | WI | Kaggle: Not provided for online purchases |  | Yes |
| S | Postal_Code | 53221 | Kaggle: Not provided for online purchases |  | Yes |
| T | Country | United States | Kaggle: Country is listed under "Merchant State" if not US |  | No |
| U | Latitude | 43.038902 | Latitude and Longitude enables easy comparison in a model of brick and mortar purchase locations: two transactions in... |  | No |
| V | Longitude | -87.906471 |  |  | No |
| W | MCC | 5541 | MCC = Merchant Category Code |  | Yes |
| X | Is_Online | No | Yes -> the transaction is made with with the merchant, e.g. with Amazon |  | Yes |
| Y | Is_Hold | 0 | A hold transaction occurs when money that is temporarily added to a credit card balance or deducted from an account... |  | No |
| Z | Is_Flight | 0 | Flight means that this transaction is for an airline reservation. Transactions that are airline reservations provide... |  | No |
| AA | Flight_Date | 2025-04-09 00:00:00 | Year - Month - Day | Flight1 Start Date. Empty if "Is Flight?" is 0 | No |
| AB | Flt1_Src_Airport |  | Flight1 Origin Airport -- often near home. This airport marks where travel begins |  | No |
| AC | Flt1_Dest_Airport |  | Flight1 Destination Airport. This airport marks where the first leg of travel ends |  | No |
| AD | Flt2_Src_Airport |  | Flight2 Origin Airport -- often same as "Flight1 Dest Airport". This airport marks the start of (typically) a return... |  | No |
| AE | Flt2_Dest_Airport |  | Flight2 Destination Airport -- often same as "Flight1 Src Airport". This airport marks the end of (typically) a... |  | No |
| AF | Uses_Stolen_Digital_Wallet | 0 | 0 -> Transaction does not use stolen digital wallet. 1 -> Does use stolen digital wallet |  | No |
| AG | Is_Fraud | 0 | 0 -> This transaction is legitimate. 1 -> This transaction is fraud |  | Yes |
| AH | Fraudster_ID | 0 | Lets models track who is doing fraud -> Better accuracy? |  | No |
| AI | IBM_Internal | No | This value is reserved for IBM use, and its value should not be relied upon. |  | No |
| AJ | Errors |  | A number of errors can prevent a transaction from being processed, and this field lists any such errors that occurred... |  | Yes |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
| NOTE | Three separate files use this schema: (1) the "card_trans.csv" file; (2) the "inst_pay_trans.csv" file; and (3) the... |  |  |  |  |
|  | Examples of retail instant payment services depicted in (2) are UPI in India, Pix in Brazil, and M-Pesa in Kenya. |  |  |  |  |
|  | Many countries do not have retail instant payment services, e.g. the United States. |  |  |  |  |
|  | However, across a broad set of countries have digital wallets like GooglePay or ApplePay. |  |  |  |  |
|  | These digital wallets typically contain a variety of payment options, e.g. different credit and debit cards. |  |  |  |  |
|  | Tapping a digital wallet for payment at a merchant serves as an alternate form of retail instant payment or "digital... |  |  |  |  |
|  | IBM Synthetic Data Sets also have digital wallets, and their use in transactions is noted in column M "Digital... |  |  |  |  |
|  | The digital wallets owned by people are listed in the "dwallets.csv" file. |  |  |  |  |
