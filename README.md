# MonitoringRPAInfraUsingAWSConfig
Monitoring RPA Infrastructure using AWS Connfig

Notes:

- Tag the EC2 Instances with Key as "RPA" and value as "RPA"
- Install SSM agent in the EC2 Instances
- Ensure that EC2 Instances have the permission for "SSMManagedInstanceCore"
- Adjust Lambda Timeout if needed. I set it to 10 seconds while testing
