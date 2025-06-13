# cloudflared-multi-instance-setup

This repository contains a utility script to create multiple `cloudflared` systemd services on a single host using unique tokens.

## 🔧 Features

- Create multiple `cloudflared` services from a base service
- Automatically set unique tokens per service
- Automatically rename the binary and service
- Designed for advanced multi-tunnel configurations

## 🚀 Quick Usage (without cloning)

You can run the script directly from GitHub using:
https://github.com/14f3v/cloudflared-multi-instance-setup.git
```bash
bash <(curl -s https://raw.githubusercontent.com/14f3v/cloudflared-multi-instance-setup/main/sprint.sh) <service-name> <cloudflare-token>
```

