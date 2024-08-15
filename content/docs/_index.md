---
linkTitle: "Documentation"
title: Introduction
---

👋 Hello! Welcome to the FleetBoard documentation!

<!--more-->

## What is FleetBoard?

FleetBoard is a multi-cluster interconnection and service discovery management tool jointly developed by the NRI community 
and the Clusternet community. It can help users easily manage and connect multiple Kubernetes clusters in different 
cloud environments (such as public cloud, private cloud, hybrid cloud, and edge computing). FleetBoard achieves cross-cluster 
network connectivity through configurable network tunnel settings and provides a consistent service discovery mechanism,
making cross-cluster access to services as simple as accessing a local cluster.
## Features

- **Compatible with all CNI plugins** - FleetBoard no longer limits the container network interface (CNI) plugins used by the cluster. FleetBoard works regardless of whether Cilium, Calico, Flannel, Weave, or other CNI plugins are used. This provides users with greater flexibility and compatibility, allowing them to choose the most suitable network solution according to their specific needs."
- **Support Pod CIDR overlap** - FleetBoard allows overlapping Pod CIDRs to be used in multiple clusters. This feature is very useful for clusters with multiple independent configurations, avoiding the complexity of network configuration caused by CIDR conflicts, making cross-cluster deployment and management easier and more efficient."
- **No cluster is required to provide an accessible IP** - Another advantage of FleetBoard is that tunnel establishment can be completed without requiring each cluster to provide an accessible IP. This greatly simplifies the configuration requirements for cross-cluster network connections and improves deployment efficiency."
- **Cross-cluster service discovery** - FleetBoard integrates a multi-cluster service discovery API to achieve cross-cluster service discovery and automatic registration."
- **Network tunnel and secure access** - FleetBoard uses BootStrap Token to ensure that clusters can be easily and securely accessed, avoiding security concerns about manually copying certificates and tokens."
- **Non-invasive network configuration** - FleetBoard does not intrusively modify the network configuration and policy rules on the cluster nodes, and all configurations are limited to the Pod. This ensures that the original network configuration of the cluster nodes is not affected, reducing potential risks and operational complexity."

## Questions or Feedback?

{{< callout emoji="❓" >}}
FleetBoard is still in active development.
  Have a question or feedback? Feel free to [open an issue](https://github.com/fleetboard-io/fleetboard/issues)!
{{< /callout >}}

## Next

Dive right into the following section to get started:

{{< cards >}}
  {{< card link="getting-started" title="Getting Started" icon="document-text" subtitle="Learn how to connect Multi-Clusters using FleetBoard" >}}
{{< /cards >}}

