---
name: 🐳 Bug Report
about: Report an issue with Docker images, containers, or orchestration
title: "[Docker Bug] "
labels: bug, docker
assignees: ''

---

## 🐛 Bug Description

A concise description of the issue—e.g., container not starting, image build failure, unexpected behavior.

---

## 📋 Steps to Reproduce

1. `docker build -t my-app .`
2. `docker run -p 3000:3000 my-app`
3. Observe error message or misbehavior

---

## ⚙️ Expected Behavior

Explain what you expected to happen (e.g., successful build, correct networking).

---

## 🐳 Docker Details

| Key              | Value                     |
|------------------|---------------------------|
| Docker Version    | e.g., 25.0.3              |
| OS / Distro       | e.g., Ubuntu 24.04 / Windows 11 |
| Base Image        | e.g., python:3.11-slim    |
| Host vs Container | e.g., Linux host / Linux container |
| Compose Used?     | Yes / No + version (if applicable) |
| Registry Source   | e.g., Docker Hub / GitHub Container Registry |

---

## 📸 Screenshots & Logs

Add terminal logs, Dockerfile excerpts, or screenshots from container runtime or monitoring tools.

---

## 🧠 Additional Context

Mention recent image/tag changes, volume mounts, network setups, build stages, or orchestration tools like KEDA, MCP, or Kubernetes (if relevant).
