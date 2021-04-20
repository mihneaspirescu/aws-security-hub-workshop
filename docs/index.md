# Overview

This workshop is designed to get you familiar with AWS Security Hub so that you can better understand how you would use it in your own AWS environment(s). This workshop is broken into two sections. The first section will guide you through a demonstration of the features and functions of Security Hub. The second section will show you how to use Security Hub to import findings from different data sources, analyze findings so you can prioritize response work, and implement responses to findings to help improve your security posture. 



* **Level**: Intermediate
* **Duration**: 2 - 3 hours
* **<a href="https://www.nist.gov/cyberframework/online-learning/components-framework" target="_blank">CSF Functions</a>**: Detect, Respond
* **<a href="https://d0.awsstatic.com/whitepapers/AWS_CAF_Security_Perspective.pdf" target="_blank">CAF Components</a>**: Detective, Responsive
* **<a href="https://awssecworkshops.com/getting-started/" target="_blank">Prerequisites</a>**: AWS Account, Admin IAM User

## Scenario

Your company is new to the cloud and is steadily migrating workloads into your cloud environment.  To detect security events you are using a mix of 3rd party services, custom scripts, and AWS services.  As a security analyst you are responsible for establishing a solution that will give visibility into security findings related to your AWS environment so that you can properly prioritize and respond to findings.   

## Architecture

For this workshop there will be multiple pieces of infrastructure and AWS services deployed in order to facilitate creation of security findings in Security Hub.  

Multiple EC2 instances will be launched to facilitate the generation of findings from GuardDuty & Inspector.  Additionally these instances will be used to help with demonstration of integration of custom findings into Security Hub.

Multiple AWS services will be configured in the workshop to help facilitate the generation of Security Hub findings.  These services include:

* Security Hub
* GuardDuty 
* Secrets Manager
* Inspector
* Config

## Region
Please use **us-east-1 (Virgina)** for this workshop.

## Modules

This workshop is broken up into setup and then four modules: 

0. [Initial Environment Setup ](./00-environment-setup.md)
1. [AWS Security Hub Walk Through ](./01-security-hub-walk-through.md)
2. [Amazon GuardDuty Walk Through ](./02-guardduty-walk-through.md)
3. [Custom Insights and Custom Findings](./03-custom-insights-findings.md) 
4. [Remediation and Response Custom Action](./04-remediation-and-response.md) 


