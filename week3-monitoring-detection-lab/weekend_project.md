# AWS Monitoring & Detection Lab

## Project Objective

Build a cloud monitoring and detection environment using AWS services to monitor activity, generate alerts, and investigate security-related events.

---

## AWS Services Used

- AWS CloudTrail
- Amazon CloudWatch
- Amazon SNS
- Amazon EC2
- Amazon S3
- AWS IAM

---

## What I Implemented

### Logging & Monitoring
- Created CloudTrail trail for AWS activity logging
- Configured centralized log storage using S3
- Monitored EC2 metrics using CloudWatch

### Alerting System
- Created SNS topic for notifications
- Configured CloudWatch alarm for high CPU usage
- Triggered CPU spike and verified alert system

### Activity Simulation
- Generated:
  - CPU spikes
  - S3 bucket activity
  - IAM user operations
  - Login activity

### Investigation Workflow
- Analyzed CloudTrail event history
- Investigated monitoring visibility issues
- Explored management vs data events in CloudTrail

---

## Key Learnings

- CloudTrail provides AWS audit visibility
- CloudWatch enables real-time monitoring
- SNS supports automated alerting
- Monitoring pipelines require proper configuration
- Region and event selector settings impact logging visibility

---

## Security Insights

- Monitoring helps detect suspicious cloud activity
- Alerts improve response time during incidents
- Misconfigured logging can create visibility gaps
- Continuous monitoring is essential in cloud security

---

## Simulated Security Events

- CPU utilization spike
- S3 bucket operations
- IAM activity generation
- Login monitoring attempts

---

## Screenshots Included

- CloudTrail trail configuration
- S3 activity logs
- CloudWatch CPU metrics
- CPU spike graph
- SNS email alerts
- Alarm state changes
- Event selector configuration

---

## Challenges Faced

- CloudTrail management event visibility issues
- Region-related monitoring confusion
- Event selector configuration troubleshooting

---

## Final Outcome

Built a foundational AWS monitoring and detection workflow capable of:
- Logging AWS activity
- Monitoring EC2 behavior
- Sending automated alerts
- Investigating cloud activity
- Understanding monitoring pipeline configuration

---

## Skills Developed

- Cloud monitoring
- AWS logging
- Alert configuration
- Detection workflows
- Security troubleshooting
- Monitoring analysis

---

## Next Step

- Week 4: Incident Response & Security Scenarios
