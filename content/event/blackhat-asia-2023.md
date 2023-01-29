+++
date = 2023-01-09
lastmod = 2023-01-09

title = "Black Hat Asia 2023 - A Practical Approach To Breaking & Pwning Kubernetes Clusters"

time_start = 2023-05-09T09:30:00
time_end = 2023-05-10T18:00:00

abstract = """
The adoption of Kubernetes use in production has increased to 83% from a survey by CNCF. Still, most of the security teams struggle to understand these modern technologies.

In this real-world scenario-based training, each participant will be learning Tactics, Techniques, and Procedures (TTPs) to attack and assess Kubernetes clusters environments at different layers like Supply chain, Infrastructure, Runtime, and many others. Starting from simple recon to gaining access to microservices, sensitive data, escaping containers, escalating to clusters privileges, and even its underlying cloud environments.

By end of the training, participants will be able to apply their knowledge to perform architecture reviews, security assessments, red team exercises, and pentesting engagements on Kubernetes Clusters and Containersed environments successfully. Also, the trainer will provide step by step guide(Digital Book) with resources and references to further your learning.
"""
abstract_short = ""
event = "Black Hat Asia 2023"
event_url = "https://www.blackhat.com/asia-23/training/schedule/index.html#a-practical-approach-to-breaking--pwning-kubernetes-clusters-29818"
location = "Singapore"

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


**Section-1**

* Kubernetes 101 - Fasttrack Edition
* Security Architecture review & Attack Trees using MITRE ATT&CK framework
* `kubectl` kung-fu to explore the cluster
* Attacking the supply chain by exploiting private registry
* Pwning the container images and gaining access to the cluster
* Exploiting security misconfigurations in the cluster

**Section-2**

* Escaping out of the container to the host system to gain more privileges
* Bypassing NSP and gaining unauthorized access to other microservices
* Lateral movement from container to node and then complete cluster access
* Escalating from ServiceAccount to more RBAC privileges (No least privileges)
* Helm with Tiller service = ClusterPwn (Complete cluster takeover)
* Gaining access to k8s volumes, logs of the services, and sensitive data
* From application vulnerability to cloud provider access (attack chain)

**Section-3**

* Hacker Container - The Swiss Army knife for hacking Kubernetes Clusters
* Exploiting Kubernetes Secrets and gaining access to third-party services
* DoS the services and cluster nodes by resources exemption
* Understanding Admission controller and possible attack surface around Webhooks
* Persisting in the clusters using Sidecar/Cronjob/DaemonSets
* Defense evasion techniques for Kubernetes Cluster environments
* Some useful hacks around `kubectl` (cheatsheet will be provided)

**Section-4**

* Tools, techniques for beyond manual exploitation and analysis
* KubeAudit, KubeSec, k9s, trivy, dockle, rakkess, linters, and many others...
* Performing Docker & K8S CIS benchmarks to find all the possible security risks
* Auditing the cluster security posture from Code to Production running cluster
* Real-World case studies of Kubernetes Hacking, Vulnerabilities and Exploits
* Best practices, Recommendations based on the Security Maturity
* Resources & references to further your attacks, exploitation, more learning
