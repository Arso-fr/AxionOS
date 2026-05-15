# AxionOS

<div align="center">

![AxionOS Logo](./assets/logo.png)

### A modern immutable Linux distribution powered by Fedora Atomic, BlueBuild and OCI containers.

[![Build Status](https://github.com/arso-fr/axionos/actions/workflows/build.yml/badge.svg)](https://github.com/arso-fr/axionos/actions/workflows/build.yml)
[![License](https://img.shields.io/github/license/arso-fr/axionos)](LICENSE)
[![Fedora](https://img.shields.io/badge/Fedora-Atomic-blue)](https://fedoraproject.org/atomic-desktops/)
[![BlueBuild](https://img.shields.io/badge/Built%20With-BlueBuild-53a7ff)](https://blue-build.org)

</div>

---

# ✨ About

AxionOS is a custom immutable Linux distribution based on Fedora Atomic technologies and built using BlueBuild.

It focuses on:

- ⚡ Fast and reproducible deployments
- 🔒 Immutable and reliable system updates
- 📦 OCI container-native workflows
- 🧱 Atomic upgrades and rollbacks
- 🎨 Custom branding and desktop experience
- 🚀 Modern Linux development workflow

AxionOS is distributed as:
- OCI container images
- bootable ISOs
- signed system images

---

# 🧱 Technologies

AxionOS is powered by:

- Fedora Atomic
- rpm-ostree
- BlueBuild
- bootc
- OCI containers
- GitHub Actions
- Sigstore / Cosign

---

# 📦 Installation

> [!WARNING]
> AxionOS is currently experimental.
> Use at your own discretion.

## Rebase an existing Fedora Atomic installation

### 1. Rebase to the unsigned image

```bash
rpm-ostree rebase ostree-unverified-registry:ghcr.io/arso-fr/axionos:latest
