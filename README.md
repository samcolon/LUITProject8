# LUITProject8
3 Tier Architecture CloudFormation templates with Bastion Host


********* Important **********

1--Deploy the templates in order: 1-Web, 2-Bastion, 3-App, 4-Data.
2--Make sure you fill out all parameter fields with your own VPC info for each CloudFormation template.
3--In the Bastion Host SG you need to add an inbound and outbound RDP rule with the Source being your IP address.
