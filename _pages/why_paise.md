---
layout: page
title: Why PAISE?
permalink: /why_paise
nav: true
nav_order: 1
---

Applications involving voluminous data often necessitate the computing to be performed as close to the data source as possible, due to communication constraints, latency requirements, privacy and sensitivity of data as well as costs associated with moving it. Given the recent advances in algorithms and techniques, as well as the increasing and improving last-mile wireless connectivity with the emergence of LoRaWAN, 5G and Wi-Fi 6, more and more application scenarios with the above requirements are becoming a reality. However, this reality comes with its own set of challenges for the applications as well as the wide range of edge computing platforms that support them.

First of all, these applications have various runtime requirements (e.g., continuous versus event-driven) and diverse resource demands (e.g., GPUs). Similarly, the platforms they run on are diverse in terms of their architectures, hardware capabilities and programming models, spanning from intelligent embedded devices (e.g., smart cameras) to on-premise systems (e.g., small-scale server racks). Due to the usually limited capacity at the edge for computation, network bandwidth and energy, sharing such heterogeneous resources among applications with different, and sometimes conflicting, requirements becomes an imminent challenge with multi-tenancy considerations.

Second, the allocation and orchestration of these limited computing and network resources will experience many challenges currently encountered in cloud computing, but with the complexity and heterogeneity of the edge. This complexity and heterogeneity will require cooperation and coordination of various parts of the software stack. Devising mechanisms for this goal will involve the data and control plane of the applications to fine-tune their behavior and change their operational parameters. As a result, DevOps and management problems for the infrastructure will have to be solved. 
Finally, coupling these applications with their centrally located cloud and HPC counterparts will increase their effectiveness but also will create new challenges.

As we push more toward edge-enabled networks of devices, we inherit a setting where resources are deployed away from the safety of secure indoor spaces, often in the midst of a bustling urban canyon, and exposed to physical and cybersecurity threats. Deployed and interconnected predominantly over public networks, these systems have to be designed with cybersecurity as a first-class design citizen, ensuring not only the integrity and confidentiality of the data, but also the correct and accountable processing of it.

At PAISE, we aim to discuss these topics from the perspectives of different members of the edge community, ranging from software to hardware researchers as well as from academia to industry. Our ultimate goal is to identify gaps in our thinking and to foster collaboration for addressing those gaps.

