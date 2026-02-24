# Roadmap Atualizado (2026) — Pós em Arquitetura Cloud + AppSec

> Objetivo: alinhar **100% do estudo** entre a Pós em Arquitetura Cloud (FIAP) e a Trilha de **AppSec** (Alura), usando **um único fluxo de aprendizado, projetos e labs**.

---

## 👤 Perfil Atual

* Dev Sênior Java/Kotlin/Python
* 8–10h de trabalho/dia
* Entrando no **Módulo 3 da Pós (Pipelines e Segurança na Cloud)**
* Em paralelo: **Carreira AppSec (níveis 1 → 3)**
* Tempo de estudo viável: **~10h/semana**

---

## 🧭 Estratégia do Roadmap

* **A Pós é prioridade e define o eixo principal**
* **O curso de AppSec entra como aprofundamento prático**
* Tudo deve convergir para:
  * AppSec e Cloud security 

---

# 📆 Roadmap: Fases concluídas (2025)

## 🟪 FASE 01 — MÊS 8-10

### Cultura DevOps, Arquitetura Cloud e Fundamentos de Segurança 

### 🎓 Pós (Core)
- [x] Cultura DevOps e colaboração
    - [x] Compreensão da Cultura DevOps.
    - [x] Implemente pipelines de ponta a ponta com CI/CD.
    - [x] Acelere a entrega de software com automação e colaboração.
    - [x] Conheça as principais ferramentas.
- [x] Arquitetura Cloud
    - [x] Arquiteturas Cloud otimizadas para AWS, Azure e GCP.
    - [x] Modelos de serviços com IaaS, PaaS, SaaS e FaaS.
    - [x] Crie soluções seguras, com custos controlados na nuvem.
    - [x] Redes privadas, públicas e híbridas, AZs, Edge Locations e Regiões.
- [x] Arquitetura de Aplicações
    - [x] Do monolito ao microsserviço.
    - [x] Arquitetura distribuída e em camadas.
    - [x] Padrões de comunicação e banco de dados
- [x] AWS
    - [x] Domine a infraestrutura e orquestração da AWS: VPC, EC2, ECS, EKS, ELB.
    - [x] Gerencie bancos de dados de alta performance (Aurora, RDS, DynamoDB).
    - [x] Garanta segurança com Secrets, WAF e IAM.
    - [x] AWS Academy e Certificações.

### 🧪 Resultado

