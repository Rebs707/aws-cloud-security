# Architecture

```text
Users
   │
   ▼
AWS Security Groups
   │
   ▼
AWS Workloads
   │
   ├──────────► AWS CloudTrail
   │
   ├──────────► AWS CloudWatch
   │
   ├──────────► AWS KMS Encryption
   │
   └──────────► AWS Secrets Manager
```
