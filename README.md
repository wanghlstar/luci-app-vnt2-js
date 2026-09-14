
# LuCI - VNT2 Networking Management Interface [VNT/VNTS Setup Guide](Image/en_README.md)

> **Language:** [中文](CN_README.md) | English


> luci-app-vnt2 – A frontend for managing VNT virtual networking on OpenWrt LuCI, supporting multi-instance concurrency, real-time monitoring, one‑click updates, and automatic firewall passthrough.

![Homepage dark](<Image/en/Homepage dark.jpeg>)
![Home page white](<Image/en/Home page white.jpeg>)

# [More screenshots](Image/en/README.md)

## ✨ Key Features

### 🔥 Multi-Instance Operation
Run multiple VNT client and server instances simultaneously. Each instance is independently configured, started, and stopped – easily join several virtual networks or provide multiple server endpoints at the same time.

### 📊 Status Dashboard
View real-time runtime status, CPU/memory usage, uptime, and version information for each instance.

### ⚙️ Client Configuration
Graphically configure client parameters: Token, IP, MTU, port mapping, STUN servers, etc.


### 🖥️ Server Configuration
Configure server listening port, virtual subnet, whitelist, WebUI credentials, etc.


### 🌐 Global Settings
Select update mirror source (GitHub / GitLab / Gitee), auto‑update policy, UPX compression, etc.

### 📦 Online Update
One‑click check and download of the latest binary, then automatically install and restart the service.


### 📜 Log Viewer
View real‑time operation logs for each instance, with support for log clearing.


### 📜 VNT2 Web UI
View real‑time status, create configurations, etc.

### 🔒 Automatic Firewall Configuration
Automatically open required ports for each instance and create independent firewall zones – no manual intervention needed.

### 🚀 Quick Start

1. Log into OpenWrt → **VPN** → **VNT**
2. Create multiple configuration profiles (client/server) and enable them as needed
3. Each instance starts independently without affecting others

### 📥 Installation Instructions

## Run the following command in the terminal to download and install:

```bash
curl -fsSL "https://gitlab.com/whzhni/tailscale/-/raw/main/Auto_Install_Script.sh" | sh -s luci-app-vnt2
```

## Or:

```bash
wget -q -O - "https://gitlab.com/whzhni/tailscale/-/raw/main/Auto_Install_Script.sh" | sh -s luci-app-vnt2
```
```
