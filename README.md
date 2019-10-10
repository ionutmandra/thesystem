### Journey: 
---
**Zoom 0 in **Organisation****:  
Organisation strategy [Portofolio -> Program -> Project] ->  
**Project**: Initiating -> Planning -> Executing -> Monitoring and Controlling -> Closing  

Next picture is from thoughtworks free chapter for EDGE book:
![alt text](https://github.com/ionutmandra/thesystem/blob/master/ThoughtworksEDGE.png)


**Zoom 1 in Project**:  
Project details [Requirements, Budget, Resources, Timeline ... ] ->  
Upfront planning (when most of constraints are clear) vs **Agile** (less initial planning, iterate, adjust)

**Zoom 2 in Architecture**:  
*  Enterprise level - Enterprise Integration Patterns (Enterprise Integration Patterns: Designing, Building, and Deploying Messaging Solutions 1st Edition)  
* Application level - Patterns of Enterprise Application Architecture
* Components level - Design patterns
* Code - SOLID  

**Zoom 3 in Application Architecture**: 
* ? Hosting / platform / OS: Cloud native, On premise, Hybrid, Linux, Windows
* ? If cloud, choose cloud agnostic design (containers, Kubernetes, KNative Serverless) vs cloud specific ?
* ? Governance ( accounts, subscriptions, tenants, identities, environments)
* ? How many systems (1 monolith vs more smaller systems working together?)  
* ? Split services - What is the core domain, the one that gives the competitive advantage ? What are the subdomains that can have their own services  (DDD Context mapping, bounded contexts)
* ? Crosscutting concerns: Discoverability, Logging, Monitoring..
* ? Business continuity, disaster recovery
* ? Operations processes
* ? Quality automated tests - Pyramid

* ? Inside Service
   * Layers/Tiers: monolith / onion / hexagonal / n layers / “cookie cutter” approach / package by component / verticals
   * Storage type
   * Commands and queries
   * Communication - Sync, async, fire and forget, notifications(SingalR, WebSockets), queues, long process (choreography vs orchestration)
   * DDD - Domain and app services, aggregate roots, transactions inside AR, between AR, eventual consistency accross Contexts
   * Authentication flows, providers, federated
   * Authorization
   * High availability: Scale out (static, dynamic) 

  
### Principles:
---
General
* https://12factor.net/ (TODO add separate page + link here)  
* https://www.reactivemanifesto.org/
* aws https://aws.amazon.com/architecture/well-architected/  
* azure https://docs.microsoft.com/en-us/learn/modules/pillars-of-a-great-azure-architecture/
* https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/reference/networking-vdc#virtual-datacenter-overview








