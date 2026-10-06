# Awesome-Network-Load-Balancing-L4 ⚖️ 🌐

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Network Load Balancing L4 Ecosystem Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Network-Load-Balancing-L4"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Network-Load-Balancing-L4?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Network-Load-Balancing-L4/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Network-Load-Balancing-L4?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Network-Load-Balancing-L4/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Network-Load-Balancing-L4?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Network Load Balancing (L4) Ecosystem

**Curated List of Commercial Load Balancers & Open-Source L4 Proxy Solutions**  
*Focused on Layer 4 (TCP/UDP) Load Balancing, High Availability, DDoS Mitigation & Kernel-Level Packet Forwarding*  

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **Layer 4 network load balancing solutions**, **open-source TCP/UDP proxies**, and **kernel-level packet forwarding engines**. Whether you are looking for enterprise-grade commercial L4 load balancers (such as *AWS Network Load Balancer*, *Azure Load Balancer*, *Google Cloud Network Load Balancing*, and *F5 BIG-IP*), or high-performance open-source alternatives (like *NGINX*, *Envoy Proxy*, *HAProxy*, *DPVS*, *Katran*, and *Seesaw*), this list covers category leaders, kernel bypass frameworks, eBPF/XDP bypass engines, and cloud-native ingress solutions.

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

> **Market Insights & Industry Dynamics** 📈  
> The global Application Delivery Controller (ADC) and L4 Load Balancing market is estimated at **$6.5 Billion+** and growing at ~12% CAGR. The sector is **highly concentrated** among hyper-scale cloud providers (Microsoft, Amazon, Google) and legacy network hardware giants (F5 Networks, A10 Networks), exhibiting strong scale economies where cloud hyperscalers capture the vast majority of elastic infrastructure workloads.

