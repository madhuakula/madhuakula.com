+++
date = 2019-09-25
lastmod = 2019-10-25

title = "Breaking & Pwning Docker Containers and Kubernetes Clusters"

time_start = 2019-09-24T09:00:00
time_end = 2019-09-25T17:00:00

abstract = """
This 2 day attack-focused, hands-on training will set you on the path to using common attack techniques against docker, kubernetes, containerized infrastructure. It will help you to learn the approach to follow and the process for testing and auditing containers and Kubernetes clusters. By the end of the training, participants will able to identify and exploit applications running on containers inside Kubernetes clusters with a hands-on approach.

An organization using micro services or any other distributed architecture rely heavily on containers and container orchestration engines like Kubernetes and as such its infrastructure security is paramount to its business operations. This course will set the base for security testers and DevOps teams to test for common security vulnerabilities and configuration weaknesses across containerized environments and distributed systems. It also helps to understand the approach and process to audit the Kubernetes environment for security posture.

* The focus is on the security aspects of the application and the container infrastructure
* The participants will learn the common tools and techniques that are used to attack applications running in containerized environments
* The participants will be introduced to Docker, Kubernetes and learn to assess the attack surfaces applicable for a given application on the cluster.
* The participants will learn how to audit for security based on best practices using tools and custom scripts
"""
abstract_short = ""
event = "Global AppSec Amsterdam 2019"
event_url = "https://globalappsecamsterdam2019.sched.com/event/TjQN"
location = "RAI Amsterdam, Europaplein 24, 1078 GZ Amsterdam, The Netherlands"

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

### Training Outline

* Student training lab setup
* Docker Quick Start
* Docker Advanced Concepts
* Docker-compose
* Portainer
* Docker Security Architecture
    * Namespaces
    * Capabilities
    * Control Groups
* Scenarios
    * Exploiting docker misconfiguration
    * Exploiting Docker Images and Containers
    * Attacking Private Registry
    * Attacking Docker Volumes and Networks
    * Auditing Docker Volumes and Networks
    * Exploiting Container Capabilities to escape
* Docker Integrity Checks
* Container introspection tool - amicontained
* LSM - Apparmor Nginx Profile
* Docker Bench Security Audit
* Container Logging and Monitoring
* Docker Logging
* Docker Events
* Kubernetes Cluster environments setup
* Kubernetes 101
    * Getting started with Kubernetes
    * Introduction to Kubernetes
    * Overview & Technical Terms
    * kubectl usage for pen-testers
* Scenarios
    * Exploiting Private Registry via Misconfiguration
    * Attacking Kubernetes Cluster Metadata using SSRF vulnerability
    * Testing for the sensitive configurations and secrets in Kubernetes cluster
    * Docker escape using Pod Volume Mounts to access the nodes and host systems
    * Attacking applications in different namespaces in Kubernetes cluster
    * Attacking Helm tiller with default RBAC setup
* Auditing Kubernetes
* kube-bench
* kubesec.io
* kube-hunter
* kubeaudit
* Logging and Monitoring for Security Events
* Logging and Monitoring
* Security checks for events using Sysdig Falco (DEMO Only)
* Advanced Scenario
* Exploiting Kubernetes API Server Vulnerability CVE-2018-1002105 (DEMO Only)
* Popular Attacks around Docker and Kubernetes ecosystem
* Resources and References

### Pre-requisites

* Google Cloud Platform (GCP) Free trial account (https://cloud.google.com/free/)
* At least 8 GB of RAM, 10GB of disk space free on the system
* Laptop should support hardware-based visualization
* If your laptop can run a 64-bit virtual machine in Oracle VirtualBox it should work
* Other visualization software might work but we will not be able to provide support for that
* USB Ports for copying data from Pen drive

### Student Requirements

* Basic knowledge of using the Linux command line
* System administration basics like servers, applications configuration, and deployment
* Familiarity with container environments like Docker would be useful

### Who Should Attend?

* Penetration Testers, Security Engineers and Bug bounty hunters
* System administrators, DevOps, and SecOps Teams
* Anyone interested in the container infrastructure security

### What to expect?

* Complete hands-on training with a practical approach and real-world scenarios
* Ebooks of the training covering all hands-on in a step by step guide (HTML, PDF, EPub, Mobi)
* Git repository of all the custom source code, scripts, playbooks used during the training
* Resources and references for further learning and practice

### What not to expect?

* A lot of hand-holding about basic concepts already mentioned in the things you should be familiar with
* A lot of theory. This is meant to be a completely hands-on training!!
* To become an accomplished DevOps or containers expert