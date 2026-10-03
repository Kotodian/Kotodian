<h1 align="center">Hi there, I'm Kotodian</h1>

<p align="center">
  <b>Kernel & eBPF Networking | VPN Protocols | High-performance Proxy Systems</b>
</p>

<p align="center">
  Building Linux datapaths, VPN/proxy protocols, and cross-platform networking products.
</p>

---

### Featured Project

#### [netsystem — Rewrite VPP into Rust](https://github.com/Kotodian/netsystem-rs)

A standalone network data-plane framework rewriting FD.io Vector Packet
Processing (VPP) in Rust, with VPP's packet graph and worker ownership model.
Under active development.

- Vector packet processing with batched Frames and compact Buffer Indices.
- Worker-owned graph execution, explicit handoff, CPU/NUMA placement, and Buffer Pools.
- Main-thread async Process Nodes, io_uring file scheduling, CLI, and Binary API.
- Session RX/TX FIFOs and message queues, with independent TUN, IP, ICMP, TCP, and iperf3 plugins.
- Shared-memory statistics, packet tracing, and architecture decisions grounded in VPP source.

[Architecture and module overview](https://github.com/Kotodian/netsystem-rs#architecture) ·
[Architecture decisions](https://github.com/Kotodian/netsystem-rs/tree/main/docs/adr)

---

### Current Focus

- Container networking datapaths: Docker netkit, eBPF port mapping, SNAT/MASQ, cgroup socket hooks, BIG TCP.
- High-performance packet processing: VPP, XDP/AF_XDP zero-copy, Linux kernel driver work.
- Proxy and VPN systems: QUIC/MASQUE, OpenVPN/IPsec acceleration, sing-box-based desktop clients.

---

### Other Projects

| Project | Description | Stack |
|:--------|:-----------|:------|
| [Calamity](https://github.com/Kotodian/calamity) | macOS & Linux proxy client powered by sing-box, with rule-based routing, TUN, and Tailscale integration | Rust, Tauri 2, React |
| [VPP-OpenVPN](https://github.com/Kotodian/vpp-more) | High-performance OpenVPN data plane acceleration via VPP, 10x faster | C, VPP |
| [StrongSwan-GM](https://github.com/Kotodian/strongswan-gm) | IPsec VPN with Chinese National Cryptography (SM2/SM3/SM4) | C, StrongSwan |
| [Docker Netkit eBPF](https://github.com/Kotodian/moby) | Docker netkit datapath work: eBPF published-port mapping, egress MASQ, cgroup socket hooks, and BIG TCP validation | Go, C, eBPF |
| [Linux vmxnet3 AF_XDP ZC](https://github.com/Kotodian/linux/tree/vmxnet3-xsk-zc) | AF_XDP zero-copy RX/TX ported to VMware's paravirt NIC driver, bisect-safe 7-commit series | C, XDP, Kernel |

---

### Tech Stack

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tauri](https://img.shields.io/badge/Tauri-FFC131?style=for-the-badge&logo=tauri&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![eBPF](https://img.shields.io/badge/eBPF-FF6B6B?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![XDP](https://img.shields.io/badge/XDP-1F6FEB?style=for-the-badge)
![VPP](https://img.shields.io/badge/VPP-2E3440?style=for-the-badge)
