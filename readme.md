<div align="center">

# Yagnesh Jariwala

**DevOps Engineer · Kubernetes · Istio · Coraza WAF · Multi-DC Infrastructure**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/yagnesh-jariwala-70273128b)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/CodeWithYagnesh)
[![Location](https://img.shields.io/badge/Ahmedabad%2C%20Gujarat-India-orange?style=flat-square)](https://github.com/CodeWithYagnesh)

</div>

---

## What I do

DevOps Engineer with 1.5+ years of production experience securing and operating Kubernetes infrastructure across multi-region, multi-datacenter environments. My work covers service mesh security with Istio, WAF enforcement at the gateway layer via Coraza, egress traffic control with ServiceEntry + Sidecar, and observability pipelines — not just CI/CD.

I document real production problems publicly. If you're dealing with Istio, Coraza WAF, EnvoyFilter, or ClickHouse on Kubernetes, the write-ups below might save you a few hours.

---

## Production stack

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

---

## Production incident notes

Real problems I have debugged and fixed in production — sanitized and documented publicly.

| Write-up | What it covers |
|---|---|
| [Coraza WAF on Istio Gateway](https://github.com/CodeWithYagnesh/k8s-production-troubleshooting) | WasmPlugin deploy · DetectionOnly → false-positive tuning → blocking. Per-domain rule sets via `per_authority_directives` |
| [Istio egress control](https://github.com/CodeWithYagnesh/k8s-production-troubleshooting) | `REGISTRY_ONLY` mode · ServiceEntry + Sidecar `workloadSelector` for workload-scoped egress · prevents data exfiltration from compromised pods |
| [EnvoyFilter PROXY Protocol + TLS Inspector](https://github.com/CodeWithYagnesh/k8s-production-troubleshooting) | HAProxy TCP passthrough → Istio Gateway · client IP preservation via XFF · `numTrustedProxies` config |
| [ClickHouse Keeper TLS migration](https://github.com/CodeWithYagnesh/k8s-production-troubleshooting) | TLS port changes · liveness probe deadlock · quorum recovery on Altinity operator |

---

## Projects

| Repo | What it is | Stack |
|---|---|---|
| [k8s-production-troubleshooting](https://github.com/CodeWithYagnesh/k8s-production-troubleshooting) | Running log of real Kubernetes/Istio production incidents | Kubernetes · Istio · Coraza · YAML |
| [polyglot-service-mesh](https://github.com/CodeWithYagnesh/polyglot-service-mesh) | Multi-language microservices running on a service mesh | Go · Istio |
| [aws-self-healing-idp](https://github.com/CodeWithYagnesh/aws-self-healing-idp) | Self-healing internal developer platform on AWS | Shell · AWS |
| [crossplane-gitops-demo](https://github.com/CodeWithYagnesh/crossplane-gitops-demo) | GitOps-based infrastructure provisioning with Crossplane | Crossplane · ArgoCD |
| [auth-api](https://github.com/CodeWithYagnesh/auth-api) | Authentication API service | Go |
| [calendar](https://github.com/CodeWithYagnesh/calendar) | CalendarX — Flutter productivity app with project and cashbook modules | Flutter · Supabase · GitHub Actions |

---

## GitHub metrics

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=CodeWithYagnesh&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=CodeWithYagnesh&layout=compact&hide_border=true&theme=default)

---

<div align="center">
  <sub>Documenting production Kubernetes · Istio · Coraza WAF fixes — Ahmedabad, India</sub>
</div>
