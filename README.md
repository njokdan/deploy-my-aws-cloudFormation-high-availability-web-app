# Udactiy/ALX-T Cloud DevOps ND - High Availability web app using CloudFormation

This is a project for the [Udacity Devops Engineer Nanodegree](https://eu.udacity.com/course/cloud-dev-ops-nanodegree--nd9991) program.

The task is to deploy a high availability static website. The website should be hosted on servers within private subnets. All trafic to the servers should be routed through NAT gateways located in public subnets.
For high availability there shouldn't be any single point of failure and we should leverage auto scaling as well as security best practices.

Below is the infrastructure diagram that visualises what this cloudformation script deploys:

![Diagram](./Daniel-Njoku-Project-2-Deploy-aws-cloudFormation-high-availability-web-app(June 2022).png)