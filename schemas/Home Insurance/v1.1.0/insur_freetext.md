| Excel Column | Field Name | Sample Value | Comment 1 | Comment 2 | In Kaggle |
|:---|:---|:---|:---|:---|:---|
| A | Index_to_Ins_Applic_and_Policy | 149 | Integer indexing this freetext to the homeowners application and policy on which this claim is made |  | No |
| B | Insurance_Policy_ID | HVD4996AFE | Unique ID for this policy among all policies of company (and indeed among all policies) |  | No |
| C | Insurance_Claim_ID | CLHVD4992AD1 | Unique ID for this claim among all claims of company (and indeed among all claims) |  | No |
| D | Insured_Claim_Narrative | I hope this damage is covered. Please have somebody come to my house. Suddenly I heard something. There was howling... | These columns in the freetext can be viewed as extensions to the columns in "insur_claims.csv", i.e. there is a 1:1... |  | No |
| E | Generic_Request_for_a_Person | 0 | Labels about attributes of narrative |  | No |
| F | Request_only_Person_can_Answer | 1 |  | E.g. Train automated systems to route more effectively to a person exactly when needed | No |
| G | Request_for_a_Fact | 1 |  |  | No |
| H | Request_for_Advice | 0 |  |  | No |
| I | Request_for_a_Prediction | 0 |  |  | No |
