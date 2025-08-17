# Automation pipeline: Turn on the Ec2 instances
This repository features an Azure Pipeline designed to automate the process of starting and managing an EC2 instance in AWS. It includes commands to launch a new EC2 instance, monitor its status, and manage its lifecycle efficiently. This setup helps streamline infrastructure management, reduce manual effort, and ensure that instances are started and checked reliably within your deployment workflows.

### 🛠️For the use the schema
* Azure devOps account
* * Create new pipeline
* * Add variables in the pipeline
```
AWS_ACCOUNT_ACCESS_KEY_ID
AWS_ACCOUNT_SECRET_ACCESS_KEY
AWS_EC2_INSTANCE_ID
AWS_EC2_REGION
```
* Aws account
* * EC2
* * RDS

### ⚡Triggers in Azure Devops
We can configure pipelines to run on the days we need:
- Create pipeline in Azure Devops
- Setting pipeline with this repository and azure-pipelines.yml
- Select Triggers and Scheduled
- Scheduled detail:

<div align="center">
  <img height="300" width="90%" src="triggers.png"  />
</div>


