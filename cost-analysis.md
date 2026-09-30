# Project 4 – AI-Powered Resume Screener & Talent Acquisition Pipeline

## 1. Objective

Estimate the monthly AWS cost for:

- 10 users/day
- 500 users/day
- 5,000 users/day

The project provides backend APIs for:

- User authentication
- Resume upload
- Candidate management
- Candidate shortlisting
- Candidate rejection
- Interview notifications
- CSV export

## 2. AWS Services

- Amazon API Gateway
- AWS Lambda
- Amazon Cognito
- Amazon DynamoDB
- Amazon S3
- Amazon SES
- Amazon CloudWatch

## 3. Traffic Assumption

Initial assumption:

1 user = 20 API requests/day

| Users/day | Users/month | API Requests/day | API Requests/month |
|---:|---:|---:|---:|
| 10 | 300 | 200 | 6,000 |
| 500 | 15,000 | 10,000 | 300,000 |
| 5,000 | 150,000 | 100,000 | 3,000,000 |

## 4. Monthly Cost Estimate

| AWS Service | 10 Users/Day | 500 Users/Day | 5,000 Users/Day |
|---|---:|---:|---:|
| API Gateway | | | |
| Lambda | | | |
| Cognito | | | |
| DynamoDB | | | |
| S3 | | | |
| SES | | | |
| CloudWatch | | | |
| **Total** | | | |

## 5. Most Expensive Component

Component:

Reason:

## 6. Actual AWS Cost

AWS Cost Explorer will be used to compare actual AWS usage
with the projected monthly cost.

## 7. Cost Optimization

Optimization selected:

Before:

After:

Expected benefit:

## 8. Notes

The final cost depends on actual API requests, Lambda execution
duration, DynamoDB reads/writes, S3 storage, Cognito usage,
SES email volume, and CloudWatch logs.