*Sorted by Valuation / Market Cap (Descending)* 💰

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Azure Load Balancer](https://azure.microsoft.com/en-us/products/load-balancer/)** ☁️ | Microsoft | $3,800,000,000,000 ($3.8T) | Standard: $0.025/hr + $0.005/GB processed; Basic: Free | Basic edition free forever (no SLA, non-redundant); 30-day / $200 Azure credit trial for Standard | **Cloud-native L4 load balancer** — ultra-low latency, TCP/UDP, zone-redundant, supports inbound NAT rules. |
| **[AWS Network Load Balancer](https://aws.amazon.com/elasticloadbalancing/network-load-balancer/)** 🌐 | Amazon | $2,000,000,000,000 ($2.0T) | $0.0225/hr + $0.006/NLCU-hr | No permanent free tier; 12 months free (750 hrs/mo combined ELB) for new AWS accounts | **Hyper-scale L4 load balancer** — millions of requests/sec, static IP per AZ, preserves source IP, TLS offloading. |
| **[Google Cloud Network Load Balancing](https://cloud.google.com/load-balancing/docs/network)** 🔷 | Google (Alphabet) | $2,000,000,000,000 ($2.0T) | $0.025/hr (first 5 rules) + $0.008 to $0.01/GB processed | No permanent free tier; 90-day / $300 free trial credits for new Google Cloud accounts | **Regional L4 load balancer** — supports TCP/UDP, external/internal, pass-through and proxy modes. |
| **[F5 BIG-IP](https://www.f5.com/products/big-ip-services)** 🏢 | F5 Networks | $10,000,000,000 ($10B) | BIG-IP Virtual Edition: $3,812/year; Hardware appliances: ~$10,000 upfront | No permanent free tier; 30-day evaluation license available for BIG-IP Virtual Edition | **Enterprise ADC** — advanced L4-L7, iRules scripting, SSL offload, DDoS protection, hardware acceleration. |
| **[NGINX Plus](https://www.nginx.com/products/nginx/)** 🟢 | F5 (Acquired NGINX) | $10,000,000,000 ($10B) | $2,500/year per instance (Basic subscription) | Open Source NGINX free forever (BSD license); 30-day free trial for NGINX Plus | **L4/L7 load balancer** — `stream` module for TCP/UDP, round-robin, least connections, hash, health checks. |
| **[Kemp LoadMaster](https://kemptechnologies.com/)** ⚙️ | Progress Software | $1,500,000,000 ($1.5B) | Virtual LoadMaster: $13,450 (1 Gbps perpetual license); Subscription: ~$1,500/year | Free Forever Edition available (limited to 20 Mbps throughput); 30-day full-feature trial | **Application delivery controller** — L4/L7 balancing, WAF, edge security, per-app licensing. |
| **[A10 Networks Thunder](https://a10networks.com/)** 🎛️ | A10 Networks | $500,000,000 ($500M) | Thunder 3350 Appliance: $41,864; vThunder Virtual: ~$2,500/year license | No permanent free tier; 30-day virtual appliance trial available upon request | **High-performance ADC** — CGN, DDoS mitigation, SSL inspection, 800M concurrent sessions. |
| **[Envoy Proxy (Commercial Support)](https://www.envoyproxy.io/)** 🔵 | Solo.io / Tetrate | Private ($1,000,000,000+) | Commercial support (Solo.io Gloo Network): ~$1,200/node/year | Envoy Proxy is 100% open source & free forever (Apache-2.0); Commercial 30-day trial | **Edge/service proxy** — L4 TCP proxy filter, cluster management, observability, dynamic configuration. |
| **[HAProxy Enterprise](https://www.haproxy.com/)** 🏎️ | HAProxy Technologies | Private ($100,000,000+) | AWS Marketplace: $0.15/hr per instance; Annual subscriptions start at ~$3,500/node/yr | Community edition free forever (GPL); 30-day trial available for Enterprise Edition | **High-performance L4/L7 proxy** — connection rate limiting, stick tables, seamless reload, advanced health checks. |
| **[Snapt Nova](https://snapt.io/)** 🚀 | Snapt (Acquired) | Private ($20,000,000+) | Developer / Starter tier: $99/month per node | Free Forever Developer Tier: up to 1 node, 5 Mbps max bandwidth; 14-day Pro trial | **Cloud-native ADC** — L4/L7 load balancing, WAF, API gateway, supports multi-cloud deployments. |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub Stars Count (Descending)* 🌟

- **[NGINX](https://github.com/nginx/nginx)** [![Stars](https://img.shields.io/github/stars/nginx/nginx?style=social&color=white)](https://github.com/nginx/nginx/stargazers) 🟢  
  **High-performance web server and reverse proxy**, BSD-2-Clause licensed. `stream` module provides L4 TCP/UDP load balancing with round-robin, least connections, hash, and random algorithms.

- **[Traefik](https://github.com/traefik/traefik)** [![Stars](https://img.shields.io/github/stars/traefik/traefik?style=social&color=white)](https://github.com/traefik/traefik/stargazers) 🚦  
  **Cloud-native application proxy**, MIT licensed. Supports TCP and UDP L4 routing alongside HTTP/HTTPS, with automatic Kubernetes service discovery and dynamic configuration.

- **[Envoy Proxy](https://github.com/envoyproxy/envoy)** [![Stars](https://img.shields.io/github/stars/envoyproxy/envoy?style=social&color=white)](https://github.com/envoyproxy/envoy/stargazers) 🔷  
  **Cloud-native high-performance edge/middle/service proxy**, Apache-2.0 licensed. L4 `tcp_proxy` network filter with route matching, cluster management, and observability. The data plane for Istio and modern service meshes.

- **[Caddy](https://github.com/caddyserver/caddy)** [![Stars](https://img.shields.io/github/stars/caddyserver/caddy?style=social&color=white)](https://github.com/caddyserver/caddy/stargazers) ⚡  
  **Fast and extensible multi-platform web server with automatic HTTPS**, Apache-2.0 licensed. Layer 4 app module (`caddy-l4`) allows raw TCP/UDP multiplexing, TLS termination, and proxying.

- **[HAProxy](https://github.com/haproxy/haproxy)** [![Stars](https://img.shields.io/github/stars/haproxy/haproxy?style=social&color=white)](https://github.com/haproxy/haproxy/stargazers) 🏆  
  **The world's fastest and most widely used software load balancer**, GPL-2.0 licensed. L4 TCP/HTTP proxy with connection rate limiting, stick tables, seamless reload, and advanced health checking.

- **[Katran](https://github.com/facebookincubator/katran)** [![Stars](https://img.shields.io/github/stars/facebookincubator/katran?style=social&color=white)](https://github.com/facebookincubator/katran/stargazers) 🛡️  
  **Facebook's high-performance L4 load balancer based on XDP/eBPF**, GPL-2.0 licensed. Kernel-level forwarding, consistent hashing, supports DSR (Direct Server Return), used in Meta infrastructure.

- **[Seesaw](https://github.com/google/seesaw)** [![Stars](https://img.shields.io/github/stars/google/seesaw?style=social&color=white)](https://github.com/google/seesaw/stargazers) 🔍  
  **Linux Virtual Server (LVS) based load balancer**, Apache-2.0 licensed. Google's open-source L4 load balancer with robust health checking, Anycast VIP routing, and BGP integration.

- **[MetalLB](https://github.com/metallb/metallb)** [![Stars](https://img.shields.io/github/stars/metallb/metallb?style=social&color=white)](https://github.com/metallb/metallb/stargazers) 🛠️  
  **Bare-metal load balancer implementation for Kubernetes**, Apache-2.0 licensed. Provides L4 load balancing via ARP/NDP (L2 mode) or BGP mode for standard Kubernetes `LoadBalancer` services.

- **[DPVS](https://github.com/iqiyi/dpvs)** [![Stars](https://img.shields.io/github/stars/iqiyi/dpvs?style=social&color=white)](https://github.com/iqiyi/dpvs/stargazers) 🚀  
  **High-performance L4 load balancer based on DPDK**, GPL-2.0 licensed. Full-NAT/DR/Tunneling modes, kernel bypass, millions of concurrent connections, supports IPVS-compatible management.

- **[Keepalived](https://github.com/acassen/keepalived)** [![Stars](https://img.shields.io/github/stars/acassen/keepalived?style=social&color=white)](https://github.com/acassen/keepalived/stargazers) 🩺  
  **VRRP high availability and LVS health checking daemon**, GPL-2.0 licensed. Provides failover VIP capability for Linux IPVS/LVS clusters and load balancer instances.

- **[LVS (Linux Virtual Server / IPVS)](https://github.com/alibaba/lvs)** [![Stars](https://img.shields.io/github/stars/alibaba/lvs?style=social&color=white)](https://github.com/alibaba/lvs/stargazers) 🐧  
  **Advanced IP load balancing inside the Linux kernel**, GPL-2.0 licensed. IPVS (IP Virtual Server) provides kernel-level L4 NAT, DR (Direct Routing), and TUN tunneling for massive scaling.

- **[OpenELB](https://github.com/kubesphere/openelb)** [![Stars](https://img.shields.io/github/stars/kubesphere/openelb?style=social&color=white)](https://github.com/kubesphere/openelb/stargazers) 🏗️  
  **Bare-metal load balancer for Kubernetes**, Apache-2.0 licensed. Supports BGP, ECMP, and L2 VIP mode for exposing internal services to external networks.

- **[kube-vip](https://github.com/kube-vip/kube-vip)** [![Stars](https://img.shields.io/github/stars/kube-vip/kube-vip?style=social&color=white)](https://github.com/kube-vip/kube-vip/stargazers) 🛠️  
  **Virtual IP and L4 load balancer for Kubernetes control plane and services**, Apache-2.0 licensed. Provides ARP/NDP and BGP-based HA load balancing.

- **[gobetween](https://github.com/yyyar/gobetween)** [![Stars](https://img.shields.io/github/stars/yyyar/gobetween?style=social&color=white)](https://github.com/yyyar/gobetween/stargazers) 🛣️  
  **Modern & minimalistic L4 load balancer**, MIT licensed. Written in Go, supports TCP, UDP, TLS termination, and service discovery backends (Consul, Etcd, DNS).

- **[nftlb](https://github.com/zevenet/nftlb)** [![Stars](https://img.shields.io/github/stars/zevenet/nftlb?style=social&color=white)](https://github.com/zevenet/nftlb/stargazers) 🔥  
  **nftables-based high performance L4 load balancer**, AGPL-3.0 licensed. Supports DSR, DNAT, SNAT, IPv4/IPv6, TCP/UDP/SCTP balancing, and JSON API for dynamic reconfiguration.

- **[Pen](https://github.com/UlricE/pen)** [![Stars](https://img.shields.io/github/stars/UlricE/pen?style=social&color=white)](https://github.com/UlricE/pen/stargazers) 🖊️  
  **Ultra-lightweight load balancer for TCP and UDP**, GPL-2.0 licensed. Supports source IP hashing, round-robin, and background server health checks.

- **[arca-lb](https://github.com/akam1o/arca-lb)** [![Stars](https://img.shields.io/github/stars/akam1o/arca-lb?style=social&color=white)](https://github.com/akam1o/arca-lb/stargazers) ⚡  
  **VPP-based Layer 4 load balancing control plane for Kubernetes**, Apache-2.0 licensed. Declarative VIP management via Custom Resource, line-rate packet processing.

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new L4 load balancing platforms or open-source proxy software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Network-Load-Balancing-L4&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Network-Load-Balancing-L4&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

Thank you for visiting and using this repository! Your support keeps this curated index of Layer 4 network load balancing technologies up-to-date for the community.

If you find this repository helpful, please consider supporting the project:
- ⭐ **Star** this repository to help others discover it!
- 🔀 **Fork** and share it with your team, network engineers, and SRE colleagues.
- ☕ **Buy Me a Coffee**: Support ongoing maintenance and curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- L4 load balancers sit in the critical path of production traffic. **Always test failover and health checking** before deploying to production. 🔒
- Open-source L4 solutions (HAProxy, Envoy, DPVS, Katran, Seesaw, nftlb) offer kernel-level performance and massive scalability, but enterprise-grade SLA guarantees, advanced DDoS mitigation, and vendor support remain primarily commercial offerings. ⚖️

---

<p align="center">
  <b>Made with ❤️ for network engineers, SRE teams, and open-source infrastructure developers.</b>
</p>
