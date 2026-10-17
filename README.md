# Hi, I'm Joash Odingo 👋

**DevOps / Platform Engineer** — automation, infrastructure as code, and CI/CD.

I build and automate the path from commit to production: containerised
applications, infrastructure defined in code, and pipelines that deploy them
reliably.

Based in **Tulsa, Oklahoma** · Open to **DevOps / Platform / SRE** roles.

---

## 👨‍💻 About Me

- 🚀 I ship end-to-end delivery pipelines — source to running service — using
  Jenkins, GitHub Actions, Terraform and Docker.
- ☁️ I define cloud infrastructure as code (AWS: VPC, EC2, EKS, S3, IAM,
  CloudFormation, OIDC) rather than clicking it together.
- 📈 I care about observability: metrics, dashboards and monitoring loops built
  from first principles.
- 🐧 Comfortable across Linux (RHEL, Ubuntu), Bash and Python automation.
- 🎯 Working toward **CKA** and **AWS** certifications.

---

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| **Cloud** | AWS — EC2, S3, VPC, EKS, IAM, CloudFormation, OIDC |
| **Containers** | Docker (multi-stage builds), Kubernetes |
| **Infrastructure as Code** | Terraform, Ansible, CloudFormation |
| **CI/CD** | Jenkins, GitHub Actions, Argo CD |
| **Observability** | Prometheus, Grafana |
| **Languages** | Python, Bash, Java, HCL |
| **OS** | Linux (RHEL, Ubuntu), macOS |

---

## 🚀 Featured Projects

My own work, MIT-licensed, buildable from source — most complex first.

### 🏗️ [infra-platform-project](https://github.com/the-jodingo/infra-platform-project)

The flagship: a reference DevOps platform. A containerised Python service on a
Terraform-provisioned AWS VPC — three private subnets across availability zones
and an **EKS cluster** — shipped by a Jenkins pipeline, with Prometheus alert
rules, Grafana dashboards, a written security policy, and a blue-green
deployment path.

`Terraform` · `AWS EKS` · `Jenkins` · `Prometheus` · `Grafana` · `Python`

### 🐳 [Jenkins-Docker-Demo](https://github.com/the-jodingo/Jenkins-Docker-Demo)

Two Node.js microservices built, tested and shipped by a **parallel Jenkins
pipeline** — test and build stages run side by side, images are pushed to a
registry, and the stack is deployed with Docker Compose. Includes Kubernetes
manifests (namespace, deployments, services, ingress) and CodeQL scanning.

`Jenkins` · `Docker Compose` · `Kubernetes` · `Node.js` · `CodeQL`

### 🔐 [terraform-cicd-oidc-pipeline_terraform.project](https://github.com/the-jodingo/terraform-cicd-oidc-pipeline_terraform.project)

Terraform CI/CD with **keyless AWS authentication** — an OIDC trust relationship
between GitHub Actions and AWS, so no long-lived cloud credentials exist at all.
Plan on pull request, apply on merge behind an approval gate, with KMS-encrypted
remote state.

`Terraform` · `GitHub Actions OIDC` · `AWS IAM` · `KMS`

### 📦 [aws-modules-remote-state_terraform.project](https://github.com/the-jodingo/aws-modules-remote-state_terraform.project)

A reusable Terraform **module library** — VPC, S3 bucket and security group —
with an S3 + DynamoDB remote-state backend, separate bootstrap and environment
roots, and Checkov/tflint scanning in CI.

`Terraform modules` · `S3 backend` · `DynamoDB locking` · `Checkov`

### 🍕 [Jenkins_Project0](https://github.com/the-jodingo/Jenkins_Project0)

A Maven **WAR** application (Java servlet + JSP) packaged and deployed to Apache
Tomcat, with a declarative Jenkins CI/CD pipeline that builds, tests, deploys
and verifies the running app — plus a multi-stage Docker build path.

`Maven` · `Java` · `Tomcat` · `Jenkins` · `Docker`

### ☁️ [aws-cloudformation](https://github.com/the-jodingo/aws-cloudformation)

CloudFormation templates for EC2, EBS and S3, linted with `cfn-lint` on every
push. Includes a parameterised, least-privilege SSH rule rather than an open
`0.0.0.0/0` default.

`AWS CloudFormation` · `cfn-lint` · `IAM`

### 📊 [Python-Terminal-CPU-Monitor](https://github.com/the-jodingo/Python-Terminal-CPU-Monitor)

A live terminal dashboard for CPU usage: overall and per-core utilisation, load
average, a rolling history bar, and the top CPU-consuming processes — tested on
Linux and macOS.

`Python` · `psutil` · `rich` · `pytest`

### 🐧 [Linux-CPU-monitoring-system](https://github.com/the-jodingo/Linux-CPU-monitoring-system)

A dependency-free Bash CPU monitor reading `/proc/stat`, `mpstat` and `ps`, with
configurable thresholds. ShellCheck-clean, with a smoke test in CI.

`Bash` · `/proc` · `mpstat` · `ShellCheck`

### 🧱 Terraform baselines

Three small, self-contained projects, each solving one problem that shows up in
every real account. All validate and pass Checkov without AWS credentials.

- **[terraform-aws-cost-guardrails](https://github.com/the-jodingo/terraform-aws-cost-guardrails)** —
  monthly cost budget publishing to an encrypted SNS topic at 50/80/100% of the
  limit. `AWS Budgets` · `SNS` · `KMS`
- **[terraform-aws-secure-bucket](https://github.com/the-jodingo/terraform-aws-secure-bucket)** —
  hardened S3: SSE-KMS, all four public-access blocks, TLS-only bucket policy,
  access logging and Glacier lifecycle. `S3` · `KMS` · `IAM policy`
- **[terraform-aws-audit-trail](https://github.com/the-jodingo/terraform-aws-audit-trail)** —
  multi-region CloudTrail with log-file validation, an encrypted log archive and
  CloudWatch delivery. `CloudTrail` · `CloudWatch Logs` · `KMS`

---

## 📊 Currently

- Deepening **Kubernetes** and **GitOps** (Argo CD) practice
- Studying **AI/ML engineering** — RAG, evaluation, and model serving
- Preparing for **CKA** and **AWS** certifications

---

## 🔗 Connect With Me

- 💼 **LinkedIn** — [linkedin.com/in/the-jodingo](https://www.linkedin.com/in/the-jodingo)
- 🐙 **GitHub** — [github.com/the-jodingo](https://github.com/the-jodingo)

---

Thanks for stopping by. If a repository here is useful to you, a ⭐ is always
appreciated.
