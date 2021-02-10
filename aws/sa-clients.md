---
author: Alex Nelson
---

# Erie Insurance [[ERIEINDEMNITY]{.smallcaps}]{.tag tag-name="ERIEINDEMNITY"} {#erie-insurance}

## MEETING with Steve Schmitt RE: Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-steve-schmitt-re-erie-insurance}

\[2020-04-21 Tue 16:01\]

## [DONE]{.done .DONE} Explore Marklogic server architecture in more detail {#explore-marklogic-server-architecture-in-more-detail}

\[2020-04-22 Wed 14:16\]

## MEETING with Marklogic meeting for Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-marklogic-meeting-for-erie-insurance}

\[2020-04-27 Mon 12:12\]

## MEETING with ATI Metals - troubleshooting Sagemaker [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-ati-metals---troubleshooting-sagemaker}

nil:END: \[2020-04-30 Thu 14:20\]

## MEETING with Marklogic about Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-marklogic-about-erie-insurance}

nil:END: \[2020-04-30 Thu 09:10\]

## MEETING with Erie Insurance - WAF review for Marklogic [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance---waf-review-for-marklogic}

\[2020-04-23 Thu 10:01\]

## [DONE]{.done .DONE} Write up and send out notes from Marklogic review for Erie Insurance {#write-up-and-send-out-notes-from-marklogic-review-for-erie-insurance}

\[2020-04-30 Thu 10:44\]

## MEETING with AWS Control Tower Activation Day [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-aws-control-tower-activation-day}

\[2020-05-27 Wed 10:00\]

## MEETING with Splunk RE: Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-splunk-re-erie-insurance}

nil:END: \[2020-05-26 Tue 13:21\]

## MEETING with Erie Insurance RE: Billing processes and how to align with their system [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-billing-processes-and-how-to-align-with-their-system}

\[2020-05-21 Thu 10:24\]

## MEETING with Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance}

\[2020-05-20 Wed 16:02\]

## MEETING with WAF review and update. [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-waf-review-and-update.}

\[2020-05-06 Wed 14:15\]

## MEETING with Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-1}

nil:END: \[2020-05-08 Fri 13:36\]

## MEETING with Marklogic RE: Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-marklogic-re-erie-insurance}

\[2020-05-11 Mon 13:10\]

## [DONE]{.done .DONE} Skill up on Redshift {#skill-up-on-redshift}

\[2020-05-12 Tue 12:03\]

## [DONE]{.done .DONE} Skill up on Elasitic Beanstalk {#skill-up-on-elasitic-beanstalk}

\[2020-05-12 Tue 12:03\]

## MEETING with Matt Chastain RE: Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-matt-chastain-re-erie-insurance}

nil:END: \[2020-05-12 Tue 15:59\]

## MEETING with Analytics Learning RE: Loading data into Redshift [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-analytics-learning-re-loading-data-into-redshift}

\[2020-05-28 Thu 12:00\]

## MEETING with Erie Insurance RE: Bi-weekly meeting [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-bi-weekly-meeting}

nil:END: \[2020-06-05 Fri 13:33\]

## MEETING with Mark Logic RE: Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-mark-logic-re-erie-insurance}

\[2020-06-08 Mon 12:00\]

## MEETING with Erie Insurance RE: Cost Optimization [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-cost-optimization}

\[2020-06-09 Tue 13:37\]

## [TODO]{.todo .TODO} Research network connectivity for Erie Insurance RE consolidated onramp for all cloud providers {#research-network-connectivity-for-erie-insurance-re-consolidated-onramp-for-all-cloud-providers}

\[2020-06-09 Tue 13:45\]

## MEETING with Steve Schmitt and Marin Mengesha RE: EDP calculations for Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-steve-schmitt-and-marin-mengesha-re-edp-calculations-for-erie-insurance}

\[2020-06-10 Wed 09:40\]

## MEETING with Steve Schmitt RE: Erie [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-steve-schmitt-re-erie}

\[2020-06-10 Wed 11:33\]

