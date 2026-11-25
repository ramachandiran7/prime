**🌟 KodeKloud Engineer 100 Days of DevOps Challenge**

<div align="center">

![DevOps Banner](https://img.shields.io/badge/DevOps-100%20Days%20Challenge-blue?style=for-the-badge&logo=devbox)
![Progress](https://img.shields.io/badge/Progress-15%20%2F%20100%20Days-green?style=for-the-badge)
![KodeKloud](https://img.shields.io/badge/Platform-KodeKloud-orange?style=for-the-badge&logo=kubernetes)

*Learning DevOps tools and practices through hands-on labs*

</div>

---

## 📌 About This Repository

This repository is my record of the **KodeKloud Engineer 100 Days of DevOps** challenge. Every task has its own file with the **task, a copy-and-paste solution, how to verify it, and the common issues with their fixes**, so a problem and its solution are quick to find.

**🎯 Mission**: Turn theory into practical skills through hands-on tasks across Linux, Git, Docker, Kubernetes, Jenkins, Ansible and Terraform.

**⏱️ Scope**: 100 tasks in 7 phases. The progress table below shows exactly which days I have completed in the lab.

> **Note:** lab values (server names, users, ports, file names) change between KodeKloud accounts. Check each value against your own task. Passwords are never stored in this repo.

---

## 🛠️ Technologies & Tools Covered

<div align="center">

### **System Administration & Web Servers**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)
![Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=black)

### **Databases**
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### **Containerization & Orchestration**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

### **Configuration Management & Infrastructure as Code**
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

### **CI/CD & Version Control**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Gitea](https://img.shields.io/badge/Gitea-609926?style=flat-square&logo=gitea&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

</div>

---

## 📅 Journey Structure

### **Daily File Format**
Every day file uses the same layout:

- **📌 Task**: what the lab asks for
- **🔁 Values to change**: the `<PLACEHOLDERS>` to replace with your task's values
- **✅ Solution**: commands, YAML or UI steps to copy and paste
- **🧪 Verification**: how to prove it worked
- **🛠️ Common Issues & Fixes**: errors you may hit and what fixes each one
- **📸 Screenshot**: your verification screenshot, saved in the day's `screenshots/` folder

### **Weekly Themes**
| Week | Focus Area | Days | Key Technologies |
|------|------------|------|------------------|
| 1-3 | **Linux & System Administration** | 1-20 | Users, SSH, cron, SELinux, iptables, Nginx, Apache, databases |
| 4-5 | **Version Control & Git** | 21-34 | Repositories, branching, merging, rebasing, hooks, pull requests |
| 6-7 | **Docker & Containerization** | 35-47 | Images, containers, networks, Dockerfiles, Compose |
| 8-10 | **Kubernetes Orchestration** | 48-67 | Pods, Deployments, volumes, Services, Secrets, full apps |
| 11-12 | **Jenkins & CI/CD** | 68-81 | Jobs, agents, security, pipelines |
| 13-14 | **Ansible Automation** | 82-93 | Inventory, playbooks, modules, roles, templates |
| 15 | **Terraform & AWS** | 94-100 | VPC, EC2, IAM, DynamoDB, CloudWatch |

### **Complete 100-Day Breakdown**

#### **🐧 Linux & System Administration (Days 1-20)**
| Day | Topic | Focus Area | Status |
|:---:|-------|------------|:------:|
| 1 | [Create a User with a Non-Interactive Shell](./DAY01/task-1-create-a-user-with-a-non-interactive-shell.md) | User management | ✅ Done |
| 2 | [Create a Temporary User with an Expiry Date](./DAY02/task-2-create-a-temporary-user-with-an-expiry-date.md) | Account expiry | ✅ Done |
| 3 | [Disable Direct Root SSH Login (all app servers)](./DAY03/task-3-disable-direct-root-ssh-login-all-app-servers.md) | SSH hardening | ✅ Done |
| 4 | [Give a Script Executable Permission](./DAY04/task-4-give-a-script-executable-permission.md) | File permissions | ✅ Done |
| 5 | [Install SELinux Packages and Disable It Permanently](./DAY05/task-5-install-selinux-packages-and-disable-it-permanently.md) | SELinux | ✅ Done |
| 6 | [Install cronie and Create a Cron Job (all app servers)](./DAY06/task-6-install-cronie-and-create-a-cron-job-all-app-servers.md) | Job scheduling | ✅ Done |
| 7 | [Passwordless SSH from thor (jump host) to all app servers](./DAY07/task-7-passwordless-ssh-from-thor-jump-host-to-all-app-servers.md) | Key-based SSH | ✅ Done |
| 8 | [Install Ansible with pip3 (globally)](./DAY08/task-8-install-ansible-with-pip3-globally.md) | Ansible install | ✅ Done |
| 9 | [Fix MariaDB Service Down](./DAY09/task-9-fix-mariadb-service-down.md) | Database recovery | ✅ Done |
| 10 | [Bash Backup Script (zip + scp with no password)](./DAY10/task-10-bash-backup-script-zip-scp-with-no-password.md) | Backup scripting | ✅ Done |
| 11 | [Install Tomcat and Deploy ROOT.war on a Custom Port](./DAY11/task-11-install-tomcat-and-deploy-root-war-on-a-custom-port.md) | App server deploy | ✅ Done |
| 12 | [Fix Apache Not Reachable on a Port (network troubleshooting)](./DAY12/task-12-fix-apache-not-reachable-on-a-port-network.md) | Service troubleshooting | ✅ Done |
| 13 | [iptables on All App Servers (only the LBR may reach Apache)](./DAY13/task-13-iptables-on-all-app-servers-only-the-lbr-may-reach.md) | Host firewall | ✅ Done |
| 14 | [Fix Apache on the Faulty App Server (same port on all)](./DAY14/task-14-fix-apache-on-the-faulty-app-server-same-port-on-all.md) | Process and port triage | ✅ Done |
| 15 | [Nginx with a Self-Signed SSL Certificate](./DAY15/task-15-nginx-with-a-self-signed-ssl-certificate.md) | TLS for web servers | ✅ Done |
| 16 | [Nginx as a Load Balancer (LBR)](./DAY16/task-16-nginx-as-a-load-balancer-lbr.md) | Load balancing | ⬜ Pending |
| 17 | [PostgreSQL User and Database](./DAY17/task-17-postgresql-user-and-database.md) | PostgreSQL admin | ⬜ Pending |
| 18 | [LAMP Stack for WordPress](./DAY18/task-18-lamp-stack-for-wordpress.md) | LAMP stack | ⬜ Pending |
| 19 | [Apache Serving Two Static Sites on a Custom Port](./DAY19/task-19-apache-serving-two-static-sites-on-a-custom-port.md) | Multi-site Apache | ⬜ Pending |
| 20 | [Nginx + PHP-FPM 8.3 over a Unix Socket](./DAY20/task-20-nginx-php-fpm-8-3-over-a-unix-socket.md) | Nginx and PHP-FPM | ⬜ Pending |

#### **🔀 Version Control & Git (Days 21-34)**
| Day | Topic | Focus Area | Status |
|:---:|-------|------------|:------:|
| 21 | [Create a Bare Git Repository](./DAY21/task-21-create-a-bare-git-repository.md) | Bare repositories | ⬜ Pending |
| 22 | [Clone a Repository to a Specific Directory](./DAY22/task-22-clone-a-repository-to-a-specific-directory.md) | Cloning repos | ⬜ Pending |
| 23 | [Fork a Repository in Gitea (UI task)](./DAY23/task-23-fork-a-repository-in-gitea-ui-task.md) | Forking in Gitea | ⬜ Pending |
| 24 | [Create a Branch from master](./DAY24/task-24-create-a-branch-from-master.md) | Branching | ⬜ Pending |
| 25 | [Branch, Commit, Merge and Push](./DAY25/task-25-branch-commit-merge-and-push.md) | Merging and pushing | ⬜ Pending |
| 26 | [Add a New Git Remote and Push](./DAY26/task-26-add-a-new-git-remote-and-push.md) | Git remotes | ⬜ Pending |
| 27 | [Revert the Latest Commit](./DAY27/task-27-revert-the-latest-commit.md) | Reverting commits | ⬜ Pending |
| 28 | [Cherry-Pick One Commit](./DAY28/task-28-cherry-pick-one-commit.md) | Cherry-picking | ⬜ Pending |
| 29 | [Pull Request Workflow in Gitea (UI task)](./DAY29/task-29-pull-request-workflow-in-gitea-ui-task.md) | Pull requests | ⬜ Pending |
| 30 | [Hard Reset to a Commit and Force-Push](./DAY30/task-30-hard-reset-to-a-commit-and-force-push.md) | Hard reset | ⬜ Pending |
| 31 | [Restore a Stash and Push](./DAY31/task-31-restore-a-stash-and-push.md) | Stashing | ⬜ Pending |
| 32 | [Rebase a Feature Branch onto master](./DAY32/task-32-rebase-a-feature-branch-onto-master.md) | Rebasing | ⬜ Pending |
| 33 | [Fix a Rejected Push (typo + rebase conflict)](./DAY33/task-33-fix-a-rejected-push-typo-rebase-conflict.md) | Conflict resolution | ⬜ Pending |
| 34 | [post-update Hook that Creates a Release Tag](./DAY34/task-34-post-update-hook-that-creates-a-release-tag.md) | Git hooks | ⬜ Pending |

#### **🐳 Docker & Containerization (Days 35-47)**
| Day | Topic | Focus Area | Status |
|:---:|-------|------------|:------:|
| 35 | [Install Docker CE and the Compose Plugin](./DAY35/task-35-install-docker-ce-and-the-compose-plugin.md) | Docker install | ⬜ Pending |
| 36 | [Run an Nginx Container](./DAY36/task-36-run-an-nginx-container.md) | Running containers | ⬜ Pending |
| 37 | [Copy a File into a Running Container](./DAY37/task-37-copy-a-file-into-a-running-container.md) | Copying files | ⬜ Pending |
| 38 | [Pull an Image and Re-tag It](./DAY38/task-38-pull-an-image-and-re-tag-it.md) | Image tagging | ⬜ Pending |
| 39 | [Create an Image from a Container](./DAY39/task-39-create-an-image-from-a-container.md) | Image from a container | ⬜ Pending |
| 40 | [Install and Configure Apache Inside a Container](./DAY40/task-40-install-and-configure-apache-inside-a-container.md) | Exec into containers | ⬜ Pending |
| 41 | [Write a Dockerfile (Ubuntu 24.04 + Apache on a custom port)](./DAY41/task-41-write-a-dockerfile-ubuntu-24-04-apache-on-a-custom-port.md) | Writing Dockerfiles | ⬜ Pending |
| 42 | [Create a Docker macvlan Network](./DAY42/task-42-create-a-docker-macvlan-network.md) | Macvlan networking | ⬜ Pending |
| 43 | [Container with Port Mapping](./DAY43/task-43-container-with-port-mapping.md) | Port mapping | ⬜ Pending |
| 44 | [Docker Compose for httpd with a Bind Mount](./DAY44/task-44-docker-compose-for-httpd-with-a-bind-mount.md) | Docker Compose | ⬜ Pending |
| 45 | [Fix a Broken Dockerfile](./DAY45/task-45-fix-a-broken-dockerfile.md) | Dockerfile debugging | ⬜ Pending |
| 46 | [Docker Compose Multi-Service Stack (PHP + MariaDB)](./DAY46/task-46-docker-compose-multi-service-stack-php-mariadb.md) | Multi-service Compose | ⬜ Pending |
| 47 | [Dockerize a Python App](./DAY47/task-47-dockerize-a-python-app.md) | Containerizing Python | ⬜ Pending |

#### **☸️ Kubernetes Orchestration (Days 48-67)**
| Day | Topic | Focus Area | Status |
|:---:|-------|------------|:------:|
| 48 | [Create a Pod](./DAY48/task-48-create-a-pod.md) | Pods | ⬜ Pending |
| 49 | [Create a Deployment](./DAY49/task-49-create-a-deployment.md) | Deployments | ⬜ Pending |
| 50 | [Pod with Resource Requests and Limits](./DAY50/task-50-pod-with-resource-requests-and-limits.md) | Resource limits | ⬜ Pending |
| 51 | [Rolling Update](./DAY51/task-51-rolling-update.md) | Rolling updates | ⬜ Pending |
| 52 | [Roll Back a Deployment](./DAY52/task-52-roll-back-a-deployment.md) | Rollbacks | ⬜ Pending |
| 53 | [Fix an Nginx + PHP-FPM Pod](./DAY53/task-53-fix-an-nginx-php-fpm-pod.md) | Volume mount debugging | ⬜ Pending |
| 54 | [Two Containers Sharing a Volume](./DAY54/task-54-two-containers-sharing-a-volume.md) | Shared volumes | ⬜ Pending |
| 55 | [Sidecar Container for Logs](./DAY55/task-55-sidecar-container-for-logs.md) | Sidecar pattern | ⬜ Pending |
| 56 | [Deployment + NodePort Service](./DAY56/task-56-deployment-nodeport-service.md) | NodePort services | ⬜ Pending |
| 57 | [Pod with Environment Variables](./DAY57/task-57-pod-with-environment-variables.md) | Environment variables | ⬜ Pending |
| 58 | [Grafana Deployment + NodePort](./DAY58/task-58-grafana-deployment-nodeport.md) | Monitoring app | ⬜ Pending |
| 59 | [Fix a Redis Deployment](./DAY59/task-59-fix-a-redis-deployment.md) | Deployment debugging | ⬜ Pending |
| 60 | [PV + PVC + Pod + NodePort Service](./DAY60/task-60-pv-pvc-pod-nodeport-service.md) | Persistent storage | ⬜ Pending |
| 61 | [Init Container](./DAY61/task-61-init-container.md) | Init containers | ⬜ Pending |
| 62 | [Secret from a File Mounted in a Pod](./DAY62/task-62-secret-from-a-file-mounted-in-a-pod.md) | Secrets | ⬜ Pending |
| 63 | [Iron Gallery App (namespace, 2 deployments, 2 services)](./DAY63/task-63-iron-gallery-app-namespace-2-deployments-2-services.md) | Multi-tier app | ⬜ Pending |
| 64 | [Fix a Python Flask Deployment and Service](./DAY64/task-64-fix-a-python-flask-deployment-and-service.md) | Fixing a Flask app | ⬜ Pending |
| 65 | [Redis with a ConfigMap and Volumes](./DAY65/task-65-redis-with-a-configmap-and-volumes.md) | Redis and ConfigMaps | ⬜ Pending |
| 66 | [MySQL with PV, PVC, Secrets and NodePort](./DAY66/task-66-mysql-with-pv-pvc-secrets-and-nodeport.md) | MySQL with PV and Secrets | ⬜ Pending |
| 67 | [Guestbook App (Redis master, Redis slave, frontend)](./DAY67/task-67-guestbook-app-redis-master-redis-slave-frontend.md) | Full-stack app | ⬜ Pending |

#### **🔧 Jenkins & CI/CD (Days 68-81)**
| Day | Topic | Focus Area | Status |
|:---:|-------|------------|:------:|
| 68 | [Set Up a Jenkins Server](./DAY68/task-68-set-up-a-jenkins-server.md) | Jenkins install | ⬜ Pending |
| 69 | [Install Jenkins Plugins](./DAY69/task-69-install-jenkins-plugins.md) | Plugin management | ⬜ Pending |
| 70 | [Create a Jenkins User and Set Matrix Authorization](./DAY70/task-70-create-a-jenkins-user-and-set-matrix-authorization.md) | Access control | ⬜ Pending |
| 71 | [Parameterized Job that Installs a Package over SSH](./DAY71/task-71-parameterized-job-that-installs-a-package-over-ssh.md) | Remote job over SSH | ⬜ Pending |
| 72 | [Parameterized Job (string + choice)](./DAY72/task-72-parameterized-job-string-choice.md) | Parameterized builds | ⬜ Pending |
| 73 | [Scheduled Job that Copies Apache Logs](./DAY73/task-73-scheduled-job-that-copies-apache-logs.md) | Scheduled jobs | ⬜ Pending |
| 74 | [Database Backup Job](./DAY74/task-74-database-backup-job.md) | Backup automation | ⬜ Pending |
| 75 | [Add SSH Slave Nodes](./DAY75/task-75-add-ssh-slave-nodes.md) | Agent nodes | ⬜ Pending |
| 76 | [Project-Based Matrix Authorization on a Job](./DAY76/task-76-project-based-matrix-authorization-on-a-job.md) | Project security | ⬜ Pending |
| 77 | [Jenkins Pipeline that Deploys Code from Gitea](./DAY77/task-77-jenkins-pipeline-that-deploys-code-from-gitea.md) | Deploy pipeline | ⬜ Pending |
| 78 | [Conditional Pipeline (branch parameter)](./DAY78/task-78-conditional-pipeline-branch-parameter.md) | Conditional pipeline | ⬜ Pending |
| 79 | [Auto-Deploy on Every Gitea Push](./DAY79/task-79-auto-deploy-on-every-gitea-push.md) | Auto-deploy job | ⬜ Pending |
| 80 | [Chained Builds (upstream then downstream)](./DAY80/task-80-chained-builds-upstream-then-downstream.md) | Chained builds | ⬜ Pending |
| 81 | [Multistage Pipeline (Deploy + Test)](./DAY81/task-81-multistage-pipeline-deploy-test.md) | Multistage pipeline | ⬜ Pending |

#### **📦 Ansible Automation (Days 82-93)**
| Day | Topic | Focus Area | Status |
|:---:|-------|------------|:------:|
| 82 | [Create an INI Inventory](./DAY82/task-82-create-an-ini-inventory.md) | Inventory files | ⬜ Pending |
| 83 | [Fix the Inventory and Create a Playbook (create a file)](./DAY83/task-83-fix-the-inventory-and-create-a-playbook-create-a-file.md) | Playbook basics | ⬜ Pending |
| 84 | [Copy a File to All App Servers](./DAY84/task-84-copy-a-file-to-all-app-servers.md) | Copy module | ⬜ Pending |
| 85 | [Create a File with Dynamic Ownership](./DAY85/task-85-create-a-file-with-dynamic-ownership.md) | File module | ⬜ Pending |
| 86 | [Passwordless SSH for Ansible](./DAY86/task-86-passwordless-ssh-for-ansible.md) | SSH keys for Ansible | ⬜ Pending |
| 87 | [Install a Package on All App Servers](./DAY87/task-87-install-a-package-on-all-app-servers.md) | Package module | ⬜ Pending |
| 88 | [Deploy httpd with blockinfile](./DAY88/task-88-deploy-httpd-with-blockinfile.md) | blockinfile module | ⬜ Pending |
| 89 | [Install, Start and Enable httpd](./DAY89/task-89-install-start-and-enable-httpd.md) | Service module | ⬜ Pending |
| 90 | [Files with ACLs](./DAY90/task-90-files-with-acls.md) | ACLs | ⬜ Pending |
| 91 | [httpd + lineinfile (prepend a line)](./DAY91/task-91-httpd-lineinfile-prepend-a-line.md) | lineinfile module | ⬜ Pending |
| 92 | [Ansible Role with a Jinja2 Template](./DAY92/task-92-ansible-role-with-a-jinja2-template.md) | Jinja2 templates | ⬜ Pending |
| 93 | [Conditionals (`when`)](./DAY93/task-93-conditionals-when.md) | Conditionals | ⬜ Pending |

#### **☁️ Terraform & AWS (Days 94-100)**
| Day | Topic | Focus Area | Status |
|:---:|-------|------------|:------:|
| 94 | [Create a VPC](./DAY94/task-94-create-a-vpc.md) | VPC | ⬜ Pending |
| 95 | [Create a Security Group in the Default VPC](./DAY95/task-95-create-a-security-group-in-the-default-vpc.md) | Security groups | ⬜ Pending |
| 96 | [EC2 Instance with an RSA Key Pair](./DAY96/task-96-ec2-instance-with-an-rsa-key-pair.md) | EC2 and key pairs | ⬜ Pending |
| 97 | [IAM Read-Only Policy for EC2](./DAY97/task-97-iam-read-only-policy-for-ec2.md) | IAM policy | ⬜ Pending |
| 98 | [EC2 in a Private VPC Subnet (variables, tfvars, outputs)](./DAY98/task-98-ec2-in-a-private-vpc-subnet-variables-tfvars-outputs.md) | EC2 in a private subnet | ⬜ Pending |
| 99 | [DynamoDB Table + IAM Role + Read-Only Policy](./DAY99/task-99-dynamodb-table-iam-role-read-only-policy.md) | DynamoDB and IAM | ⬜ Pending |
| 100 | [EC2 + CloudWatch CPU Alarm to an Existing SNS Topic](./DAY100/task-100-ec2-cloudwatch-cpu-alarm-to-an-existing-sns-topic.md) | CloudWatch alarm | ⬜ Pending |

**Status legend:** ✅ Done means I completed and verified that day in the lab. ⬜ Pending means not done yet.

---

## 📂 Repository Structure

```
📦 kodekloud-100-days-devops/
├── 📁 DAY01/
│   ├── 📄 task-1-create-a-user-with-a-non-interactive-shell.md
│   └── 📁 screenshots/
├── 📁 DAY02/
│   ├── 📄 task-2-create-a-temporary-user-with-an-expiry-date.md
│   └── 📁 screenshots/
├── 📁 DAY03/ ... DAY99/
├── 📁 DAY100/
│   ├── 📄 task-100-ec2-cloudwatch-cpu-alarm-to-an-existing-sns-topic.md
│   └── 📁 screenshots/
├── 📄 README.md
├── 📄 CONTRIBUTING.md
├── 📄 CODE_OF_CONDUCT.md
├── 📄 SECURITY.md
└── 📄 LICENSE
```

---

## 🎯 Learning Objectives

### **Core Competencies**
- ✅ **System Administration**: users, permissions, SSH hardening, SELinux, cron, firewalls
- ✅ **Web & Database Servers**: Apache, Nginx, Tomcat, MariaDB, PostgreSQL
- ✅ **Version Control**: Git workflows, branching, rebasing, hooks, pull requests
- ✅ **Containerization**: Docker images, networks, Compose
- ✅ **Orchestration**: Kubernetes workloads, storage, Secrets, Services
- ✅ **CI/CD Pipelines**: Jenkins jobs, agents, scripted pipelines
- ✅ **Configuration Management**: Ansible playbooks, roles and templates
- ✅ **Infrastructure as Code**: Terraform on AWS (VPC, EC2, IAM, DynamoDB, CloudWatch)

### **Professional Skills**
- 🔧 **Troubleshooting**: read logs, find the root cause, fix it
- 🔐 **Security Basics**: least privilege, key-based access, firewalls
- 📝 **Documentation**: clear, repeatable runbooks

---

## 🚦 Getting Started

### **Prerequisites**
- Basic Linux command line knowledge
- A KodeKloud Engineer account to run the labs
- Git installed on your machine

### **Setup Instructions**
1. **Clone the repository**:
```bash
git clone https://github.com/<your-username>/kodekloud-100-days-devops.git
cd kodekloud-100-days-devops
```

2. **Open a day and follow it**:
```bash
cd DAY01
cat task-1-*.md
```

3. **Track your progress**:
- Change the day's status from ⬜ Pending to ✅ Done in the table above
- Add your screenshot as `DAYxx/screenshots/dayxx.png`
- Update the numbers in [Progress Tracking](#-progress-tracking)

---

## 📈 Progress Tracking

### **Current Status**
- ✅ **Completed**: 15 of 100 days
- ⏳ **Remaining**: 85 days
- 🎯 **Completion Percentage**: 15%

### **Milestones**
- [ ] **Phase 1**: Linux & System Administration (Days 1-20)
- [ ] **Phase 2**: Git & Version Control (Days 21-34)
- [ ] **Phase 3**: Docker & Containerization (Days 35-47)
- [ ] **Phase 4**: Kubernetes Orchestration (Days 48-67)
- [ ] **Phase 5**: Jenkins CI/CD (Days 68-81)
- [ ] **Phase 6**: Ansible Automation (Days 82-93)
- [ ] **Phase 7**: Terraform & AWS (Days 94-100)

---

## 🤝 Community & Collaboration

### **Connect With Me**
- 👤 **GitHub**: [@<your-username>](https://github.com/<your-username>)

### **Join the Challenge**
- ⭐ **Star this repository** to follow along
- 🍴 **Fork it** to start your own 100-day record
- 💬 **Share your progress** with `#100DaysOfDevOps`
- 🔄 **Pull requests welcome**: see [CONTRIBUTING.md](./CONTRIBUTING.md)

---

## 📚 Additional Resources

- 📖 **[KodeKloud](https://kodekloud.com/)** - Learning platform
- 🎯 **[KodeKloud Engineer](https://engineer.kodekloud.com/)** - Where the 100 Days tasks live
- 📝 **[DevOps Roadmap](https://roadmap.sh/devops)** - Learning path
- 🐳 **[Docker Docs](https://docs.docker.com/)** · ☸️ **[Kubernetes Docs](https://kubernetes.io/docs/)** · 📦 **[Ansible Docs](https://docs.ansible.com/)**
- ☁️ **[Terraform Docs](https://developer.hashicorp.com/terraform/docs)** · 🔧 **[Jenkins Docs](https://www.jenkins.io/doc/)** · 🔀 **[Git Docs](https://git-scm.com/doc)**

---

## 🙏 Credits

- Tasks and labs: [KodeKloud Engineer](https://engineer.kodekloud.com/)
- Repository layout inspired by [MiqdadProjects/kodekloud-eng-100-days-devops](https://github.com/MiqdadProjects/kodekloud-eng-100-days-devops) (MIT). The write-ups in this repository are my own.

## 📄 License

MIT. See [LICENSE](./LICENSE).

---

## 💫 Inspiration

*"Small, verified steps every day beat big plans that never start."*

Each task here is one more working skill: a fixed service, a clean deployment, a repeatable runbook.

---

<div align="center">

### 🌟 **Ready to start your own 100 days?**

[![Start Challenge](https://img.shields.io/badge/Start-Day%201-success?style=for-the-badge&logo=rocket)](./DAY01/)
[![Follow Progress](https://img.shields.io/badge/Follow-Progress-blue?style=for-the-badge&logo=github)](#-progress-tracking)

</div>
