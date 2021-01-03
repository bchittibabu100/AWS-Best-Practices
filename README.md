# AWS-Best-Practices
1. Try avoid using Bastion host just to execute shell commands instead use AWS System manager SSM Run command utility
2. Enable VPC Security Group monitoring and revert if any modifications done to the Security group automatically using below approach.
        https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=security-group-change-auto-response&templateURL=https://s3.amazonaws.com/awsiammedia/public/sample/revertsecuritygroupchanges/security-group-change-auto-response.yaml
3.     
