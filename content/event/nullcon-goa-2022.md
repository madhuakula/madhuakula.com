+++
date = 2022-06-26
lastmod = 2022-06-26

authors = ["admin"]

title = "Goa Training - Hacking and Securing Kubernetes Clusters"

time_start = 2022-09-06T09:00:00
time_end = 2022-09-08T10:30:00

abstract = """
Containers and Kubernetes are everywhere. The adoption of Kubernetes use in production has increased to 83% from a survey by CNCF. Still, most security teams struggle to understand these modern technologies.

In this training, we will see both sides (offensive & defensive) of the coin by learning tactics, techniques, and procedures (TTP). We will start with understanding architecture and its attack surface. Then we will dive into each layer of security starting from the supply chain, infrastructure, runtime, and many others.

From an attacker's perspective participants can assess and attack Kubernetes Cluster environments to gain access to microservices, sensitive data, escaping containers, escalating to clusters privileges, and even its underlying cloud environments. Also, we will be using the offensive knowledge to build and design secure cluster environments using secure defaults, RBAC, NSP, Policy Engines, and many other built-in and open source components.
"""
abstract_short = ""
event = "Nullcon Goa 2022"
event_url = "https://nullcon.net/goa-2022/training/hacking-and-securing-kubernetes-clusters/"
location = "Goa, India"

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["deep-learning"]

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

**Training level:** Intermediate; Advanced

**TRAINING OUTLINE**

* Introduction to Kubernetes
* Kubernetes 101 - Fasttrack Edition
* Exploring the cluster with `kubectl`
* Architecture Overview and Attack Surface
* Threat modeling cluster components and their services
* Exploiting Kubernetes security misconfiguration and insecure defaults
* Bypassing namespaces and accessing unauthorized microservices
* Escaping out of the container to host systems and lateral movement to nodes
* Escalating privileges to gain access to compromise the private registry
* Exploring the Kubernetes Cluster using Hacker Container
* Gaining access to sensitive data, logs, and resources
* Pwning the cluster by escaping the RBAC privileges
* Review Kubernetes cluster with Docker and Kubernetes CIS benchmarks
* Auditing and evaluating the Kubernetes cluster security maturity using open source utilities and resources
* Securing the possible cluster components and configurations
* Security guard rails at different layers (Development, CI/CD, Runtime, Continous)
* Implementing NSP (network security policies) and monitoring using eBPF
* Defense in depth by creating least privileged RBAC roles
* Building supply chain security validations using SBOM (Software Bill of Materials)
* Policy Engines at different layers for evaluation, monitoring, and violations
* Introduction to Microservices security elements of API Gateway, Service Mesh
* Logging and Monitoring for continuous security visibility
* Resources, References, and Further learning