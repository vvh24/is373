---
title: Kubernetes vs Docker
date: 2024-10-15 10:00:00
order: 7
---

As we could learn from previous readings: 

**Kubernetes** helps us developers manage complex distibuted systems by asbtracting the underlying infrastructure. It automates the management, scheudling and coordination of containers across a cluster of machines which allows a user to run applications efficiently withothout about the underlying infrastructure. Kubernetes also makes it easy to scale applications up or down based on demand, as this means you can scale the number of containers running an application automatically.

Some advantages of Kubernetes are:
1. Portability and Flexibility
2. Efficient Resource Utilization
3. Rolling Updates and Rollbacks

<img src="/is373hexo/img/kubernetes_vs_docker.png" alt="kuberentes and docker diagram" width= "700"/> and Docker

**Docker** helps us by allowing user to package an application and all of its dependencies into a standerized unit. It ensures that the applications run the same regardless of where they are deployed which eliminates a common of issue "it works on my machine" since the environment is consistent across all stages.

Some advantages of Docker are:
1. Isolation
2. Consistency Across Environments
3. Lighweight and Fast