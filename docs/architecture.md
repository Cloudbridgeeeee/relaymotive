# Proposed AWS architecture

| Service | Role |
|---|---|
| S3 and Lambda | Encrypted uploads, job cards read and matched to vehicles |
| SageMaker AI | Service-due and repeat-fault models per vehicle type |
| Bedrock | Plain-language recommendations that cite their job cards |
| DynamoDB | Vehicles, reminders and the mechanic decision log |

One AWS account per customer, encrypted at rest and in transit. The public demo calls none of these services.