## MEETING with AWS Insurance BD Team [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-aws-insurance-bd-team}

nil:END: \[2020-06-15 Mon 15:01\]

## [DONE]{.done .DONE} Expose MSK cluster to the internet {#expose-msk-cluster-to-the-internet}

### Start with default cluster

1.  Create Internet gateway

2.  Attach the Internet Gateway to the MSK VPC

3.  Add the Internet Gateway into the Routing Table for the MSK VPC

4.  Create a Network Load Balancer for each Availability Zone

    1.  Choose Internet facing

    2.  Add TCP Listeners for ports

    3.  Make sure listener is in the MSK VPC

        1.  Port 2181 is Zookeeper Port

        2.  Port 9092 is Non-TLS for Producers and Consumers

        3.  Port 9094 is TLS for Producers and Consumers

    4.  Get DNS names of the brokers and zookeper nodes from the MSK
        client information

        1.  Perform a DNS lookup on each entry and record the IP address
            that is returned

            \[2020-08-27 Thu 09:48\]

## MEETING with Erie Insurance RE: MarkLogic cost optimization [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-marklogic-cost-optimization}

### Review of spreadsheet from Brian Novacek

### Review of notes from last meeting

### Usage of RI for MarkLogic instances since they will be relatively static

### Staging is manual setup.

1.  Takes about an hour.

2.  Plans to automate in the future.

3.  Data Team is responsible for loading/unloading of data from
    MarkLogic

### All lower environments are using versions of production data

\[2020-09-11 Fri 11:09\]

## MEETING with Erie RE: Weekly touch base [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-re-weekly-touch-base}

### Middle management has gutted and stopped most of the cloud inititives that would be the most beneficial

\[2020-09-11 Fri 12:56\]

## MEETING with Erie Insurance RE: Bi-weekly sync [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-bi-weekly-sync}

\*\* \[2020-09-11 Fri 13:03\]

## MEETING with MarkLogic RE: Status [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-marklogic-re-status}

\[2020-09-15 Tue 12:03\]

### No native JDBC driver from MarkLogic

### ODBC is the only connection type

### Postgres driver can be used to connect into ODBC

### PWC seems to be a blocker for Glue. Not sure what the issue is.

## [TODO]{.todo .TODO} Investigate tools for data lineage [[ERIEINDEMNITY]{.smallcaps}]{.tag tag-name="ERIEINDEMNITY"} {#investigate-tools-for-data-lineage}

\[2020-09-16 Wed 16:03\]

## [TODO]{.todo .TODO} Clarify what the maximum number of query users is for Redshift [[ERIEINDEMNITY]{.smallcaps}]{.tag tag-name="ERIEINDEMNITY"} {#clarify-what-the-maximum-number-of-query-users-is-for-redshift}

\[2020-09-16 Wed 16:05\]

## [TODO]{.todo .TODO} Write up comparison betweeen CloudTrail and AWS Config [[ERIEINDEMNITY]{.smallcaps}]{.tag tag-name="ERIEINDEMNITY"} {#write-up-comparison-betweeen-cloudtrail-and-aws-config}

\[2020-09-16 Wed 16:06\]

## [TODO]{.todo .TODO} Investigate XML import into Redshift [[ERIEINDEMNITY]{.smallcaps}]{.tag tag-name="ERIEINDEMNITY"} {#investigate-xml-import-into-redshift}

\[2020-09-16 Wed 16:07\]

## [TODO]{.todo .TODO} Get Redshift roadmap for features and enhancements [[ERIEINDEMNITY]{.smallcaps}]{.tag tag-name="ERIEINDEMNITY"} {#get-redshift-roadmap-for-features-and-enhancements}

\[2020-09-16 Wed 16:08\]

## [TODO]{.todo .TODO} Investigate Data Inventory tool [[ERIEINDEMNITY]{.smallcaps}]{.tag tag-name="ERIEINDEMNITY"} {#investigate-data-inventory-tool}

\[2020-09-16 Wed 16:09\]

