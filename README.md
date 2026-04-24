<h1 align="center">Hi there, I'm Kotodian</h1>

<p align="center">
  <b>Kernel & eBPF Networking | VPN Protocols | High-performance Proxy Systems</b>
</p>

<p align="center">
  Building Linux datapaths, VPN/proxy protocols, and cross-platform networking products.
</p>

---

### Featured Project

<table>
  <tr>
    <td width="400">
      <h3><a href="https://github.com/Kotodian/calamity">Calamity</a></h3>
      <p>A modern macOS & Linux proxy client powered by sing-box, built with Tauri 2 + React.</p>
      <p>
        <img src="https://img.shields.io/github/v/release/Kotodian/calamity?include_prereleases&style=flat-square&color=e94560" alt="Release" />
        <img src="https://img.shields.io/github/downloads/Kotodian/calamity/total?style=flat-square&color=16213e" alt="Downloads" />
      </p>
      <ul>
        <li>Rule-based routing, TUN mode, Fake-IP DNS</li>
        <li>Process-based routing</li>
        <li>Gateway Mode — transparent LAN proxy</li>
        <li>BGP Rule Sync — sync rules between instances over Tailscale</li>
        <li>Tailscale integration with MagicDNS</li>
        <li>Linux support — headless daemon + CLI, deb/rpm/pacman/tarball</li>
        <li>Ruleset marketplace & subscription management</li>
        <li>Light / Dark theme, EN & ZH-CN</li>
      </ul>
    </td>
    <td>
      <a href="https://github.com/Kotodian/calamity">
        <img src="https://raw.githubusercontent.com/Kotodian/calamity/main/docs/screenshots/dashboard-dark.png" alt="Calamity Dashboard" width="500" />
      </a>
    </td>
  </tr>
</table>

---

### Current Focus

- Container networking datapaths: Docker netkit, eBPF port mapping, SNAT/MASQ, cgroup socket hooks, BIG TCP.
- High-performance packet processing: VPP, XDP/AF_XDP zero-copy, Linux kernel driver work.
- Proxy and VPN systems: QUIC/MASQUE, OpenVPN/IPsec acceleration, sing-box-based desktop clients.

---

### Other Projects

| Project | Description | Stack |
|:--------|:-----------|:------|
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
