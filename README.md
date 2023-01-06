# Give your Application Auto-Deploy Superpowers

A CI-CD pipeline for a client/server TypeScript project hosted on AWS EC2 and CloudFront and monitored with Prometheus,
with E-mail notifications used for alerts.

## Product

UdaPeople(Cloud-Based Software): a fictional revolutionary concept in Human Resources which promises to help small businesses care better for their most valuable resource: their people

![Diagram of CI/CD Pipeline we will be building.](udapeople.png)


### Instructions

* Deploying Working, Trustworthy Software
* Configuration Management
* Turn Errors into Sirens


### Udapeople Project: Deploying Working, Trustworthy Software


 
|CRITERIA|MEETS SPECIFICATIONS |Files |
|:-----|:-----|:-----|
|Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.|Public git repository with project code. |[URL01](https://github.com/github.com/lebogangolifant/udapeople)<br>https://github.com/lebogangolifant/udapeople|[![url1](https://img.shields.io/badge/URL01-EXISTS-brightgre)](https://github.com/lebogangolifant/udapeople) |
||Evidence of code-based CI/CD configuration in the form of yaml files in your git repository.|[config.yml](./.circleci/config.yml)|[![config.yml](https://img.shields.io/badge/config.yml-EXISTS-brightgre)](./.circleci/config.yml) <br> [![CircleCI](https://circleci.com/gh/github.com/lebogangolifant/udapeople.svg?style=shield&circle-token=499c794914a6668bd794027edc74d9400d7a361f)](https://app.circleci.com/pipelines/github.com/lebogangolifant/udapeople?branch=master&filter=all)  |
||***Console output of various pre-deploy job failure scenarios:***||
||Build Jobs that failed because of compile errors. |[SCREENSHOT01](./udapeople-screenshots/SCREENSHOT01.png)|
||Failed unit tests. |[SCREENSHOT02](./udapeople-screenshots/SCREENSHOT02%20.png)|
||Failure because of vulnerable packages. |[SCREENSHOT03](./udapeople-screenshots/SCREENSHOT03%20.png)|
||An alert from one of your failed builds. |[SCREENSHOT04](./udapeople-screenshots/SCREENSHOT04%20.png) e-mail Notification<br> |
||***Evidence in your code that:*** Compile errors have been fixed.<br>Unit tests have been fixed.<br>All critical security vulnerabilities caught by the “Analyze” job have been fixed|[.circleci](./.circleci)<br>[backend](./backend)<br>[frontend](./frontend)|
|Utilize a configuration management tool to accomplish deployment to cloud-based servers.|Console output of appropriate failure for infrastructure creation job (using CloudFormation). |[SCREENSHOT05](./udapeople-screenshots/SCREENSHOT05.png)|
||Console output of a smoke test job that is failing appropriately. |[SCREENSHOT06](./udapeople-screenshots/SCREENSHOT06.png)|
||Console output of a successful rollback after a failed smoke test. |[SCREENSHOT07](./udapeople-screenshots/SCREENSHOT07.png)|
||Console output of successful promotion of new version to production in CloudFront. |[SCREENSHOT08](./udapeople-screenshots/SCREENSHOT08.png)|
||Console output of successful cleanup job that removes old S3 bucket and EC2 instance. |[SCREENSHOT09](./udapeople-screenshots/SCREENSHOT09.png)|
||Evidence that the deploy jobs only happen on the `master` branch. |[SCREENSHOT10](./udapeople-screenshots/SCREENSHOT10.png)|
||Evidence of deployed and functioning front-end application in CloudFront. |[URL03_SCREENSHOT](./udapeople-screenshots/URL03_SCREENSHOT.jpg)|
||Evidence of healthy back-end application. |[URL02]<br>[URL04_SCREENSHOT](./udapeople-screenshots/URL04_SCREENSHOT%2.png)|
<h3 align="center">Section 3: Turn Errors into Sirens</h3>  

|CRITERIA|MEETS SPECIFICATIONS |Files |
|:-----|:-----|:-----|
|Surface critical server errors for diagnosis using centralized logging.|Evidence of Prometheus Server. |[URL05]<br>[URL05_SCREENSHOT](./udapeople-screenshots/URL05_SCREENSHOT%20.png)|
||Evidence that Prometheus is monitoring memory, cpu and disk usage of EC2 instances. |[SCREENSHOT11 *CPU*](./udapeople-screenshots/SCREENSHOT11-CPU%20.png)<br>[SCREENSHOT11 *Disk Usage*](./udapeople-screenshots/SCREENSHOT11-DISK%20.png)<br>[SCREENSHOT11 *Memory*](./screenshots/SCREENSHOT11-MEMORY%20.png)|
||Evidence that Prometheus and AlertManager send alerts when certain conditions exist in the EC2 instance. |[SCREENSHOT12](./udapeople-screenshots/SCREENSHOT12%20.png)|


### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
