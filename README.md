# Amazon App Mesh (amazon-app-mesh)
AWS App Mesh is a service mesh that provides application-level networking to make it easy for your services to communicate with each other across multiple types of compute infrastructure.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-app-mesh/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Microservices, Networking, Service Mesh

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### AWS App Mesh API
The AWS App Mesh API provides programmatic access to configure and manage service mesh resources for microservices. It enables developers to create and manage meshes, virtual services, virtual nodes, virtual routers, and routes, providing fine-grained control over service-to-service communication, traffic routing, and observability.

**Human URL:** [https://aws.amazon.com/app-mesh/](https://aws.amazon.com/app-mesh/)

#### Tags:

 - AWS, Microservices, Networking, Service Mesh

#### Properties

- [Documentation](https://docs.aws.amazon.com/app-mesh/)
- [OpenAPI](openapi/amazon-app-mesh-openapi.yaml)
- [Pricing](https://aws.amazon.com/app-mesh/pricing/)
- [Getting Started](https://aws.amazon.com/app-mesh/getting-started/)
- [FAQ](https://aws.amazon.com/app-mesh/faqs/)
- [JSONSchema](json-schema/amazon-app-mesh-accesslog-schema.json)
- [JSONSchema](json-schema/amazon-app-mesh-accountid-schema.json)
- [JSONSchema](json-schema/amazon-app-mesh-arn-schema.json)
- [JSONSchema](json-schema/amazon-app-mesh-awscloudmapinstanceattribute-schema.json)
- [JSONSchema](json-schema/amazon-app-mesh-awscloudmapinstanceattributekey-schema.json)
- [JSONStructure](json-structure/amazon-app-mesh-accesslog-structure.json)
- [JSONStructure](json-structure/amazon-app-mesh-accountid-structure.json)
- [JSONStructure](json-structure/amazon-app-mesh-arn-structure.json)
- [JSONLD](json-ld/amazon-app-mesh-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/app-mesh/)
- [Documentation](https://docs.aws.amazon.com/app-mesh/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/appmesh/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [Login](https://aws.amazon.com/console/)
- [Status](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)
- [SpectralRules](rules/amazon-app-mesh-spectral-rules.yml)
- [NaftikoCapability](capabilities/app-mesh-management.yaml)
- [Vocabulary](vocabulary/amazon-app-mesh-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Service Mesh Management | Create and manage service meshes that define the logical boundary for network traffic between microservices. |
| Virtual Service Configuration | Define virtual services that act as logical routers for microservice traffic, abstracting the underlying routing logic. |
| Traffic Routing Control | Configure virtual routers and routes to implement traffic management policies including weighted routing and retry policies. |
| Virtual Node Management | Manage virtual nodes representing microservice task groups with service discovery and health check configurations. |
| Observability Integration | Configure access logs and tracing for end-to-end visibility of traffic flowing through the service mesh. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservices Traffic Management | Control traffic routing between microservices with weighted routing, canary deployments, and circuit breaking. |
| Service Discovery Integration | Integrate App Mesh with AWS Cloud Map for automatic service discovery across compute types. |
| Multi-Cluster Networking | Connect services running on ECS, EKS, and EC2 instances within a unified service mesh for consistent networking policies. |

## Integrations

| Name | Description |
|------|-------------|
| AWS ECS | Deploy App Mesh sidecar proxies alongside ECS tasks for automatic traffic interception and routing. |
| AWS EKS | Run App Mesh with Kubernetes via the App Mesh Controller for Kubernetes for native K8s integration. |
| AWS X-Ray | Use X-Ray for distributed tracing of requests flowing through the App Mesh service mesh. |
| AWS Cloud Map | Integrate App Mesh with Cloud Map for service discovery across ECS, EKS, and EC2 compute. |

## Artifacts

### OpenAPI

- [Amazon App Mesh API OpenAPI](openapi/amazon-app-mesh-openapi.yaml)

### JSON Schema (323 files)

- [amazon-app-mesh-accesslog-schema.json](json-schema/amazon-app-mesh-accesslog-schema.json)
- [amazon-app-mesh-accountid-schema.json](json-schema/amazon-app-mesh-accountid-schema.json)
- [amazon-app-mesh-arn-schema.json](json-schema/amazon-app-mesh-arn-schema.json)
- [amazon-app-mesh-awscloudmapinstanceattribute-schema.json](json-schema/amazon-app-mesh-awscloudmapinstanceattribute-schema.json)
- [amazon-app-mesh-awscloudmapinstanceattributekey-schema.json](json-schema/amazon-app-mesh-awscloudmapinstanceattributekey-schema.json)
- [amazon-app-mesh-awscloudmapinstanceattributes-schema.json](json-schema/amazon-app-mesh-awscloudmapinstanceattributes-schema.json)
- [amazon-app-mesh-awscloudmapinstanceattributevalue-schema.json](json-schema/amazon-app-mesh-awscloudmapinstanceattributevalue-schema.json)
- [amazon-app-mesh-awscloudmapname-schema.json](json-schema/amazon-app-mesh-awscloudmapname-schema.json)
- [amazon-app-mesh-awscloudmapservicediscovery-schema.json](json-schema/amazon-app-mesh-awscloudmapservicediscovery-schema.json)
- [amazon-app-mesh-backend-schema.json](json-schema/amazon-app-mesh-backend-schema.json)
- ... and 313 more

## Capabilities

- [Amazon App Mesh API](capabilities/shared/amazon-app-mesh.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [App Mesh Management](capabilities/app-mesh-management.yaml) | Amazon App Mesh API | 1 | Platform Engineer, DevOps Engineer |

## Vocabulary

- [Amazon App Mesh API Vocabulary](vocabulary/amazon-app-mesh-vocabulary.yaml)

## Rules

- [Amazon App Mesh API Spectral Rules](rules/amazon-app-mesh-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
