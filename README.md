# Hello, I'm Akkireddy Challa 👋

Platform Engineer at [Telia](https://www.telia.se/) in Stockholm, Sweden.
I build secure, self-service cloud platforms for data and AI/ML teams.

My mission is to make data and AI development faster, safer, and more scalable
by designing platforms and golden paths that let engineers focus on what matters.

Previously, I spent 4+ years as Head of DevOps at Talent Venture Group,
building cloud-native infrastructure and DevSecOps pipelines for multiple clients.
I hold a Master's in Computer Science from Blekinge Institute of Technology and
published research on [handwritten digit recognition using ML](http://urn.kb.se/resolve?urn=urn:nbn:se:bth-17656).

---

## What I do

- Design and operate multi-cloud platforms on AWS, GCP & Azure — Kubernetes, EKS, GKE, AKS, multi-tenant, secure, cost-optimised
- Enable data scientists and ML engineers with CI/CD, MLOps, observability, and golden paths for data products and models
- Automate infrastructure with Terraform, GitOps (Argo CD), and policy-as-code to keep platforms reliable and compliant
- Drive FinOps initiatives to optimise cloud spend while maintaining performance
- Build and manage LLM platforms — LiteLLM, Open WebUI, Azure AI Foundry, Vertex AI, with SSO via Azure Entra ID

---

## Technologies

**Cloud & IaC:** AWS (EKS, Lambda, S3, RDS, IAM, EC2, VPC) · GCP (Vertex AI, AlloyDB, GKE) · Azure (AKS, Entra ID, AI Foundry) · Terraform · Pulumi · CDK

**Containers & Orchestration:** Kubernetes · Helm · Argo CD · Kustomize · Docker

**CI/CD & GitOps:** GitHub Actions · Jenkins · GitLab CI · JFrog · Tekton

**Observability:** Datadog · Grafana · Prometheus · OpenTelemetry · Jaeger

**Data & AI/ML:** Apache Spark · Airflow · dbt · MLflow · Feast · LiteLLM · Open WebUI · Redis · Hinode

**Security & Identity:** Azure Entra ID · OAuth 2.0 / OIDC · RBAC · AWS IAM · OPA · Kyverno

**Languages:** Python · Go · Shell · HCL · SQL

---

## Featured projects

| Project | Focus |
|---|---|
| [k8s-mcp-server](https://github.com/akkireddy-challa/k8s-mcp-server) | Read-only Kubernetes diagnostics through the Model Context Protocol |
| [aws-analytics-platform-terraform](https://github.com/akkireddy-challa/aws-analytics-platform-terraform) | Terraform foundations for a scalable, secure AWS analytics platform |
| [akkireddy-challa.github.io](https://akkireddy-challa.github.io/) | Portfolio and writing on platform engineering, SRE, and AI infrastructure |
| [DevOps-guide](https://github.com/akkireddy-challa/DevOps-guide) | Practical DevOps concepts, tools, and automation examples |
| [azure-mcp-platform](https://github.com/akkireddy-challa/azure-mcp-platform) | MCP server for Azure Resource Manager, AKS, and AI Foundry management |
| [grafana-mcp-observability](https://github.com/akkireddy-challa/grafana-mcp-observability) | MCP server for Grafana dashboards, alerts, and datasource management |
| [phoenix-mcp-eval](https://github.com/akkireddy-challa/phoenix-mcp-eval) | MCP server for Arize Phoenix LLM tracing, evaluation, and dataset management |

---

## Open source

I am actively contributing in the Kubernetes, GitOps, AI platform, and observability ecosystems — especially production-grade AI infrastructure, secure agentic workflows, and developer self-service platforms.

I maintain a growing MCP (Model Context Protocol) ecosystem enabling AI agents to operate on real infrastructure:
- **[k8s-mcp-server](https://github.com/akkireddy-challa/k8s-mcp-server)** — Read-only Kubernetes diagnostics
- **[azure-mcp-platform](https://github.com/akkireddy-challa/azure-mcp-platform)** — Azure Resource Manager, AKS & AI Foundry
- **[grafana-mcp-observability](https://github.com/akkireddy-challa/grafana-mcp-observability)** — Grafana dashboards, alerts & datasources
- **[phoenix-mcp-eval](https://github.com/akkireddy-challa/phoenix-mcp-eval)** — Arize Phoenix LLM tracing & evaluation

---

## Connect

[LinkedIn](https://www.linkedin.com/in/akkireddy-challa/) ·
[Blog](https://akkireddy-challa.github.io/)

<!-- dynamic:activity:start -->
## Current output

_Updated automatically every day via GitHub Actions._

### Latest writing
- [Build MCP skills for AI assistants](https://akkireddy-challa.github.io/writing/mcp-skills-for-ai.html) (2026-06-05) - A practical guide to building MCP skills for AI assistants, including design, prompts, and...
- [Run AI models locally with OpenLLM](https://akkireddy-challa.github.io/writing/openllm-local-ai-models.html) (2026-06-05) - A practical guide to running AI models locally with OpenLLM and open-source tooling for inference.
- [AI Ops trends to watch in 2026](https://akkireddy-challa.github.io/writing/trending-ai-ops-2026.html) (2026-06-05) - Model reproducibility, observability, governance, and cost-aware model lifecycle management.
- [Cloud cost optimization patterns for 2026](https://akkireddy-challa.github.io/writing/cloud-cost-optimization-2026.html) (2026-06-05) - Autoscaling economics, spot/preemptible strategies, and telemetry-driven rightsizing.
- [Kubernetes security priorities for 2026](https://akkireddy-challa.github.io/writing/k8s-security-2026.html) (2026-06-05) - Supply chain hardening, RBAC least-privilege, and runtime protection approaches.

### Recent project activity
- [Online-Banking-system](https://github.com/akkireddy-challa/Online-Banking-system) (stars: 107) - The project’s primary goals consist of: A robust and effective web based online banking system. Extending functionality without compromising the security. Personal banking services that gives you complete control over all your banking demands online. Simple and easy user interface to work with. Online Banking features: Registration for online banking by Admin. Adding Beneficiary account by customer. Transferring amount to the beneficiary added by customer. Staff must approve for beneficiary activation before it can be used for transferring funds. Customer gets to know his last login date and time each time he logs in. Customer can check last 10 transactions made with their account. Customer can check their account statement within a date range. Customer can request for ATM and Cheque Book. Staff will approve requests for ATM card and cheque book. Admin can add/edit/delete customer as well as staff. All three of them(customer, staff & admin) can change their password. Staff and Admin Login pages are hidden from customer for security purpose. Security: Each and every input is passed through mysql_real_escape_string() to remove special characters from the string so that user can’t submit arbitrary input. It protects from attacks like Sql Injection and Cross Site Scripting(XSS). Passwords are encrypted with SHA- 1 hashing algorithm and then stored in database. Passwords are stored as encrypted hashes with an additional random salt for added security. Note: If we talk about security,above mentioned points would provide no security at all but it will work for beginners. Being into web app pentesting,I very well know this project will not be considered secure. It needs atleast a more effective filtering mechanism, better hashing algorithm, a better salting procedure for storing passwords and some other things too. Database: The database contains customer, staff & admin tables. Each customer has its own virtual passbook linked with its account number. Staff, customer and, admin have their details and password in their respective tables with all the details. A separate table for beneficiary is included in the database. A table for cheque book and ATM requests is included. This project is divided into three hierarchical parts: The index page for the customer login. A hidden staff login page. A hidden admin login page. Usage: 1.Install XAMPP or something similar. 2.Copy all the files to c:/xampp/htdocs/banking/ 3.Create a db named as 'bnak_db' and import the bank_db.sql from phpMyAdmin. 4.change the password in _inc/dbconn.php file accordingly. 5.visit localhost/banking (customer index page) 6.visit localhost/banking/adminlogin.php (admin login) 7.visit the localhost/banking/staff_login.php (staff login) _(updated 2026-08-22)_
- [devblog](https://github.com/akkireddy-challa/devblog) - No description yet. _(updated 2026-08-19)_
- [phoenix-mcp-eval](https://github.com/akkireddy-challa/phoenix-mcp-eval) - MCP server for Arize Phoenix — LLM tracing, evaluation, and dataset management via AI agents _(updated 2026-08-14)_
- [grafana-mcp-observability](https://github.com/akkireddy-challa/grafana-mcp-observability) - MCP server for Grafana — query dashboards, alerts, and datasources via AI agents _(updated 2026-08-14)_
- [akkireddy-challa.github.io](https://github.com/akkireddy-challa/akkireddy-challa.github.io) - Portfolio and writing hub for Akkireddy Challa: platform engineering, DevOps, SRE, open source, and AI infrastructure. _(updated 2026-07-20)_

### GitHub stats

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=akkireddy-challa&show_icons=true&theme=dark&hide_border=true&count_private=true)](https://github.com/akkireddy-challa)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=akkireddy-challa&layout=compact&theme=dark&hide_border=true)](https://github.com/akkireddy-challa)
[![GitHub Streak](https://streak-stats.demolab.com?user=akkireddy-challa&theme=dark&hide_border=true)](https://github.com/akkireddy-challa)

![Profile views](https://komarev.com/ghpvc/?username=akkireddy-challa&color=0e75b6&style=flat)

_Last refreshed: 2026-08-30 UTC_
<!-- dynamic:activity:end -->