## [TODO]{.todo .TODO} Explore ways to export data columns and types into IBM Infosphere [[ERIEINDEMNITY]{.smallcaps}]{.tag tag-name="ERIEINDEMNITY"} {#explore-ways-to-export-data-columns-and-types-into-ibm-infosphere}

\[2020-09-16 Wed 16:09\]

## [TODO]{.todo .TODO} Investigate recommendations for data governance tool [[ERIEINDEMNITY]{.smallcaps}]{.tag tag-name="ERIEINDEMNITY"} {#investigate-recommendations-for-data-governance-tool}

\[2020-09-16 Wed 16:10\]

## [TODO]{.todo .TODO} IAM Best practices for Redshift [[ERIEINDEMNITY]{.smallcaps}]{.tag tag-name="ERIEINDEMNITY"} {#iam-best-practices-for-redshift}

\[2020-09-16 Wed 16:11\]

## MEETING with Amit Sen RE: MAP program for Redshift for Erie [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-amit-sen-re-map-program-for-redshift-for-erie}

\[2020-09-18 Fri 16:30\]

### Need to review spreadsheet from Brian Novachek with Redshift specialist

### REach out to

1.  Brahmarouthu, Sandeep \<brahmaro\@amazon.com\>

2.  daniel brock Brockda\@amazon.com

3.  thottr\@amazon.com - rajeev thottathil

### Ramping it down to 100K of ARR

### Including Phase 1 and future phases are going to come later

## MEETING with AWS Bi-Weekly Teams Meeting [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-aws-bi-weekly-teams-meeting}

\[2020-09-25 Fri 13:31\]

### SALM - SSO discussion

1.  AD and IAM mixture

2.  Very few workload or application groups

3.  Technical and process limitations

### MS Access

1.  Top thee approaches for replacement as if new code

2.  Possibly Honeycode?

3.  Look for other alternatives

### Snowball

1.  Move splunk enterprise to cloud

2.  Check on ordering snowball - Ask fellow SA\'s

## MEETING with Erie Insurance RE: Weekly enterprise call [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-weekly-enterprise-call}

\[2020-09-25 Fri 11:30\]--\[2020-09-25 Fri 12:30\] \*\*

## MEETING with Steve Schmitt RE: Erie Cost Optimisations for MAP [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-steve-schmitt-re-erie-cost-optimisations-for-map}

\[2020-09-23 Wed 12:30\]

## MEETING with Erie MAP [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-map}

\[2020-09-23 Wed 11:28\]

### 128k/Month

### 12 months

### List reductions

1.  Redhat reduction etc

## MEETING with Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-2}

\[2020-09-22 Tue 13:03\]

### Dealing with lack of information

### Business is not aware of cloud economics

### Looking to create repeatable governance

## MEETING with Erie Insurance RE: PSS Cost Optimization [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-pss-cost-optimization}

\[2020-09-28 Mon 09:00\]

### Using Kinesis to pump CloudWatch logs into Splunk

\*\*

## [DONE]{.done .DONE} Review Kineses configuration for pumping data into Splunk {#review-kineses-configuration-for-pumping-data-into-splunk}

\[2020-09-28 Mon 09:13\]

## MEETING with ValueMomentum RE: Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-valuemomentum-re-erie-insurance}

\[2020-09-28 Mon 15:04\]

### 250 Onshore working for Erir

### Another 250 approx in Hyderabad

### Potential of using Nicus as Erie\'s cost/financial management

## MEETING with Erie Insurance RE: Personal Lines Cost Review [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-personal-lines-cost-review}

\[2020-09-29 Tue 09:31\]

### SAS attached through Athena

## MEETING with Erie Insurance RE: PCS Cost Optimization [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-pcs-cost-optimization}

\[2020-09-30 Wed 09:02\]

### PCS - Platform Common Services

\*\*

## MEETING with Erie Insurance RE: Actuarial Workload [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-actuarial-workload}

\[2020-09-30 Wed 13:00\]

### Colabrio is call center solution

