![Docker Logo](https://th.bing.com/th/id/R.a2f46e02ea8f7f8af6c6989687bd6b52?rik=0keMY0UQso%2b1kg&riu=http%3a%2f%2flogz.io%2fwp-content%2fuploads%2f2016%2f01%2fdocker-facebook.png&ehk=vi9I6O3dyq5d2%2bOmy8ZDLrWQv2LbFNVfkFhTEcajShM%3d&risl=&pid=ImgRaw&r=0)

<!--
 🐋 `README.md` — Docker for Windows Quick‑Start Guide
 Last updated: 2025‑08‑04
-->

# 🐳 Docker Desktop on **Windows 10/11 (WSL 2 Backend)** — Quick Start Guide

> This guide walks you through installing Docker Desktop on a Windows 10/11 machine, enabling WSL 2, and running the official `ubuntu` image interactively using the `docker run -it ubuntu` command.

---

## ✅ Supported Platforms & Prerequisites

| Requirement | Minimum Version / Detail |
|-------------|----------------------------|
| **Windows 11** | 64‑bit, Home/Pro/Education, version **22H2+** |
| **Windows 10** | 64‑bit, Home/Pro/Education, **22H2** (build **19045**) or later |
| **WSL 2 (Linux kernel)** | Version **2.1.5+** installed and enabled |
| **Hardware virtualization** | SLAT support enabled in BIOS/UEFI with ≥ 4 GB RAM |

Docker Desktop requires **Windows 10/11 with build 19045 or later and WSL 2 version ≥ 2.1.5** to work correctly :contentReference[oaicite:0]{index=0}.

---

## 📥 Step 1: Install or Update **WSL 2**

Open **PowerShell as Administrator** and run:

```powershell
wsl --install       # Installs WSL + Ubuntu distro on both Windows 10 and 11
# Or:
wsl --update        # If WSL is already installed but needs updating




## Post installing  Docker

 1)run cmd or powershell
 2)docker pull ubuntu
 3)docker run -it ubuntu
