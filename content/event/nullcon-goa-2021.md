+++
lastmod = 2021-03-01

title = "Virtual Training - Hacking and Securing Kubernetes Clusters"

time = 2021-03-01T10:00:00
time_end = 2021-03-04T14:00:00

all_day = false

authors = ["admin"]


# Schedule page publish date (NOT talk date).
# publishDate = 2017-01-01T00:00:00

abstract = """
Containers and Kubernetes are everywhere. We can see the use of Kubernetes in production increased exponentially. Still, most of the security teams struggle tounderstand these modern technologies

In this training, we will see both sides (offensive & defensive) of the coin by learning tactics, techniques, and procedures (TTPs). We will start with understandingarchitecture and its attack surface. Then we will dive into each layer of security starting from the supply chain, infrastructure, runtime, and many others.

From an attacker's perspective participants able to assess and attack Kubernetes Cluster environments to gain access to microservices, sensitive data, escapingcontainers, escalating to clusters privileges, and even its underlying cloud environments. Also, we will be using the offensive knowledge to build and design securecluster environments using secure defaults, RBAC, NSP, PSP(deprecating so we may see using OPA), and many other built-in and opensource components.
"""
abstract_short = ""
event = "Nullcon Goa 2021"
event_url = "https://nullcon.net/website/goa-2021/training/hacking-and-securing-kubernetes-clusters.php"
location = "Virtual"

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

**Day 1**

* Introduction to Kubernetes
* Kubernetes 101 - Fasttrack Edition
* Exploring the cluster with kubectl
* Architecture and Attack Surface
* Threat modeling cluster components and services

**Day 2**

* Exploiting Kubernetes security misconfiguration and insecure defaults
* Bypassing namespaces and accessing unauthorized microservices
* Escaping out of the container to host systems and nodes
* Escalating privileges to gain access to the private registry
* Exploring the Kubernetes Cluster using Hacker Container

**Day 3**

* Gaining access to sensitive data, logs, and resources
* Pwning the cluster by escaping the RBAC privileges
* Review Kubernetes cluster with Docker and Kubernetes CIS benchmarks
* Auditing and evaluating the Kubernetes cluster security maturity using opensource utilities and resources
* Securing the possible cluster components and configurations

**Day 4**

* Implementing security guard rails at different layers (Development, CI/CD, Runtime, Continous)
* Implementing NSP (network security policies)
* Creating least privileged roles and understanding RBAC
* OPA (Open Policy Agent) to evaluate and monitor for policy violations
* Logging and Monitoring for continuous security visibility
* Resources, References, and Further learning

**What to bring/have**

* Laptop with a modern browser and access to wireless internet connectivity
* Trainer will provide each student their own Kubernetes Cluster environment in the cloud environment

**Prerequisites**

* Fundamental knowledge of Linux, CLI, Servers, and its configuration
* Basic knowledge of using Docker containers
* Familiarity with cluster environments like Kubernetes would be useful (we will cover the FastTrack version in our training)

**Who Should Attend?**

* Security Engineers, Penetration Testers, and Security Architects
* Red & Blue Teams, who wish to see both offensive and defensive side
* Cloud, SRE, DevOps, and DevSecOps teams
* Anyone interested in learning more about Kubernetes Security

**What to expect?**

* Completely hands-on driven training (except where concepts introduced)
* Step by step detailed learning guide for the entire training
* Lot of real-world experience, examples, knowledge, and scenarios
* Resources and references for further your learning about Kubernetes Security

**What not to expect?**

* Already mentioned prerequisites topics like Docker, Containers, System Administration
