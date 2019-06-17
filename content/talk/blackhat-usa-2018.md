+++
date = 2018-02-07
lastmod = 2018-02-07

title = "Automated Defense using Cloud Services for AWS, Azure and GCP"

time_start = 2018-08-04T09:30:00
time_end = 2018-08-07T18:00:00

abstract = """
Monitoring for attacks and defending against them in real-time is crucial. Defending our cloud infrastructure during attacks can prove to nightmare even with the currently available solutions in the market. We live in cloud first era where the cloud is our first choice of deployment due to the convenience and scalability. In this training we will learn how to defend our cloud infrastructure using Serverless technologies and Elastic Stack. Elasticstack will collect, analyse logs and triggers alerts based on configured rule-set. Serverless stack drives the defence to perform automated blocking. It will be configured based on the use case and type of attacks. The currently solution works on AWS, Azure and GCP. It can be extended for other providers and custom solutions like in house firewalls, IPS, etc.

The world is advancing towards accelerated deployments using DevOps and Cloud technologies. Automated defence will solve the modern world security challenges using near real-time alerting system, serverless technologies and centralised monitoring system.
"""
abstract_short = ""
event = "Blackhat USA 2018"
event_url = "https://www.blackhat.com/us-18/training/automated-defense-using-cloud-services-for-aws-azure-and-gcp.html"
location = "Mandalay Bay, Las Vegas, USA"

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["deep-learning"]

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.

#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

**Scenarios**

- SSH Bruteforce detection & defense
- Content Management System Audit analysis
- VPC flow logs to defend cloud services (AWS)
- IAM CloudTrail logs to detect and defend against backdoors (AWS)
- Container logs to audit Kubernetes security
Cloud Custodian for automated compliance


**Participants will get**

- Step by Step Gitbook covering the entire training (html, pdf, epub, mobi)
- Custom Ansible Playbooks
- Automated Defence Solution for AWS, Azure, GCP


**Some of the topics and techniques covered will include (at a minimum):**

Day one starts by setting the stage for automated defence by tackling Centralised Monitoring & Alerting System. 

- Understanding limitations of existing solutions
- Setting & Hardening Elasticstack using Ansible Playbooks
- Configuring Infrastructure to send logs
- Attack patterns analysis and detection
- Building attack monitoring dashboards
- Setting up near real-time alerts (slack, email, etc.)


Day two focus on advancing the setup by adding serverless stack to defend against the Infrastructure based on the near real-time alerts to match DevOps speed.

- Getting started with serverless
- Deploying serverless stack for defence
- Automated attack generation
- Automated defence using serverless stack
- Near real-time alerts & defence with different attack simulations
- Defenders CTF with scenarios
- Best practices and deployment strategies

> We will be deploying mostly in Amazon Web Services, with some demonstrations on Microsoft Azure and Google Cloud Platform. But serverless defence code will be given for three clouds.


### WHO SHOULD TAKE THIS COURSE

- Security Engineers & Analysts
- SOC Teams
- DevOps Teams
- Who is interested in automating security monitoring

### STUDENT REQUIREMENTS

- Able to use Linux CLI
- Basic understanding of TCP/IP
- Security Experience would be plus
- Understanding about different cloud providers will be advantage

### WHAT STUDENTS SHOULD BRING

- Laptop with admin/root privileges for VM setup and wireless connectivity
- Students MUST sign up for AWS, Azure, GCP accounts before training begins


### WHAT STUDENTS WILL BE PROVIDED WITH

- Customised VM with all the required tools installed
- Step by Step Gitbook covering the entire training (html, pdf, epub, mobi)
- Custom Ansible Playbooks
- Automated Defence Solution for AWS, Azure, GCP