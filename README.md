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
* **Cloud-Native Platform & GitOps:** Designed a Terraform-based Amazon EKS platform using EKS Pod Identity, Karpenter Spot autoscaling, and ArgoCD with automated synchronization, self-healing, and pruning.
* **High-Scale Ingress & Capacity:** Led Istio production-readiness and capacity assessments for onboarding ~96,000 transactions/minute onto shared ingress infrastructure; identified exhausted autoscaling headroom at 4/4 replicas and defined load testing, monitoring, staged rollout, and rollback requirements for a projected 3x traffic increase.
* **Deep Performance Diagnostics:** Investigated reported Istio sidecar memory consumption using Envoy, cAdvisor, and Prometheus telemetry; measured approximately 199 MiB of utilization and identified dashboard aggregation as the likely source of a 1.8 GiB discrepancy.
* **Zero-Trust Security & Identity:** Hardened Kubernetes secrets architecture with CyberArk Conjur OSS and External Secrets Operator, addressing CA trust, SAN validation, JWT service-account identity, and OIDC issuer, audience, and JWKS configuration.
* **Agentic Logistics & Local LLM Tooling:** Built Python (FastAPI) microservices and an agentic logistics system using LangChain and Azure OpenAI to assign cargo to vessels based on dimensions, routes, and priorities, deployed on Azure Kubernetes Service (AKS); evaluated local LLM runtimes (Ollama, Qwen, DeepSeek) with LangSmith tracing.