* Base sólida em Cloud + DevOps
* Vocabulário comum entre Dev, Ops e Security
* [Projeto Fase 1](https://github.com/rodx64/pos_arch/tree/develop/fase_1/tech_challenge)

---

## 🟦 FASE 02 — MÊS 11-12

### Escalabilidade, Containerização e Segurança Inicial

### 🎓 Pós (Core)
- [x] Introdução a Containers
    - [x] Containers e arquitetura linux.
    - [x] Dockerfile, imagens, volumes e registries.
    - [x] Aplicações compostas com Docker compose.
    - [x] Segurança e boas práticas com Docker
- [x] Kubernetes Básico
    - [x] Arquitetura do Kubernetes (k8s).
    - [x] Cluster com Kind, Minikube e Cloud.
    - [x] Control Plane, Worker Nodes e API.
    - [x] Deployments, Pods, Services, ConfigMaps e Secrets, PV e PVC, HPA e VPA.
- [x] Kubernetes Avançado
    - [x] Gerenciador de pacotes com Helm Charts.
    - [x] Escalabilidade com Karpenter e KEDA.
    - [x] Estratégias de deploy com Blue/Green e Canary.
    - [x] Segurança com RBAC, Service Accounts e Cert-Manager.
    - [x] Liveness, Readiness, Limits e Resources.
    - [x] Taints, Tolerations, Evictions e Rollout.
- [x] Escalabilidade de Servidores
    - [x] Fundamentos de Escalabilidade Moderna.
    - [x] Load Balancers, CDNs e Performance Global.
    - [x] Padrões de escala horizontal e vertical.
    - [x] Escalabilidade de banco de dados.
- [x] Servidores Web e Balanceamento de Carga
    - [x] Domine Web Servers com Nginx, Apache e IIS.
    - [x] Balanceamento de Carga com Web Servers e Containers.
    - [x] Proxy, Proxy Reverso e Alta Disponibilidade

### 🔐 AppSec
 - [x] Fundamentos de cibersegurança
 - [x] Redes e protocolos
 - [x] Linux para segurança
 - [x] Criptografia (conceitos)
 - [x] GRC e legislação (LGPD)
 - [x] OWASP Top 10 (overview)
 - [x] Gestão básica de segredos
 - [x] Introdução a Threat Modeling

### 🧪 Resultado

* Aplicações escaláveis e containerizadas
* Primeira camada de segurança aplicada
* [Projeto Fase 2](https://github.com/rodx64/pos_arch/tree/develop/fase_2/tech_challenge)
---

# 📆 Roadmap: em andamento (2026)

---

## 🟩 FASE 03 — MÊS 1–2

### Pipelines, IaC e DevSecOps

### 🎓 Pós (Core)
- [x] CI / CD
    - [x] Fundamentos e Arquitetura de Pipelines de CI/CD
    - [x] Otimização e Escalabilidade de Pipelines
    - [x] Entrega Contínua para Kubernetes
    - [x] doção de GitOps com ArgoCD e FluxCD
    - [x] IaC em Pipelines com Terraform
    - [x] CI/CD para Arquiteturas Serverless
    - [x] AIOps e Automação em Pipelines de CI/CD
- [ ] IAAC
    - [ ] Introdução à IaC: Terraform e OpenTofu
    - [ ] Aprofundando no Terraform: Variáveis, Outputs e State
    - [ ] Módulos, Loops e Condicionais
    - [ ] Automação com IaC e CI/CD (Terraform + GitHub Actions)
    - [ ] Gerenciando Ambientes com Terragrunt
    - [ ] Kubernetes via Terraform: Usando os Providers Kubernetes e Kubectl
    - [ ] Auditoria, Versionamento e Segurança em IaC
    - [ ] Criando infraestrutura completa na AWS
- [ ] DevSecOps
    - [ ] Fundamentos: Do Git ao Pipeline
    - [ ] Shift-Left: SAST, DAST e SCA
    - [ ] Análise de Riscos: MITRE ATT&CK
    - [ ] Vulnerabilidades Críticas: OWASP e CVEs
    - [ ] Explorando Falhas: Injections e XSS
    - [ ] Risco das Dependências: Supply Chain e SBOM
    - [ ] Estratégia DevSecOps: Métricas e Maturidade
- [ ] Segurança na Cloud
    - [ ] Principais Ameaças em Ambientes Cloud.
    - [ ] Modelo de Responsabilidade Compartilhada na Nuvem
    - [ ] Segurança de Identidade e Acesso (IAM, MFA e Zero Trust)
    - [ ] Proteção de Dados: Criptografia e Privacidade
    - [ ] Ferramentas de CSPM, CWPP e CASB
  

### 🔐 AppSec — Nível 1
- [ ] SSDLC na prática
- [ ] OWASP Top 10 (Web)
- [ ] Segurança em Aplicações Web
- [ ] Segurança em APIs
- [ ] Gerenciamento de Segredos (Vault)
- [ ] Threat Modeling (STRIDE)


### 🧪 Projeto Integrado
* Pipeline CI/CD com controles de segurança
* Infra como código versionada
* Documentação de riscos e mitigação

---

## 🟨 FASE 04 — MÊS 3–4

### Observabilidade, Monitoramento e Segurança Operacional

### 🎓 Pós (Core)
- [ ] Observabilidade e Monitoramento
    - [ ] Fundamentos de Monitoramento e Observabilidade.
    - [ ] Os 3 pilares (Logs, Métricas e Traces).
    - [ ] Métricas de Infraestrutura, Aplicação e Containers.
    - [ ] Alertas e Notificações (Slack, Teams e Email).
- [ ] Monitoramento Open Source
    - [ ] Zabbix, Prometheus, Grafana, OpenTelemetry, Jaeger, StatsD e Loki.
    - [ ] Instalação, configuração e integração.
    - [ ] Monitoramento OpenSource no Kubernetes.
- [ ] APM
    - [ ] Métricas e Performance com Datadog, New Relic e ELK.
    - [ ] Logs, Métricas e Traces na prática.
    - [ ] Alertas Inteligentes e Automação.
    - [ ] Troubleshooting Avançado e Otimização de Performance/Custos com APM.
- [ ] Automação de Incidentes
    - [ ] Monitoramento Ativo, escalation e call rotation.
    - [ ] MTTR baixo com PagerDuty e OpsGenie.
    - [ ] Notificação com Slack, Teams, Email.
    - [ ] Automação com Functions.

### 🔐 AppSec — Nível 2
- [ ] Monitoramento de eventos de auth e acesso
- [ ] Detecção básica de ameaças
- [ ] Segurança multicloud
- [ ] Proteção de dados e KMS
- [ ] APIs seguras em escala
- [ ] Segurança em pipelines CI/CD
- [ ] Segurança em Aplicativos Mobile
- [ ] SAST, SCA e DAST
- [ ] Logs e métricas de segurança

### 🧪 Projeto Integrado
* Dashboards técnicos e de segurança
* Alertas e runbooks
---

## 🟧 FASE 05 — MÊS 5–6

### Multicloud, SRE e Segurança em Escala

### 🎓 Pós (Core)
- [ ] Multicloud e Segurança
    - [ ] Criação e Automação Multicloud (AWS, Azure e GCP).
    - [ ] Segurança e privacidade centralizada.
    - [ ] Disaster Recovery e PCN.
    - [ ] Casos de Uso e Cenários reais
- [ ] SRE
    - [ ] SRE (Site Reliability Engineering)
    - [ ] Cultura e papel do SRE.
    - [ ] SRE vs DevOps: Diferenças e Colaborações.
    - [ ] Golden Metrics, Runbooks e Post-Mortem.
    - [ ] SLA, SLI, SLO e Error Budget.
    - [ ] MTTR, RTO e RPO
- [ ] FinOps
    - [ ] Cultura FinOps na Cloud.
    - [ ] Rightsizing, Forecast, Savings Plans, Spot Instances.
    - [ ] Tagueamento de recursos e automação de economia.
    - [ ] Visibilidade com Kubecost e AWS Cost Explorer.
- [ ] IT Service Management e AIOps
    - [ ] A Evolução do ITSM e o Papel do AIOps.
    - [ ] Boas práticas e Frameworks: ITIL e ISO/IEC 20000.
    - [ ] Ciclo de Vida e Estratégias de Serviços.
    - [ ] AIOPs no gerenciamento preditivo da TI.

### 🔐 AppSec — Nível 3
- [ ] Gestão de Logs e Métricas
- [ ] Integrando Security by Design no SDLC
- [ ] Gestão de Vulnerabilidade
- [ ] AppSec (Estratégias)
- [ ] ASVS
- [ ] OWASP SAMM

## ✅ Resultado Esperado
* Arquitetura Cloud sólida
* AppSec prático e aplicado ao projeto final
* Documentação do projeto baseada em ASVS
* Observabilidade e métricas de segurança
