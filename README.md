# containers

A collection of Docker Compose configurations for the services I run locally or on my home lab.  
Each service lives in its own folder with its own `docker-compose.yml` file and environment configuration.

- [containers](#containers)
  - [🧩 Overview](#-overview)
  - [⚙️ Usage](#️-usage)
    - [1. Clone the repository](#1-clone-the-repository)
  - [Support](#support)

## 🧩 Overview

This repository centralizes all my Docker Compose setups — databases, utilities, and self-hosted services — in one place.  
Each stack is self-contained, portable, and version-controlled.

Each directory typically contains:

- `docker-compose.yml`
- `.env.example` (for configuration templates)
- Optional `README.md` (for service-specific notes)

---

## ⚙️ Usage

### 1. Clone the repository

```sh
git clone https://github.com/<your-username>/containers.git ~/containers
cd ~/containers
```

## ❓ Support

Please [contact Dave Gulati](https://davegulati.com/contact) for support.
