+++
date = 2019-04-08
lastmod = 2019-04-08

title = "AUTOMATED DEFENSE USING CLOUD SERVICES FOR AWS, AZURE AND GCP"

time_start = 2019-08-03T09:30:00
time_end = 2019-08-06T18:00:00

abstract = """
Monitoring for attacks and defending against them in real-time is crucial. The mean time to detect (MTTD) has become an important criteria for cloud admins and SREs. Defending our cloud infrastructure during attacks is a challenge in the best of times and especially difficult when under attack.

In this training, we will learn how to do orchestration for security which enable us to do automated response. Sometimes this approach is also known as Security Orchestration and Automated Response (SOAR). 
We will learn how to utilize cloud native services supplemented by the ELK stack to offer automated response. Cloud native services such as AWS Lambda along with DynamoDB offers the freedom to DevSecOps teams to bring in security without worrying about one more server they need to manage.

Elastic Stack will collect, analyze logs and triggers alerts based on configured rule-set. Serverless stack drives the defense to perform automated response by blocking, slowing down attackers and alerting the defenders. The approach is cloud agnostic and works anywhere where we are able to respond programatically using APIs.
"""
abstract_short = ""
event = "Black Hat USA 2019"
event_url = "https://www.blackhat.com/us-19/speakers/Madhu-Akula.html"
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

During the training, you will be able to orchestrate and see the automated response work for the following scenarios.

**Scenarios**

- SSH Brute-force attacks detection & automated defense
- Popular CMS attack detection and automated analysis for further audit
- Parsing VPC flow logs to defend against network attacks in AWS cloud services
- AWS IAM CloudTrail logs to detect and defend against backdoors planted by attackers
- Container logs to detect and offer automated response in real time for attacks against Kubernetes clusters in GCP
- Automated Security Compliance using cloud native tools such as AWS Config and open source tool such as Cloud Custodian

**Key Take Aways**

- Real-world scenarios where we show how to foil attackers using security orchestration and automated response across cloud providers such as AWS, Azure and GCP
- Ebooks of the training covering all hands-on in a step by step guide (HTML, PDF, EPub, Mobi)
- Git repository of all the custom source code, scripts, playbooks used during the training
- Approaches on how to tailor automated response solutions for the cloud provider you work with
- Orchestration, provisioning playbooks, scripts for setting up the entire cloud infrastructure used for the training labs which includes Terraform, Packer and Ansible

**Some of the topics and techniques covered will include (at a minimum):**

We start day one by setting the stage for automated response by deploying a centralized monitoring & alerting system

- Environment setup for defenders to work with the training labs
- Setting up hardened Elastic Stack using Ansible playbooks and Terraform
- Configuring cloud infrastructure to send logs to centralized monitoring system
- Attack patterns analysis and detection
- Building attack monitoring dashboards
- Setting up near real-time alerts (slack, email, etc.)
- SSH brute-force attack and security response against infrastructure
- Building security dashboards for further analysis
- Detecting the attack and applying real-time defense using automated response
- CMS attack detection and automated analysis for further audit
- Attack audit analysis using security dashboards

We will focus on day two by adding a Serverless stack to defend against the cloud infrastructure based on the near real-time alerts to match DevOps speed

- Deploying the automated defense
- Setting up monitoring system AWS CloudWatch and AWS CloudTrail logs
- Attacking internal services hosted inside the AWS Virtual Private Cloud Service (VPC)
- Detecting internal attacks against cloud services using AWS Flow Logs
- Applying defense for attacks against cloud services
- Abusing metadata and gaining access to compromised AWS IAM keys for users and roles
- Identifying compromised IAM keys usage using AWS CloudTrail logs
- Defending against IAM compromised keys using Serverless (AWS Lambda)
- Setting up automated Kubernetes infrastructure with services
- Monitoring Kubernetes security events for attacks
- Attacking containerized applications in Kubernetes
- Near real-time automated defense against Docker container security attacks
- Automated compliance using AWS Config and Cloud Custodian

### WHO SHOULD TAKE THIS COURSE

- Security Engineers & Analysts
- DevSecOps and Cloud Operations teams
- SOC and Incident Response teams
- Anyone interested in automating defense against security attacks in cloud environments

### STUDENT REQUIREMENTS

- Able to use Linux CLI
- Basic understanding of syste administration
- Security Experience would be plus
- Understanding about different cloud providers will be advantage

### WHAT STUDENTS SHOULD BRING

- Laptop with browser and wireless connectivity
- Students MUST sign up for AWS, Azure, GCP free trail accounts before training begins

### WHAT STUDENTS WILL BE PROVIDED WITH

- Ebooks of the training covering all hands-on in a step by step guide (HTML, PDF, EPub, Mobi)
- Git repository of all the custom source code, scripts, playbooks used during the training
- Orchestration, provisioning playbooks, scripts for setting up the entire cloud infrastructure used for the training labs which includes Terraform, Packer and Ansible