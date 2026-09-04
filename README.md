<div align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:00FF41&height=170&section=header&text=RHCSA%20Home%20Lab&fontColor=00FF41&fontSize=38&animation=fadeIn" width="100%"/></div>

<div align="center">

# 🐧 RHCSA Home Lab

**A production-style Red Hat Enterprise Linux lab I built to learn systems the way they actually break.**

![RHEL](https://img.shields.io/badge/RHEL_9-EE0000?style=for-the-badge&logo=redhat&logoColor=white)
![KVM](https://img.shields.io/badge/KVM_/_libvirt-333?style=for-the-badge&logo=linux&logoColor=white)
![Bash](https://img.shields.io/badge/Bash_Automation-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

</div>

---

## Why

Reading about Linux administration isn't the same as running it. So I built a **full nested-virtualization lab** — multiple RHEL machines with real infrastructure services — where I can break, fix, and re-break things safely, over and over.

## What's inside

- 🖥️ **Multiple RHEL 9 hosts** (server + client roles) running under KVM/libvirt on a virtualized ESXi backend.
- 🌐 **Core infra services**: DNS resolution, local package repositories, a container registry, NFS shares, and time sync (chrony).
- 📦 **Containers** with Podman — building images offline and running them as systemd services.
- 🔐 **Users, groups, permissions, ACLs, sudo** — the daily bread of the RHCSA.
- 💾 **Storage**: partitions, LVM, filesystems, autofs, swap.
- ⚙️ **Automated provisioning** — Bash scripts that spin up and reset lab machines to a known-good state.
- 🩺 **Self-healing touches** — boot-time fixes so a power loss doesn't leave the lab broken.

## Skills demonstrated

`RHEL 9` · `KVM/libvirt` · `networking & DNS` · `Podman` · `LVM & storage` · `systemd` · `SELinux` · `Bash scripting` · `firewalld`

## What I got out of it

A place to fail fast. Most of what I know about Linux troubleshooting came from something in this lab refusing to work at 1 a.m. — and me not being allowed to give up until it did.

---

<div align="center">

**Əliəsgər Fətullayev**
📫 eliesgerfetullayev@gmail.com

</div>
