---
title: "Week 5 Worklog"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Week 5 Objectives:

* Learn different approaches for connecting multiple Amazon VPCs.
* Compare Amazon VPC Peering with AWS Transit Gateway for multi-network architectures.
* Practice configuring network connectivity between VPCs on AWS.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Study the architecture and use cases of Amazon VPC Peering.<br>- Learn how to connect VPCs within the same Region, across Regions, and across AWS accounts.<br>- Review the limitations of VPC Peering. | 15/05/2026 | 15/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 3 | - Practice creating a VPC Peering connection between two VPCs.<br>- Accept the peering request and verify the connection status. | 16/05/2026 | 16/05/2026 | https://000019.awsstudygroup.com/ |
| 4 | - Configure Route Tables to enable communication between peered VPCs.<br>- Verify connectivity between EC2 instances located in different VPCs. | 17/05/2026 | 17/05/2026 | https://000019.awsstudygroup.com/ |
| 5 | - Learn the architecture of AWS Transit Gateway and the Hub-and-Spoke networking model.<br>- Compare the advantages and limitations of Transit Gateway versus VPC Peering. | 18/05/2026 | 18/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 6 | - Practice creating an AWS Transit Gateway.<br>- Attach multiple VPCs using Transit Gateway Attachments.<br>- Configure Transit Gateway Route Tables. | 19/05/2026 | 20/05/2026 | https://000020.awsstudygroup.com/ |
| 7 | - Verify routing between all connected VPCs.<br>- Test network connectivity.<br>- Remove AWS resources after completing the lab exercises. | 21/05/2026 | 21/05/2026 | https://000020.awsstudygroup.com/ |

### Week 5 Achievements:

* Gained a clear understanding of Amazon VPC Peering and its common use cases.

* Learned the differences between:
  * Same-Region VPC Peering.
  * Cross-Region VPC Peering.
  * Cross-Account VPC Peering.

* Successfully completed the VPC Peering hands-on lab by:
  * Creating a VPC Peering connection.
  * Updating Route Tables.
  * Testing communication between EC2 instances across different VPCs.

* Understood the architecture of AWS Transit Gateway and the Hub-and-Spoke networking model for large-scale environments.

* Successfully completed the Transit Gateway lab by:
  * Creating an AWS Transit Gateway.
  * Attaching multiple VPCs.
  * Configuring Transit Gateway Route Tables.
  * Verifying routing across connected VPCs.
  * Cleaning up AWS resources after completing the lab.

* Developed the ability to determine when to use Amazon VPC Peering or AWS Transit Gateway based on different cloud networking requirements.
