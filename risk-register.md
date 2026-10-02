# Risk Register

| Risk | Possible harm | Safeguard |
|---|---|---|
| Very small dataset (12 customers) | Results may not apply to real customers | Treat as a learning exercise; do not use for real decisions |
| Unknown data source or permission | Data may be used or shared without authorization | Ask the task provider about permission before sharing the customer-level data |
| False positive (predicts churn, but customer stays) | Unwanted contact or wasted staff time | Use only for optional, respectful outreach; have staff review |
| False negative (misses a customer who leaves) | Customer may not receive helpful support | Keep normal support available to everyone |
| Data leakage | Model may appear more accurate than it is | Confirm features were recorded before the churn outcome; exclude customer ID |
| Bias or poor representation | Some customers may be treated less fairly | Check errors across relevant groups when authorized data is available |
| Model performance changes | Predictions may become unreliable over time | Monitor results and stop using the model if data or performance becomes unreliable |

## Human review and rollback

Do not take automatic action based on a prediction. Have a staff member review any suggested outreach. Stop using the model if the input data changes, errors increase, or unfair patterns are found.
