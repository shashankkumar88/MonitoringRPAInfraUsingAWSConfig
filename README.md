# MonitoringRPAInfraUsingAWSConfig
Monitoring RPA Infrastructure using AWS Connfig

Link to Article
https://www.linkedin.com/pulse/monitoring-your-rpa-infrastructure-using-aws-config-shashank-kumar/?trackingId=7%2FPOQWWvSXWsONUoR6N6Sw%3D%3D

Notes:

- Tag the EC2 Instances with Key as "RPA" and value as "RPA"
- Install SSM agent in the EC2 Instances
- Ensure that EC2 Instances have the permission policies for "SSMManagedInstanceCore"
- Adjust Lambda Timeout if needed. I set it to 10 seconds while testing
- Lambda needs to have the permission policies for "AWSConfigRole" and "AmazonSSMAutomationRole"
- Lambda can be modified to trigger SNS notification on non-compliance 