### Looking into Transcribe - multiple avenue

## MEETING with Erie Insurance RE: VPC Cost Optimization [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-vpc-cost-optimization}

\[2020-10-01 Thu 09:36\]

### 2021 plan is to go to 10g Equinix connection

### AT&T is network provider

## MEETING with Erie Team RE: Credits for Snowball [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-team-re-credits-for-snowball}

\[2020-10-01 Thu 15:44\] \*\*

## MEETING with Erie Insurance RE: Weekly Enterprise Review [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-weekly-enterprise-review}

\[2020-10-02 Fri 11:35\] \*\*

## MEETING with Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-3}

\[2020-10-02 Fri 13:29\]

### Kafka

### Event Driven Tagging (IVANS uses XSLT to parse xml and convert to agent management system)

### ActiveMQ

## MEETING with Splunk RE: Erie Insurance data load [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-splunk-re-erie-insurance-data-load}

\[2020-10-05 Mon 15:47\]

## MEETING with Erie Insurance RE: Snowball proceedure and handling [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-snowball-proceedure-and-handling}

\[2020-10-15 Thu 10:14\] \*\*

## MEETING with Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-4}

nil:END: \[2020-07-01 Wed 14:03\]

## MEETING with Erie Insurance RE: RI vs Savings Plans [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-ri-vs-savings-plans}

### Discussion of RI vs Savings Plans and what the options are prior to presenting to senior leadership

\[2020-12-02 Wed 11:12\]

## MEETING with Matt Chastain RE: Erie Insurance and SSO [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-matt-chastain-re-erie-insurance-and-sso}

\*\* \[2020-12-07 Mon 14:05\]

## MEETING with Erie Insurance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-5}

### PAYGO architecture and OneShield1

1.  Oneshield

    1.  Oracle RAC

    2.  J2EE

    3.  ActiveMQ

    4.  UI layer

    5.  Tessle integration layer

        \[2020-12-11 Fri 15:05\]

## MEETING with Erie Insurance RE: Monthly status meeting [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-monthly-status-meeting}

## WAR Levels

## cc

\[2020-12-16 Wed 17:04\]

## [TODO]{.todo .TODO} Contact Josh (TAM Manager) about how to activate enterprise support for their accounts {#contact-josh-tam-manager-about-how-to-activate-enterprise-support-for-their-accounts}

\[2020-12-16 Wed 17:04\]

## MEETING with Erie Insurance RE: Snowball performance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-snowball-performance}

### Separate VLAN

### Machines might need 32+ GB of RAM

### Using the S3 interface

### IO stats on Linux (source) machine were all good

### Virtualized infrastructure

\[2020-12-22 Tue 14:45\]

## MEETING with Erie RE: OSPAS Paygo design session \#4 [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-re-ospas-paygo-design-session-4}

### Review of prior meetings

### Using webshphere-liberty image

### Cloud COE needs to get engaged about architecture

1.  Security

2.  Logging

3.  Underlying service

### 5 containers

1.  Services

2.  Robotic Processor

3.  ActiveMQ

4.  OS Ent

5.  OS Designer

### Can potentially use SQS instead of custom ActiveMQ container

### Possibly going to use Mendix as UI

### There is existing custom UI based .NET that is on premises right now

### Need to have broader converssation with Adam and David Poulliott

\[2020-12-21 Mon 14:40\]

## [DONE]{.done .DONE} Prepare list of questions around speed of loading data into Snowball. Erie was experiencing slow transfer {#prepare-list-of-questions-around-speed-of-loading-data-into-snowball.-erie-was-experiencing-slow-transfer}

\[2020-12-18 Fri 13:41\]

## [TODO]{.todo .TODO} Check if Erie can use a public VIF as well as the TG VIF on the same circuit {#check-if-erie-can-use-a-public-vif-as-well-as-the-tg-vif-on-the-same-circuit}

\[2020-12-18 Fri 13:43\]

