# 🌌 Nebulix

> **Cloud without the Cloud.**  
> The modern alternative to OpenStack & VMware: **one binary per node, zero control plane, Rust-fast, Terraform-friendly.**

---

## ✨ What is Nebulix?

Nebulix is a next-generation KVM orchestrator that makes running virtual machines at scale simple:

- **Zero Control Plane** → every node runs the same daemon, Raft-replicated state.  
- **Rust-fast, Ops-easy** → safe by default, single static binary, systemd-native.  
- **Cloud on Bare Metal** → VM lifecycle, networking (bridge/VLAN, security groups), and volumes built-in.  
- **Terraform-friendly** → declarative API and CLI for integration into existing workflows.  

Nebulix brings cloud-like capabilities without the operational complexity of OpenStack or the cost of VMware.

---

## 🚀 Project Status

Nebulix is currently in **early development**.  
We’re building towards our **MVP**:

- VM lifecycle management (create, start, stop, delete)  
- Bridge/VLAN networking + security groups  
- Local volumes & snapshots  
- Go CLI + Terraform provider  
- Cluster state replication via [OpenRaft](https://github.com/databendlabs/openraft)  

---

## 📦 Getting Started

🔗 Docs & quickstart guides will be published soon at [**nebulix.cloud**](https://nebulix.cloud).  
For now, you can **join the early-access waitlist** on our website.

---

## 🛠️ Contributing

We ❤️ community involvement. Contributions will open up as soon as the public repo is ready:

- Join our discussions in [GitHub Issues](https://github.com/nebulix-cloud)  
- Try early builds and give feedback  
- Share ideas and use cases (VMware replacement, OpenStack alternative, Edge deployments)

---

## 📣 Stay Connected

- 🌐 Website: [nebulix.cloud](https://nebulix.cloud)
- 💼 LinkedIn: [Nebulix](https://linkedin.com/company/nebulix)
- 💬 Community (soon): Discord / Slack  

---

## 📜 License

Nebulix Core will be open-sourced under the **Apache-2.0** license.  
Enterprise features & support plans will be available separately.

---

Nebulix — **Made for teams who want cloud without the cloud.**
