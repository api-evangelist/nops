# nOps (nops)
nOps is an AI-powered cloud cost visibility and optimization platform that helps organizations reduce their AWS spending by 50% or more through autonomous management and automation.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/nops/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Costs, FinOps

## Timestamps

- **Created:** 2026-01-02
- **Modified:** 2026-04-18

## APIs

### nOps
nOps is an AWS-focused cloud management platform that helps engineering and FinOps teams cut costs, improve governance, and keep environments well-architected.

**Human URL:** [https://www.nops.io/](https://www.nops.io/)

#### Tags:

 - Costs, FinOps

#### Properties

- [Documentation](https://www.nops.io/)
- [Documentation](https://app.nops.io/public_redoc/)
- [OpenAPI](openapi/nops-nops-openapi.yml)
- [JSONSchema](json-schema/map-migration-project.json)
- [JSONLD](json-ld/nops-context.jsonld)

## Common Properties

- [Blog](https://www.nops.io/blog/)
- [Webinars](https://www.nops.io/webinars-and-workshops/)
- [Documentation](https://help.nops.io/docs/introduction/platform-introduction)
- [Support](https://help.nops.io/docs/support/open-support-case)
- [Integrations](https://help.nops.io/docs/agents-integrations/integrations)

## Features

| Name | Description |
|------|-------------|
| Autonomous Cost Optimization | AI-powered autonomous management that identifies and implements cost savings without manual intervention. |
| 100% Cost Visibility | Complete visibility into cloud costs across AWS, GCP, Azure, Kubernetes, GenAI, and SaaS applications. |
| Essentials Scheduler | Automated scheduling of non-production workloads to eliminate idle resource costs. |
| MAP Migration Support | AWS Migration Acceleration Program tracking for migration projects, products, and resources. |
| Spot Instance Optimization | Intelligent spot instance management for maximizing cost savings on compute workloads. |

## Use Cases

| Name | Description |
|------|-------------|
| FinOps Automation | Automate cloud cost allocation, tracking, and optimization across teams and business units. |
| Cloud Migration Tracking | Track MAP migration projects and measure cost savings from AWS migration programs. |
| Idle Resource Elimination | Identify and schedule or terminate idle resources to reduce wasted cloud spending. |
| Cost Anomaly Detection | Real-time detection and alerting on unusual cost spikes and billing anomalies. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Services | Deep integration with AWS billing, CUR, CloudTrail, CloudWatch, and resource management services. |
| Kubernetes | Container cost visibility and optimization for EKS and self-managed Kubernetes clusters. |
| Slack and Teams | Notification integrations for cost alerts, optimization recommendations, and scheduler events. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [nOps API](openapi/nops-nops-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [nOps API](capabilities/shared/nops.yaml) -- 12 operations for MAP migration and scheduler management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Cloud Cost Optimization](capabilities/cloud-cost-optimization.yaml) | nOps | 12 | FinOps Engineer |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
