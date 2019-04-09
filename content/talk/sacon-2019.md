+++
date = 2019-02-07
lastmod = 2019-02-07

title = "AUTOMATED DEFENCE USING CLOUD SERVICES FOR AWS, AZURE & GCP"

time_start = 2019-02-15T09:30:00
time_end = 2019-02-15T17:30:00

abstract = """
Monitoring for attacks and defending against them in real-time is crucial. Defending our cloud infrastructure during attacks can prove to nightmare even with the currently available solutions in the market. We live in cloud first era where the cloud is our first choice of deployment due to the convenience and scalability. In this workshop, we will learn how to defend our cloud infrastructure using Serverless and Elastic Stack. Elastic Stack will collect, analyse logs and triggers alerts based on configured rule-set. Serverless stack drives the defence to perform automated blocking. It will be configured based on the use case and type of attacks. The currently solution works on AWS, Azure and GCP. It can be extended for other providers and custom solutions like in house firewalls, IPS, etc.
"""
abstract_short = ""
event = "SACON 2019"
event_url = "https://www.sacon.io/?#madhuakula"
location = "Taj Yeshwantpur, Bengaluru"

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

Some of the real-world scenarios we will be covering during the workshop includes

* SSH Brute-force detection & defence
* Content Management System Audit analysis (Azure)
* AWS IAM CloudTrail logs to detect and defend against backdoors (AWS)
* Container logs to defend Kubernetes security attacks(GCP)

**High Level Overview**

* Environment setup using automated playbook
* Cloud providers accounts configuration
* Setting up hardened Elastic Stack using Ansible playbooks and Terraform
* Configuring cloud infrastructure to send logs to centralized monitoring system
* Attack patterns analysis and detection
* Building attack monitoring dashboards
* Setting up near real-time alerts (slack, email, etc.)
* SSH brute-force attack against infrastructure
* Building security dashboards for analysis
* Detecting the attack and applying real-time defence
* CMS application service attack simulation
* Attack audit analysis using security dashboards
* Deploying the automated defence
* Setting up monitoring system AWS CloudWatch and AWS CloudTrail logs
* Abusing metadata and gaining access to compromised AWS IAM keys for users and roles
* Identifying compromised IAM keys usage using AWS CloudTrail logs
* Defending against IAM compromised keys using Serverless (AWS Lambda)
* Setting up automated Kubernetes infrastructure with services
* Monitoring Kubernetes security events for attacks
* Attacking containerized applications in Kubernetes
* Near real-time automated defence against Docker container security attacks

**ATTENDEE REQUIREMENTS**

* Most of the workshop will be covered using demonstrations and discussions around the scenarios
* Laptop with browser and wireless connectivity would be useful
* Keep a hotspot handy for internet access (if required)