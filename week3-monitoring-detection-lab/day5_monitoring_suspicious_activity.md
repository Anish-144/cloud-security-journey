
---

# 📅 Day 5 — Suspicious Activity Detection

# AWS Suspicious Activity Detection

## What I did:

- Generated AWS activity for monitoring analysis
- Attempted failed login testing
- Created IAM users and S3 resources
- Investigated CloudTrail event history
- Analyzed S3 activity logs and monitoring events
- Troubleshooted CloudTrail configuration issues

---

## Key Learnings:

- CloudTrail records AWS account activities
- Monitoring configuration affects event visibility
- CloudTrail uses:
  - Management Events
  - Data Events
- Region configuration impacts event monitoring
- Troubleshooting logging systems is part of real-world cloud security work

---

## Hands-on Summary:

- Generated events:
  - IAM user creation
  - S3 bucket creation/deletion
  - Login activity
- Investigated:
  - Event history
  - CloudTrail trails
  - Event selectors
  - Region settings
- Successfully monitored:
  - S3 activity logs
  - CloudWatch monitoring
  - SNS notifications

---

## Mistakes to Avoid:

- Misconfiguring CloudTrail event selectors
- Confusing management events with data events
- Using incorrect AWS region during monitoring
- Assuming logs appear instantly

---

## Security Insight:

- Logging pipelines require correct configuration
- Monitoring visibility is critical during investigations
- Missing logs can create security blind spots
- Continuous monitoring improves incident detection

---

## Screenshots Taken:

- CloudTrail trail configuration
- S3 event logs
- Event selector settings
- CloudWatch monitoring graphs
- SNS alert notifications

---

