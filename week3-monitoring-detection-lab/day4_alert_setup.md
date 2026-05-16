# AWS CloudWatch Alerts & SNS Notifications

## What I did:

- Created SNS topic for alert notifications
- Configured email subscription using SNS
- Confirmed email subscription
- Created CloudWatch alarm for EC2 CPU utilization
- Triggered CPU spike using EC2 workload
- Observed alarm state changes
- Received email notification from AWS SNS

---

## Key Learnings:

- CloudWatch alarms help detect abnormal system behavior
- SNS enables automated alert notifications
- Threshold-based monitoring improves incident response
- Alerts are important for proactive security monitoring

---

## Hands-on Summary:

- Created SNS topic:
  - `security-alerts`
- Configured email-based notification system
- Created CloudWatch alarm:
  - CPUUtilization > 70%
- Generated CPU load using:
  ```bash
  yes > /dev/null
