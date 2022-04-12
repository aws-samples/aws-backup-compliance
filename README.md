<p align="center">
</p>

# Automating Backup Compliance in AWS using AWS Backup Audit Manager


1. **Automated backup compliance with AWS Backup Audit Manager and AWS Security Hub**
	
Integrates Backup Audit Manager with Security Hub. The solution provisions a AWS Backup Audit Manager framework with 5 default controls (and you can additional controls to the template). These generate and trigger AWS Config rules and the rule evaluations are converted to Security Hub findings.

2. **Devops automation for backup compliance in AWS using AWS Backup Audit Manager**
	
Integrates Backup Audit Manager with AWS CodePipeline, enabling developers to embed automated backup controls for AWS resources in their development workflows and shift left with backup compliance in AWS. A git check-in triggers CodePipeline to build, deploy and update AWS Backup Audit Manager framework controls to the managed accounts. The solution uses the Backup Audit Manager framework stackset in the developer account as the basis for provisioning stacks into selected managed accounts across specified AWS Regions



