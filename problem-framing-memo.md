# Problem-Framing Memo: Customer Churn

## Decision to support

Could a support team use customer activity to decide whom to contact with an optional, helpful check-in?

## Prediction target

Predict whether a customer will churn. The dataset’s `churned` column uses `1` for churned and `0` for not churned. The dataset does not define when churn is measured or how far ahead to predict.

## Unit of observation

One row represents one customer. The sample has 12 customers.

## Action window

The dataset has no dates, so a prediction window cannot be set from the supplied information. For a real project, agree on a time window, such as predicting churn within the next 30 days using information collected before those 30 days begin.

## Non-ML baseline

Predict “not churned” for every customer. That is the majority class in this sample: 7 of 12. Any model should be compared with this simple baseline.

## Appropriate use

A future, properly tested model might help staff prioritize optional, supportive outreach. Staff should review suggestions, and ordinary support must remain available to everyone.

## Decisions this must not make

Do not use predictions to deny service, change prices, penalize customers, or make automatic decisions about individual customers.

## Limitations and open questions

The dataset has only 12 rows. Its source, collection dates, churn definition, representativeness, and sharing permission are unknown. This sample cannot establish that a model will work for real customers. Confirm these details and obtain a larger, authorized dataset before considering real use.
