# MARCELO GARCIA
### Senior Platform Engineer | Senior DevOps & SRE Specialist | Cloud Solutions Architect
Santiago, Chile • +56 9 3194 2642 • marcelo.garcia@linux.com • [linkedin.com/in/marcelodevops](https://linkedin.com/in/marcelodevops) • [github.com/marcelodevops](https://github.com/marcelodevops)

---

## EXECUTIVE SUMMARY

Senior Platform Engineer and DevOps/SRE Leader with 21+ years of overall IT experience and 10+ years architecting, securing, and scaling cloud-native infrastructure across AWS, Google Cloud, and Azure. Deep technical authority in Kubernetes orchestration (EKS/GKE/AKS), GitOps automation (ArgoCD), service mesh (Istio), automated IaC (Terraform, Pulumi), and enterprise observability (Prometheus, Grafana, Loki, Datadog). Proven track record of slashing cloud operational costs by up to 40% and accelerating delivery velocity from hours to minutes, combined with pioneering work in agentic engineering, local LLM tooling, and autonomous workflow runtimes.

---

## CORE TECHNICAL COMPETENCIES

* **Cloud & Serverless:** AWS (EKS, ECS, Lambda, RDS, S3, Route53, EMR, Kinesis, Batch), Google Cloud Platform (GKE, BigQuery, Pub/Sub, Dataflow, Cloud Run), Azure (AKS, Functions, Monitor, DevOps), Google Distributed Cloud (Anthos), Serverless Stack (SST), AWS CDK
* **Containers & GitOps:** Kubernetes (EKS, GKE, AKS, kOps, Architecture & Admin), Docker, ArgoCD, Helm / Helmfile, Kustomize, Istio Service Mesh, Karpenter, Kyverno, OpenShift
* **IaC & CI/CD Automation:** Terraform, Pulumi, Ansible, GitHub Actions, GitLab CI, Azure DevOps Pipelines, Jenkins (Groovy), SaltStack, vRealize, SonarQube
* **Observability & Reliability:** OpenTelemetry (OTel), Prometheus, Grafana, Loki, Datadog (APM & Dashboards), ELK Stack (Elasticsearch, Logstash, Kibana), Fluent Bit, Vector, New Relic, Splunk
* **Security & Identity:** HashiCorp Vault, CyberArk Conjur, Keycloak, FreeIPA, External Secrets Operator, OIDC & OAuth 2.0, mTLS, AWS WAF & Shield, Apigee API Gateway
* **Networking & Traffic Engineering:** Cilium, Calico (CNI), Envoy Proxy, Istio Service Mesh, NetBox (IPAM/DCIM), WireGuard, OpenVPN, Traefik, HAProxy, Nginx, AWS Transit Gateway, Direct Connect, Cloud Interconnect, VPC Peering, BGP, Cloudflare, CoreDNS, Wireshark, tcpdump, iperf, Linux Network Admin
* **Languages, Data & BI Platforms:** Python (FastAPI, Scripting), Go (Golang), TypeScript / Node.js, Bash Scripting, Apache Kafka, Apache Spark, PostgreSQL, MongoDB, ClickHouse, Redis / Valkey, Microsoft Fabric, Power BI
* **AI, MLOps & Agentic Engineering:** Kubeflow, Amazon SageMaker, Amazon Bedrock, Microsoft Copilot Studio, LangChain, Azure OpenAI / OpenAI API, Ollama, Qwen / DeepSeek Runtimes, Agent Observability & Evaluation, LangSmith, Developer & Terminal Tooling (Ghostty, Zed)

---

## PROFESSIONAL EXPERIENCE

### Senior DevOps & Platform Engineer (Contract) | Taina — Freight Forwarder Chile (`03/2025 – 05/2026`)
* **Cloud-Native Platform & GitOps:** Designed a Terraform-based Amazon EKS (Kubernetes 1.30+) platform using native EKS Pod Identity, Karpenter (v1.x) Spot autoscaling, and ArgoCD with automated synchronization, self-healing, and pruning.
* **High-Scale Ingress & Capacity:** Led Istio production-readiness and capacity assessments for onboarding ~96,000 transactions/minute onto shared ingress infrastructure; identified exhausted autoscaling headroom at 4/4 replicas and defined load testing, monitoring, staged rollout, and rollback requirements for a projected 3x traffic increase.
* **Deep Performance Diagnostics:** Investigated reported Istio sidecar memory consumption using Envoy, cAdvisor, and Prometheus telemetry; measured approximately 199 MiB of utilization and identified dashboard aggregation as the likely source of a 1.8 GiB discrepancy.
* **Zero-Trust Security & Identity:** Hardened Kubernetes secrets architecture with CyberArk Conjur OSS and External Secrets Operator, addressing CA trust, SAN validation, JWT service-account identity, and OIDC issuer, audience, and JWKS configuration.
* **Internal AI Agent Platform (~30 Agents):** Architected and deployed an internal platform hosting approximately 30 autonomous AI agents adopted across engineering teams; automated operational workflows, incident triage, and cluster operations through deep integrations with Jira APIs and Kubernetes.
* **AI-Driven CI/CD & Security Gates:** Implemented AI-augmented CI/CD delivery pipelines incorporating model API validations, automated quality gates, and Retrieval-Augmented Generation (RAG); enforced strict security policies, deterministic guardrails, and approval gates to govern automated deployments.
* **LLM Observability & Telemetry:** Established comprehensive end-to-end LLM observability using LangSmith and OpenTelemetry correlated with APM and RUM metrics to monitor token consumption, inference latency, agent invocation traces, and application reliability.
* **Agentic Logistics & Local LLM Tooling:** Built Python 3.12 (FastAPI) microservices and an agentic logistics system using LangChain and Azure OpenAI to assign cargo to vessels based on dimensions, routes, and priorities, deployed on Azure Kubernetes Service (AKS); evaluated local LLM runtimes (DeepSeek-R1, Qwen 2.5) via Ollama.

### Senior DevOps & SRE Consultant | Contractor Independent (`07/2020 – 12/2024`)
*Stockholm, Sweden*

Delivered enterprise multi-cloud platform engineering, zero-downtime cloud migrations, SRE observability, and FinOps cost optimizations across client assignments in Sweden:

#### Assignment: FirstVet (`05/2024 – 12/2024`) — Senior DevOps Engineer (Contract)
* **Aggressive Cloud Cost Optimization:** Spearheaded multi-tier AWS cost reduction strategies; implemented Compute Savings Plans and RDS Reserved Instances, replaced AWS Transfer Family with self-managed SFTP on EC2, and transitioned from ElastiCache Redis 7 to Valkey 7.2, generating substantial recurring cloud savings.
* **Logging Architecture Revamp:** Eliminated redundant CloudWatch log ingestion expenses by redesigning log pipelines to route exclusively via Promtail and Loki 3.0 into centralized Grafana dashboards.
* **Unified Observability & FinOps Alerts:** Built comprehensive Grafana, Loki, Prometheus, and OpenTelemetry observability stacks with custom FinOps cost-allocation dashboards and real-time AWS Billing anomaly alerts.
* **Infrastructure Automation:** Managed and provisioned Amazon ECS clusters and cloud networking resources with Pulumi and TypeScript.

#### Assignment: Arelion (via Expertake) (`09/2022 – 05/2024`) — Senior SRE & DevOps Consultant
* **Mission-Critical Cloud Migration:** Delivered a cloud migration against a tight 3-month deadline from on-premises Docker Swarm to AWS, migrating approximately 50 Java microservices (Java 11/17 LTS, Spring Boot 2.7/3.x, Payara 5/6) to Amazon EKS (Kubernetes 1.25–1.28) and approximately 15 distributed stateful platforms (Kafka, ZooKeeper, RabbitMQ, MongoDB, MSSQL) to EC2 and RDS.
* **GitOps & Release Automation:** Implemented Helmfile and ArgoCD for version-controlled Kubernetes release management; engineered enterprise CI/CD workflows in GitHub Actions for Spring Boot and Payara microservices.
* **Perimeter DevSecOps:** Strengthened infrastructure perimeter defenses in collaboration with Cybersecurity, establishing AWS WAF rules, Shield DDoS protection, Service Control Policies (SCPs), and IDS/IPS inspection.
* **IaC, Observability & Database Modernization:** Automated infrastructure provisioning using Terraform 1.x and AWS CDK v2 with Go; integrated Datadog and ELK Stack monitoring across migrated workloads, and orchestrated MongoDB and MSSQL cutovers to AWS RDS.

#### Assignment: H&M Group (`03/2021 – 09/2022`) — Senior DevOps & Software Engineer
* **Data Mesh Proof of Concept:** Worked on a Google Cloud Data Mesh proof of concept and served as a technical reference for the planned migration of data assets from Azure Storage to Google BigQuery.
* **Real-Time Streaming Pipelines:** Implemented Apache Kafka (v2.8/3.x) streaming pipelines utilizing custom Google Cloud Dataflow Flex Templates to stream real-time events into BigQuery and Pub/Sub.
* **Multi-Cloud Secrets Management PoC:** Developed two proofs of concept, one on Google Cloud Platform (GCP) and another on Azure Kubernetes Service (AKS), to test HashiCorp Vault (v1.8+) secrets management across multi-cloud environments.
* **Multi-Cloud CI/CD & Telemetry:** Built reusable GitHub Actions workflows across GCP, Azure, and AWS; added Grafana dashboards and operational KPIs, and used Azure Monitor to improve application visibility.

#### Assignment: Tele2 (`07/2020 – 03/2021`) — Senior DevOps Chapter Leader
* **Azure DevOps & Cloud Platform:** Managed Azure DevOps platform and supported cloud-based application environments.
* **Monitoring & Operational Visibility:** Implemented monitoring solutions and dashboards to improve visibility and operational awareness.
* **PowerShell & Windows Automation:** Automated operational processes using PowerShell 7 and 5.1, reducing manual intervention and minimizing human error across enterprise Windows Server 2019 environments.
* **Platform Reliability & Risk Mitigation:** Contributed to planning and risk mitigation strategies for platform reliability.
* **Technical Mentorship:** Mentored team members and supported knowledge sharing.

### Senior SRE & DevOps Engineer | Equifax (`06/2019 – 06/2020`)
* **Apigee Enterprise Cloud Migration:** Led the cross-cloud migration of Apigee Edge API Gateway from AWS to Google Cloud Platform, integrating gateway traffic with OpenShift container clusters.
* **Istio Service Mesh Security:** Configured and managed Kubernetes clusters on GCP with Istio service mesh and the Apigee Istio Adapter (v1.4.1).
* **HA Kubernetes Architecture:** Engineered and managed resilient, highly available Kubernetes (v1.14/1.15) clusters in AWS Canada Central using kOps with least-privilege IAM security controls prior to regional EKS availability.

### DevOps Chapter Leader & Technical Lead | Cencosud (`02/2018 – 06/2019`)
* **Cloud Cost Optimization:** Reduced AWS cloud infrastructure costs by 40% through infrastructure optimization and automation.
* **Provisioning Velocity (4h to 6min):** Reduced environment provisioning lead-time from 4 hours to 6 minutes (97.5% reduction) via Jenkins 2.x automation pipelines and AWS CLI scripting, eliminating human deployment errors.
* **Security Compliance Standards:** Coordinated enterprise security hardening and compliance audits for IEC 62443 and ISO 27001 certifications across multi-cloud environments (AWS and GCP).
* **IoT Retail Innovation:** Pioneered smart supermarket IoT initiatives, deploying automated serverless REST APIs (AWS API Gateway + Lambda) for self-service sensor arrays and Scan & Go retail devices.
* **MLOps Workflows:** Worked on MLOps workflows using Amazon SageMaker and Kubeflow (v0.3/0.4) components.

### Senior DevOps Engineer & Lead Consultant | Deloitte Canada (`02/2015 – 01/2018`)
* **Senior DevOps Engineer Lead — Deloitte (07/2017 – 01/2018):** Cut deployment cycles by 30% and AWS costs by 20%; engineered CI pipelines with XL-Release, Jenkins, and Docker (v1.12+); built streaming data transformations with Apache Kafka (0.10/0.11), Apache Flink 1.x, and Apache Spark 2.x.
* **DevOps Lead — Client: Sonnet Insurance (08/2015 – 06/2017):** Built automated Kafka data streaming platforms; automated deployment and server provisioning using Ansible 2.x, SaltStack, and Python; established HashiCorp Vault encryption for sensitive data.
* **DevOps Engineer — Client: WSIB (02/2015 – 08/2015):** Planned automated deployment pipelines using Puppet, Docker, and Jenkins; configured ELK Stack monitoring and supported Guidewire production integrations.

---

### Earlier Career & Software Engineering (2005 – 2015)

#### Java Developer & DevOps Specialist | BNP Paribas Cardif (`08/2014 – 02/2015`)
*Santiago, Chile*
* **Application Architecture & Microservices:** Engineered backend microservices with Node.js and Java (Spring Boot) integrated with Oracle PL/SQL stored procedures.
* **Enterprise JEE Engineering:** Designed, developed, and deployed enterprise integration services using J2EE, Spring, Hibernate, Web Services (SOAP/REST), and Maven.
* **DevOps POC & Streaming Platform:** Spearheaded Cardif's initial DevOps continuous integration POC utilizing Jenkins, Chef, Linux, SonarQube, Git, Artifactory, and Selenium; configured and administered Apache Kafka clusters.

#### Java Consultant & Software Engineer | JPMorgan (`05/2013 – 05/2014`)
*Santiago, Chile*
* **Core Banking JEE Development:** Developed and supported mission-critical JEE applications using Spring, Hibernate, JMS messaging queues, Hermes, Pentaho, and Oracle 11g.
* **Production Reliability & Release Engineering:** Provided 24/7 production environment support, executing scheduled releases, hotfixes, patches, and Oracle PL/SQL stored procedures.

#### Technical Specialist & Integration Lead | InterSystems (`02/2009 – 04/2013`)
*Boston, USA • Sydney, AU • Chile*
* **Nationwide SIDRA Healthcare Platform:** Served as core technical reference for the Chilean Ministry of Health SIDRA platform deployed across 27 Health Services nationwide, developing in Caché ObjectScript.
* **Healthcare Interoperability & Standards:** Led technical standards and integration architecture for external clinical systems (RIS-PACS, FONASA) utilizing HL7 and DICOM communication protocols.
* **Hospital Information Systems (HIS):** Supervised and coordinated system integrations for the Military Hospital of Santiago HIS deployment.

#### Head Developer | PowerMedia (`01/2008 – 01/2009`)
*Santiago, Chile*
* **Enterprise System Architecture:** Architected and delivered web systems using Python, Java, Flex, PHP, MySQL, PostgreSQL, and Oracle for enterprise clients including Mattel, Michelin, and Coca-Cola.
* **Infrastructure & Public Sector Consulting:** Administered Linux servers and development networking; delivered a web application for the Ministry of Work (04/2008 – 07/2008) for social reform benefits administration using PHP and PostgreSQL.

#### SysAdmin & Lead Java Developer | OAKS Agency (`01/2005 – 12/2007`)
*Santiago, Chile*
* **Infrastructure & Storage Administration:** Administered corporate Linux servers, network switches, routers, security perimeters, and hardware RAID (Type 3 & 5) disk arrays.
* **Banking & Retail Web Engineering:** Promoted to Lead Developer, architecting web applications and portals in Java (Servlets, Applets, JSP), PHP, Python, and Perl with MySQL and PostgreSQL for banking and retail clients.

---

## EDUCATION & CERTIFICATIONS

* **AWS Certified Solutions Architect – Associate** — Amazon Web Services (2023)
* **MIT Professional Education: Cloud & DevOps — Continuous Transformation** — MIT (2020 – 2021)
* **Google Cloud Specialization: Architecting Hybrid Cloud with Anthos** — Google Cloud / Coursera (2020)
* **Google Cloud Specialization: Security in Google Cloud Platform** — Google Cloud / Coursera (2020)
* **Cloud Architecture with Google Cloud (Professional Certificate)** — Google Cloud / Coursera (2019)
* **Cloud Engineering with Google Cloud (Professional Certificate)** — Google Cloud / Coursera (2019)
* **Google Cloud Specialization: Networking in Google Cloud Platform** — Google Cloud / Coursera (2019)
* **Kubernetes Architecture in Google Cloud Specialization** — Google Cloud / Coursera (2019)
* **IBM SoftLayer Fundamentals Certification** — IBM (2016)
* **Guidewire Certification: Billing, Policy & Contact Center** — Guidewire (2015)
* **Linux Networking Administration Certification** — Linux Centre (2013)
* **PL/SQL Developer Workshop I & II** — Oracle University (2007)
* **Sun Certified Java Programmer (SCJP 5)** — Sun Microsystems (2006)
* **Linux Servers Administration Certification** — Linux Center (2002)
