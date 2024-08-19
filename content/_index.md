---
title: FleetBoard Theme
layout: hextra-home
---

{{< hextra/hero-badge >}}
  <div class="hx-w-2 hx-h-2 hx-rounded-full hx-bg-primary-400"></div>
  <span>Free, open source</span>
  {{< icon name="arrow-circle-right" attributes="height=14" >}}
{{< /hextra/hero-badge >}}

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-headline >}}
  Multi-Cluster Connection &nbsp;<br class="sm:hx-block hx-hidden" /> 
and Seamless Cross Cluster service discovery.
{{< /hextra/hero-headline >}}
</div>

<div class="hx-mb-12">
{{< hextra/hero-subtitle >}}
FleetBoard establishes an independent and unified parallel network, facilitating cross-cluster service discovery even in cases of IP overlap.
{{< /hextra/hero-subtitle >}}
</div>

<div class="hx-mb-6">
{{< hextra/hero-button text="Get Started" link="docs" >}}
</div>

<div class="hx-mt-6"></div>

{{< hextra/feature-grid >}}
{{< hextra/feature-card
title="Compatible with all CNI plugins"
subtitle="FleetBoard no longer limits the container network interface (CNI) plugins used by the cluster. FleetBoard works regardless of whether Cilium, Calico, Flannel, Weave, or other CNI plugins are used. This provides users with greater flexibility and compatibility, allowing them to choose the most suitable network solution according to their specific needs."
style="background: radial-gradient(ellipse at 50% 80%,rgba(194,97,254,0.15),hsla(0,0%,100%,0));"
>}}
{{< hextra/feature-card
title="Support Pod CIDR overlap"
subtitle="FleetBoard allows overlapping Pod CIDRs to be used in multiple clusters. This feature is very useful for clusters with multiple independent configurations, avoiding the complexity of network configuration caused by CIDR conflicts, making cross-cluster deployment and management easier and more efficient."
style="background: radial-gradient(ellipse at 50% 80%,rgba(142,53,74,0.15),hsla(0,0%,100%,0));"
>}}
{{< hextra/feature-card
title="No cluster is required to provide an accessible IP"
subtitle="Another advantage of FleetBoard is that tunnel establishment can be completed without requiring each cluster to provide an accessible IP. This greatly simplifies the configuration requirements for cross-cluster network connections and improves deployment efficiency."
style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.15),hsla(0,0%,100%,0));"
>}}
{{< hextra/feature-card
title="Cross-cluster service discovery"
subtitle="FleetBoard integrates a multi-cluster service discovery API to achieve cross-cluster service discovery and automatic registration."
>}}
{{< hextra/feature-card
title="Network tunnel and secure access"
subtitle="FleetBoard uses BootStrap Token to ensure that clusters can be easily and securely accessed, avoiding security concerns about manually copying certificates and tokens."
>}}
{{< hextra/feature-card
title="Non-invasive network configuration"
subtitle="FleetBoard does not intrusively modify the network configuration and policy rules on the cluster nodes, and all configurations are limited to the Pod. This ensures that the original network configuration of the cluster nodes is not affected, reducing potential risks and operational complexity."
>}}
{{< /hextra/feature-grid >}}
