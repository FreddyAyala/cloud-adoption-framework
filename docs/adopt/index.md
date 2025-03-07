---
title: How to adopt the cloud
description: The Adopt methodology shows you how to migrate, modernize, innovate, and relocate workloads in Azure.
author: stephen-sumner
ms.author: ssumner
ms.date: 03/07/2023
ms.topic: conceptual
ms.custom: internal
keywords: cloud adoption, cloud framework, cloud adoption framework
---

# Cloud adoption

The Adopt methodology shows you how to migrate, modernize, innovate, and relocate workloads in Azure. These four processes align to different phases in the cloud adoption journey. Each phase has distinct goals, solutions, and benefits. This article provides an overview of each process, so you can find the right guidance.

:::image type="content" source="../_images/adopt/modernization-strategy-flowchart.png" alt-text="Diagram that shows possible choices to modernize an application. Each application, in relation to some questions, can be either retired, rebuilt, rearchitected, replaced, rehosted or replatformed." border="false":::

## Migrate

Migration is when you move workloads to the cloud or between clouds. Different types of migration exist, and the migrate guidance shows you how to pick the migration strategy that aligns with your objectives.

- ***Goals:*** Meet business demands, exit on-premises environment, and align to Well-Architected Framework principles.

- ***Solutions:*** Adopt cloud solutions based on business need.

- ***Key benefits:*** Improve security, reliability, performance, and operations with managed solutions. Easily integrate new solutions and design patterns. No need to acquire, manage, and secure hardware.

Migrating an enterprise-scale workload to cloud should require no development effort to create new business logic. It can be performed through a lift and shift approach, also known as ***Rehosting***.

For more information, see [Migrate](../migrate/index.md).

## Modernize

Modernization enhances existing workloads to improve operations, increase efficiency, maximize developer velocity, and reduce the total cost of ownership.

- ***Goals:*** Reduce technical debt, modernize applications, and modernize data platforms.

- ***Solutions:*** Integrate other services and modify code meet business goals.

- ***Key benefits:*** Optimize cost, security, reliability, performance, and operations for increased productivity. You don't need to maintain the underlying infrastructure, so you can focus on your core business.

Generally, application modernization moves toward platform as a service (PaaS) solutions to improve your business at scale. This approach is also referred to as ***Replatforming***.

For more information, see [Modernize](../modernize/index.md).

## Innovate

Innovation is when you adopt cloud-native technologies to create customer-focused solutions that rapidly transform business outcomes.

- ***Goals:*** Reposition your business, reposition technical solutions, and find innovative data plays.

- ***Solutions:*** Adopt data and application capabilities to empower adoption and build predictive tools.

- ***Key benefits:*** Improve predictive analytics, performance, and adaptability.

Application innovation can improve a company's position in the market and unlock new technical capabilities. AI-powered applications can automate existing business processes and provide new ways to engage with customers. Several strategies are available, each one supporting a distinct value and outcome:

- ***Rearchitecting***: Extend and optimize the architecture for cloud capabilities and scale
- ***Rebuilding***: Rebuild the code base from scratch by using cloud-native technologies
- ***Replacing***: Replace the application with SaaS or low-code solutions

For more information, see [Innovate](../innovate/index.md).

## Relocate

Relocation is when you move an Azure workload to a different region in Azure. You can relocate a workload anytime after migration. Relocation evaluations should be a regular part of your workload lifecycle so your workload evolves with your business needs.

- ***Goals:*** Respond to business changes and expand your global footprint, meet data sovereignty and residency requirements, and provide lower latency to end users.

- ***Solutions:*** Adopt the location, services, and capabilities of a new Azure region.

- ***Key benefits:*** Respond to business changes, expand global footprint, meet data sovereignty and residency requirements, provide lower latency to end users.

For more information, see [Relocate](../relocate/index.md).

## Next steps

Follow the guidance that best meets your goals. If you're still considering cloud adoption, it's help to get a sense of what the cloud adoption journey looks like. The next article outlines the typical cloud adoption journey, showing what workloads you should migrate and the order you should migrate them.

> [!div class="nextstepaction"]
> [Cloud adoption journey](cloud-adoption.md)
