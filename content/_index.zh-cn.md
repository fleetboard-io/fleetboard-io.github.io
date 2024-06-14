---
title: Nauti 主题
layout: hextra-home
---

{{< hextra/hero-badge >}}
  <div class="hx-w-2 hx-h-2 hx-rounded-full hx-bg-primary-400"></div>
  <span>免费 开源</span>
  {{< icon name="arrow-circle-right" attributes="height=14" >}}
{{< /hextra/hero-badge >}}

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-headline >}}
  多集群网络连接<br class="sm:hx-block hx-hidden" />
以及无缝服务发现
{{< /hextra/hero-headline >}}
</div>

<div class="hx-mb-12">
{{< hextra/hero-subtitle >}}
  Nauti 建立独立统一的并行网络 <br class="sm:hx-block hx-hidden" />
即使在 IP 重叠的情况下也能实现跨集群服务发现。
{{< /hextra/hero-subtitle >}}

</div>

<div class="hx-mb-6">
{{< hextra/hero-button text="现在开始" link="docs" >}}
</div>

<div class="hx-mt-6"></div>

{{< hextra/feature-grid >}}
{{< hextra/feature-card
title="兼容所有CNI插件"
subtitle="Nauti不再限制集群使用的容器网络接口（CNI）插件。无论使用Cilium、Calico、 Flannel、Weave还是其他CNI插件，Nauti都能正常工作。这为用户提供了更大的灵活性和兼容性， 使其能够根据具体需求选择最适合的网络解决方案。"
style="background: radial-gradient(ellipse at 50% 80%,rgba(194,97,254,0.15),hsla(0,0%,100%,0));"
>}}
{{< hextra/feature-card
title="支持Pod CIDR重叠"
subtitle="Nauti允许在多个集群中使用重叠的Pod CIDR。这一特性对于拥有多个独立配置的集群非常有用， 避免了由于CIDR冲突带来的网络配置复杂性，使得跨集群的部署和管理更加简便和高效。"
style="background: radial-gradient(ellipse at 50% 80%,rgba(142,53,74,0.15),hsla(0,0%,100%,0));"
>}}
{{< hextra/feature-card
title="无需集群提供公网IP"
subtitle="Nauti的另一个优势是不要求每个集群提供一个可访问的IP，即可完成隧道建立。这样大大简化了跨集群网络连接的配置要求，提升了部署效率。"
style="background: radial-gradient(ellipse at 50% 80%,rgba(221,210,59,0.15),hsla(0,0%,100%,0));"
>}}
{{< hextra/feature-card
title="跨集群服务发现"
subtitle="Nauti集成了多集群服务发现API，实现跨集群的服务发现和自动注册。"
>}}
{{< hextra/feature-card
title="网络隧道和安全访问"
subtitle="Nauti通过BootStrap Token，确保集群间可以轻易地安全访问，避免了手工拷贝证书和Token的安全性疑虑。"
>}}
{{< hextra/feature-card
title="非侵入性网络配置"
subtitle="Nauti不会侵入性地修改集群节点上的网络配置和策略规则，所有配置都限制在Pod内。这确保了集群节点的原始网络配置不受影响，降低了潜在的风险和运维复杂性。"
>}}
{{< /hextra/feature-grid >}}