+++
lastmod = 2019-04-08

title = "Attacking and Auditing Docker Containers and Kubernetes Clusters"

time = 2019-06-20T09:00:00
time_end = 2019-06-22T17:00:00

all_day = false

authors = ["admin"]


# Schedule page publish date (NOT talk date).
# publishDate = 2017-01-01T00:00:00

abstract = """
This 3 day attack-focused, hands-on training will set you on the path to using common attack techniques against docker, kubernetes, containerized infrastructure. It will help you to learn the approach to follow andthe process for testing and auditing containers and Kubernetes clusters. By the end of the training participants will able to identify and exploit applications running on containers inside Kubernetes clusters witha hands-on approach.

An organization using micro services or any other distributed architecture rely heavily on containers and container orchestration engines like Kubernetes and as such its infrastructure security is paramount to its business operations. This course will set the base for security testers and DevOps teams to test for common security vulnerabilities and configuration weaknesses across containerized environments and distributed systems. It also helps to understand approach and process to audit the Kubernetes environment for security posture.

* The focus is on the security aspects of application and the container infrastructure
* The participants will learn the common tools and techniques that are used to attack applications running in containerized environments
* The participants will be introduced to Docker, Kubernetes and learn to assess the attack surfaces applicable for a given application on the cluster
* The participants will learn how to audit for security based on best practices using tools and custom scripts

> As part of the course delivery, the trainers will share examples of real world security issues found in penetration testing engagements to showcase mapping of the concepts with what usually happens in the real world.
"""
abstract_short = ""
event = "Nullcon Bangalore 2019"
event_url = "https://nullcon.net/website/bangalore-2019/training/kubernetes-and-docker-security.php"
location = "Royal Orchid Hotels, Bangalore"

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

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

+++

**Course outline**

* Student training lab setup
* Docker Quick Start
    * Getting started with Docker
    * Docker run
    * Dockerfile
    * Docker Management
* Docker Advanced Concepts
    * Docker-compose
    * Docker volumes and networks
    * Docker swarm
    * Portainer
* Namespaces
* Capabilities
* Control Groups
* Scenarios
    * Exploiting docker misconfiguration
    * Attacking Docker Images and Containers
    * Auditing Docker Images and Containers
    * Attacking Private Registry
    * Attacking Docker Volumes and Networks
    * Auditing Docker Volumes and Networks
    * Attacking Container Capabilities
    * Exploiting docker swarm cluster secrets
* Docker Integrity Checks
* Container introspection tool - amicontained
* Auditing docker container runtime
* Auditing docker container registries
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
    * kubectl usage for pentesters
* Deploying simple application in Kubernetes cluster
    * Using YAML manifest
    * Using helm chart
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
* Popular Attacks around Docker and Kubernetes eco system
* Resources and References

**What to bring?**

* At least 8 GB of RAM, 10GB of disk space free on the system
* Laptop should support hardware-based visualization
    * If your laptop can run a 64-bit virtual machine in Oracle VirtualBox it should work
    * Other visualization software might work but we will not be able to provide support for that
* Network Connectivity or USB Ports for copying data
* Trainer will provide the **VM and dedicated Kubernetes cluster configuration** for each student with administrative access to have a hand-on experience during the training

**Prerequisites**

* Basic knowledge of using the Linux command line
* System administration basics like servers, applications configuration and deployment
* Familiarity with container environments like Docker would be useful

**Who Should Attend?**

* Penetration Testers, Security Engineers and Bug bounty hunters
* System administrators, DevOps and SecOps Teams
* Anyone interested in the container infrastructure security

**What to expect?**

* Complete hands-on training with a practical approach and real-world scenarios
* Ebooks of the training covering all hands-on in a step by step guide (HTML, PDF, EPub, Mobi)
* Git repository of all the custom source code, scripts, playbooks used during the training
* Resources and references for further learning and practice

**What not to expect?**

* A lot of hand holding about basic concepts already mentioned in the things you should be familiar with
* A lot of theory. This is meant to be a completely hands-on training!!
* To become an accomplished DevOps or containers expert