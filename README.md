# 🧱 IaaS Foundations — Compute, Networking, Storage, Regions

Deck **02 of 6** in the [Cloud `*aaS` series](https://github.com/BrendanJamesLynskey/Cloud_aaS_Hub). The IaaS floor — VMs, VPCs, storage, regions, identity primitives — that every higher *aaS layer is built on.

## ▶ [Open the Presentation](https://brendanjameslynskey.github.io/Cloud_aaS_02_IaaS_Foundations/)

## 🧭 [Series hub](https://github.com/BrendanJamesLynskey/Cloud_aaS_Hub)

---

## Contents

| # | Topic | Description |
|---|-------|-------------|
| 01 | Title | Compute · Network · Storage · Identity → a system |
| 02 | Topics | Map of compute, networking, storage, operability |
| 03 | The VM as a primitive | Hypervisors (Nitro, Andromeda, Hyper-V, Firecracker), instance families, ARM (Graviton, Axion, Cobalt) |
| 04 | Spot &amp; preemptible | Three flavours, when to use, when it hurts, diversified pools, bare metal |
| 05 | The VPC anatomy | Three-tier subnets, two AZs, IGW, NAT — annotated diagram |
| 06 | Routing — IGW · NAT · Endpoints | NAT gateway costs, peering / Transit Gateway / PrivateLink, on-prem ↔ cloud |
| 07 | Security Groups vs NACLs | Stateful vs stateless, defence-in-depth, the SG-on-0.0.0.0/0 anti-pattern |
| 08 | Storage — block / object / file | Side-by-side comparison: latency, throughput, pricing shape, best fit |
| 09 | Storage class lifecycle | S3 classes, lifecycle XML rule, R2 disruption, cost gotchas |
| 10 | Regions &amp; AZs | Region anatomy diagram, multi-region patterns (active-passive, active-active, global) |
| 11 | Cloud identity primitives | Things that have identity, IAM building blocks, sample policy, no-long-lived-keys |
| 12 | Observability primitives | Metrics / logs / traces, four golden signals, the cloud-bill-as-observability anti-pattern |
| 13 | Provisioning — IaC | Terraform / OpenTofu / Pulumi / CDK, ops practices, GitOps for IaC |
| 14 | What costs money on IaaS | Compute / storage / network breakdown, surprise generators, FinOps essentials |
| 15 | When IaaS still wins | Specialised kernels, stateful, compliance, cost ceilings — vs when to climb |
| 16 | Anti-patterns | Pets-not-cattle, public IPs, static keys, all-AZ planning, no-restore-drill |
| 17 | Summary | Three takeaways &amp; next-deck pointer |

---

## Slide Controls

| Action | Key |
|--------|-----|
| Next / Previous | `→` `←` or swipe |
| Overview | `Esc` |
| Fullscreen | `F` |
| Speaker notes | `S` |
| Export to PDF | append `?print-pdf` to URL, then print |

## Technology

[Reveal.js 4.6](https://revealjs.com) · [highlight.js](https://highlightjs.org) · Big Shoulders Display + Public Sans + Overpass Mono · inline SVG diagrams. Single self-contained `index.html`.

## See also

- [Deploying with Docker](https://github.com/BrendanJamesLynskey/Deploying_with_Docker) — what you put on these VMs
- [Deploying Node.js Microservices](https://github.com/BrendanJamesLynskey/Deploying_Node_Microservices) — service architecture on top
- [Introduction to CI/CD](https://github.com/BrendanJamesLynskey/Introduction_to_CI_CD) — the pipeline that drives provisioning
- Next in this series: [Cloud_aaS_03_PaaS_FaaS_CaaS](https://github.com/BrendanJamesLynskey/Cloud_aaS_03_PaaS_FaaS_CaaS) — managed compute layers above IaaS

## License

Educational use. Code examples provided as-is.
