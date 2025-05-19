# minaki-shield
A modular Linux intrusion detection CLI tool for SSH brute-force and sudo abuse monitoring and more. Includes systemd integration.

# 🛡️ MinakiShield

MinakiShield is a lightweight, modular Linux intrusion detection CLI tool developed by [MinakiLabs](https://minakilabs.com). It monitors system logs for suspicious SSH brute-force attacks and sudo abuse attempts, and alerts administrators via Slack or other webhooks.

---

## 🚀 Features

- 🔍 Detects SSH brute-force attempts and sudo abuse
- 🧩 Plugin-based architecture for future extensions
- ⚙️ Systemd integration for persistent background monitoring
- 📢 Real-time alerts via Slack or any compatible webhook
- 🧼 CLI tool with commands for setup, status, restart, and uninstall

---

## 📦 Install MinakiShield

### Option 1: Install from `.deb` file

Download the latest `.deb` from the [Releases page](https://github.com/MinakiLabs-Official/minaki-shield/releases):

```bash
sudo dpkg -i minaki_1.1.3_all.deb
