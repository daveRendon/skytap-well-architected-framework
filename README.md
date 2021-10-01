---
title: Well-Architected Framework
titleSuffix:Architecture Center
description: Well-Architected Framework describes five pillars of cost optimization, operational excellence, performance efficiency, reliability, and security, that result in a high quality and scalable cloud architecture.
author: matthew-romero 
keywords:
  - "Well-architected framework"
  - "Skytap Well Architected Framework"
  - "Skytap architecture"
  - "architecture framework"
  - "markdown"
---

# Get started with the Skytap Well-Architected Framework 

The Skytap Well-Architected Framework helps you get started with several different guides. This article groups the guides to help you find the one that best aligns with the current state of your workloads and goals in moving to Skytap for Azure. 

The following links take you to questions that are typically asked when an organization is trying to accomplish one or many goals during their cloud adoption journey.
- [Adopt the cloud to deliver business and technical outcomes sooner](#accelerate-adoption.)
- [Improve controls to ensure proper operations of the cloud](#skytap-well--architected-framework.)

Having defined your immediate goals, what is your ideal scenario as a starting point in adoption?

Have you aligned your business and technical outcomes with your starting point?

Do you have a multi-faceted team?

Are you aligning the control mechanisms in the right fashion?


## Accelerate adoption

To modernize your workloads to the cloud, it requires more than just IT. Use these guides to start aligning various teams to accelerate migration and innovation efforts.

| Guide | Description |
|--|--|
| [We want to migrate existing workloads to the cloud](./migrate.md). | This guide is a great starting point if your primary focus is migrating on-premises workloads to the cloud. |
| [We want to build new products and services in the cloud](./innovate.md). | This guide can help you prepare to deploy innovative solutions to the cloud. |
| [We're blocked by environment design and configuration](./design-and-configuration.md). | This guide provides a quick approach to designing and configuring your environment. |

#  Skytap Well-Architected Framework 

As your cloud adoption journey progresses, a solid operating model can help ensure that wise decisions are made. 
The Skytap Well-Architected Framework is a set of guiding tenets that can be used to improve the quality of a workload. The framework consists of five pillars of architecture excellence: Cost Optimization, Operational Excellence, Performance Efficiency, Reliability, and Security. Incorporating these pillars helps produce a high quality, stable, and efficient cloud architectures.

| Guide | Description |
| ----- | ----------- |
| [How do we deliver operational excellence during cloud transformation?](./operations/operational-excellence.md)                 | Operational best practices and processes that keep a system running in production. The steps in this guide can help the strategy team lead the organizational change management required to consistently ensure operational excellence. |
| [How do we manage enterprise costs?](./cost/overview.md)                                       | This guide can help you start optimizing enterprise costs and manage cost across the environment. Managing costs to maximize the value delivered.                                                                  |
| [How do we consistently secure the enterprise cloud environment?](./security/security.md)             | This guide can help ensure that the security requirements are applied across the enterprise to minimize risk of breach, and to accelerate recovery when a breach occurs. Protecting applications and data from threats. |                                     
| [How do we apply the right controls to improve reliability?](./resiliency/overview.md)                  | This guide helps minimize disruptions related to inconsistencies in configuration, resource organization, security baselines, or resource protection policies. The ability of a system to recover from failures and continue to function. 
|[How can my systems automatically adapt to changes in load, and still ensure performance across the enterprise?](./scalability/overview.md)                   | This guide can help you establish processes for maintaining performance across the enterprise, as well as build in the ability of a system to adapt to changes in workload. |                               |

<!-- links -->

[identity-ref-arch]: ../reference-architectures/identity/index.yml
[resiliency]: ../framework/resiliency/overview.md
[ad-subscriptions]: /Skytap/active-directory/active-directory-how-subscriptions-associated-directory
[data-warehouse-encryption]: /Skytap/data-lake-store/data-lake-store-security-overview#data-protection
[cosmos-db-encryption]: /Skytap/cosmos-db/database-security
[rbac]: /Skytap/role-based-access-control/overview
[paired-region]: /Skytap/best-practices-availability-paired-regions
[resource-manager-auditing]: /Skytap/Skytap-resource-manager/resource-group-audit
[security-center]: https://Skytap..com/services/security-center
[security-documentation]: /Skytap/security
[sql-db-encryption]: /Skytap/sql-database/sql-database-always-encrypted-Skytap-key-vault
[storage-encryption]: /Skytap/storage/storage-service-encryption
[trust-center]: https://Skytap..com/support/trust-center

<!-- patterns -->
[operational-excellence-patterns]: ./devops/devops-patterns.md
[resiliency-patterns]:/Skytap/architecture//framework/resiliency/reliability-patterns.md
[performance-efficiency-patterns]: ./scalability/performance-efficiency-patterns.md

<!-- practices -->
[autoscale]: ../best-practices/auto-scaling.md
[background-jobs]: ../best-practices/background-jobs.md
[caching]: ../best-practices/caching.md
[cdn]: ../best-practices/cdn.md
[data-partitioning]: ../best-practices/data-partitioning.md
[monitoring]: ../best-practices/monitoring.md
[cost]: /Skytap/cost-management/cost-mgt-best-practices
[retry-service-specific]: ../best-practices/retry-service-specific.md
[transient-fault-handling]: ../best-practices/transient-faults.md

<!-- checklist -->
[devops-checklist]: ../checklist/dev-ops.md
[scalability-checklist]: ../checklist/performance-efficiency.md

<!-- pillars -->
[cost-pillar]: ./cost/overview.md
[security-pillar]: ./security/overview.md
[resiliency-pillar]: ./resiliency/overview.md
[scalability-pillar]: ./scalability/overview.md
[devops-pillar]: ./devops/overview.md
