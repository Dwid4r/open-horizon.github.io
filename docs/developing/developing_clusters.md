---
copyright: Contributors to the Open Horizon project
years: 2021 - 2025
title: Edge services for clusters
description: Documentation for Developing an edge service for clusters
lastupdated: 2025-05-03
nav_order: 3
parent: Developing edge services
has_children: True
has_toc: False
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}

# Developing an edge service for clusters
{: #developing_clusters}

{{site.data.keyword.edge_notm}} ({{site.data.keyword.ieam}}) edge cluster capability provides you with edge computing features to help you manage and deploy workloads from a management hub cluster to remote instances of OpenShift® Container Platform or other Kubernetes-based clusters. Edge clusters are {{site.data.keyword.ieam}} edge nodes that are Kubernetes clusters. An edge cluster enables use cases at the edge, which require co-location of compute with business operations, or that require more scalability, availability, and compute capability than what can be supported by an edge device. Further, it is not uncommon for edge clusters to provide application services that are needed to support services running on edge devices due to their close proximity to edge devices, resulting in a multi-tier edge application. {{site.data.keyword.ieam}} deploys edge services to an edge cluster via a Kubernetes operator, enabling the same autonomous deployment mechanisms used with edge devices. The full power of Kubernetes as a container management platform is available for edge services that are deployed by {{site.data.keyword.ieam}}.

![Developing an edge service for clusters](../../images/edge/03b_Developing_edge_service_for_cluster.svg "Developing an edge service for clusters")

* [Developing a Kubernetes operator](service_operators.md)
* [Creating your own hello world for clusters](creating_hello_world.md)
