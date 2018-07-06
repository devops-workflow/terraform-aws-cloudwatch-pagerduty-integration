# terraform-aws-cloudwatch-pagerduty-integration

Manage AWS Cloudwatch to Pagerduty notification integration

- Per service
  - Create SNS topic
  - Subscription: HTTPS with Pagerduty service integration URL

- Outputs
  - SNS Topic: Name, ARN

  Alarms will use SNS topic to send to Pagerduty