## [TODO]{.todo .TODO} Qlik connections from On Premesis to AWS Redshift for Erie Insurance {#qlik-connections-from-on-premesis-to-aws-redshift-for-erie-insurance}

\[2020-12-18 Fri 14:04\]

## [TODO]{.todo .TODO} GitLab runner connection to RedShift for Erie Insurance {#gitlab-runner-connection-to-redshift-for-erie-insurance}

### Using runner to push and execute DDL within Redshift

\[2020-12-18 Fri 14:05\]

## MEETING with Erie Insurance RE: Paygo [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-paygo}

\*\* \[2020-12-18 Fri 14:41\]

## MEETING with Erie RE: Weekly Touch Base [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-re-weekly-touch-base-1}

\*\* \[2020-12-18 Fri 13:36\]

## MEETING with Erie Insurance RE: Qlik data needs [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-insurance-re-qlik-data-needs}

\[2020-10-29 Thu 11:06\]

### DataSync possible for transfering files to FSX

### 5mb to 20GB

### Up to 1800 users

### CSV and Qlik files

\*\*

## MEETING with Erie RE: [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-re}

\[2020-10-26 Mon 15:12\]

## MEETING with Erie RE: Teams Access [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-re-teams-access}

\[2021-01-13 Wed 13:32\]

### Erie is deleting and re-adding account

## MEETING with Erie RE: WAR for PCDS [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-re-war-for-pcds}

\[2021-01-14 Thu 09:00\]

### 1/21/2021 Go live date

## MEETING with Erie RE: Snowball Performance [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-re-snowball-performance}

\[2021-01-19 Tue 09:00\] \*\*

## MEETING with Erie RE: PAYGO OSPAS POC [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-re-paygo-ospas-poc}

\[2021-01-20 Wed 12:07\]

### Performance testing

1.  Load

    1.  ramped

    2.  anticipated load first

    3.  Ramp up to overall laod for existing workloads

2.  UI

3.  New business and endorsement transactions

4.  All Non-OSPAS services will be stubbed out

### Mendix will be used for UI

### Intent for POC

1.  Leverage AWS to validate

    1.  Using automation for infrastructure

    2.  Performance to meet anticipated needs

    3.  Scaling to meet anticipated needs

### Might use Amazon MQ (Still resistance)

### Going to fork Erie Secure Business (ESB)

1.  External-facing systems

    1.  Agent system of record

    2.  Billing/pay plan options

    3.  Address standardization

    4.  Reports

    5.  Business Valuation

    6.  Additional third party systems

2.  Internal systems

    1.  Ratabase

    2.  Print

3.  Need to convert JSON (Mendix) to DXF (OneShield)

4.  Mendix

    1.  will talk to services.erie over public internet

    2.  services.erie is hosted out of erie datacenter

    3.  Integration layer is in the works that will extend that out to
        the (\~ 6 months out)

### AWS infrastructure

1.  Potentially using RDS Oracle for database

2.  Cloudwatch

3.  ALB discussion

## MEETING with Erie RE: OSPAS PAYGO [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-erie-re-ospas-paygo}

\[2021-01-22 Fri 14:01\]

### Planning on Terraform in container on AWS

1.  Hashicorp recommends against this pattern

2.  terraform can run in Lambda \> lower cost

    \*\*

## [TODO]{.todo .TODO} Erie: Schedule broader conversation around CI/CD architecture and how to best integrate with AWS {#erie-schedule-broader-conversation-around-cicd-architecture-and-how-to-best-integrate-with-aws}

\[2021-01-22 Fri 14:33\]

## MEETING with Steve Schmitt RE: Erie strategic approach [[MEETING]{.smallcaps}]{.tag tag-name="MEETING"} {#meeting-with-steve-schmitt-re-erie-strategic-approach}

\[2021-01-25 Mon 09:15\]

### Data

1.  use data gravity to pull other workloads

2.  leverage Marko to get traction

3.  lakehouse architecture

### Containers

1.  Need strategy

2.  EKS Anywhere

3.  strategy -\> PWC -\> Erica
