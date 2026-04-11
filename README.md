<p align="center">
  <img src="https://httpeep.com/logo.svg" alt="HTTPeep Logo" width="120" height="120">
</p>

<h1 align="center">The Next-Gen HTTP/HTTPS Debugger & Programmable Proxy for Modern Developers.</h1>

<p align="center">
  <strong>The Composable HTTP Debugger Stack rules to mock, intercept, and rewrite traffic — combine any actions, reuse anywhere.</strong>
</p>

<p align="center">
  <a href="https://httpeep.com"><img src="https://img.shields.io/badge/Website-httpeep.com-0078D4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://github.com/HTTPeep/httpeep/releases"><img src="https://img.shields.io/github/v/release/HTTPeep/httpeep?style=for-the-badge&logo=github&color=2ea44f" alt="Version"></a>
  <img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey?style=for-the-badge&logo=apple&logoColor=black" alt="Platform">
  <a href="https://github.com/HTTPeep/httpeep/releases"><img src="https://img.shields.io/github/downloads/HTTPeep/httpeep/total?style=for-the-badge&logo=github&color=0078D4" alt="Downloads"></a>
  <a href="https://x.com/HTTPeep001"><img src="https://img.shields.io/badge/Follow-@HTTPeep001-000000?style=for-the-badge&logo=x&logoColor=white" alt="Follow on X"></a>
  <a href="https://discord.gg/hWS5X2Hyqj"><img src="https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
</p>

---

<p align="center">
  <img src="./screenshots/banner.png" alt="HTTPeep Main Interface" width="800">
</p>

<p align="center">
  <video controls width="250">
  <source src="https://s1.httpeep.com/video/demo.mp4" type="video/mp4" />
  </video>
</p>


## About HTTPeep

HTTPeep is a fast, reliable, and developer-friendly HTTP/HTTPS debugging proxy built from the ground up with Rust. It captures, inspects, and modifies network traffic with a clean, professional interface. Whether you are debugging complex APIs, setting up mock servers, or rewriting requests on the fly, HTTPeep provides a powerful, composable toolset to handle your web traffic effortlessly.

> **Note**: This repository is for **bug reports** and **feature requests** only. For product information, visit [httpeep.com](https://httpeep.com).

## 🚀 Download

| Platform | Download | Requirements |
|----------|----------|--------------|
| **macOS** | [Download for macOS](https://httpeep.com/download) | macOS 10.15+ |
| **Windows** | [Download for Windows](https://httpeep.com/download) | Windows 10+ |
| **Linux** | [Download for Linux](https://httpeep.com/download) | glibc 2.31+ |

## ✨ Core Features

### 🔍 Traffic Capture & Inspection
HTTPeep seamlessly captures HTTP/1.1, HTTP/2, and HTTPS (MITM) traffic. It automatically groups requests by TCP connection, visualizes HTTP timing, and provides multi-dimensional filtering to easily locate the requests you care about.

<p align="center">
  <img src="./screenshots/home.png" alt="Traffic Capture" width="800">
</p>

### 🛠️ Advanced Rule Engine Arch
The true power of HTTPeep lies in its composable rule engine. Match traffic by domain, path, headers, or method, and build an action pipeline to Map Local, Forward, Delay, or Reject. Create robust rules, combine multiple actions, and export them to share with your team.

<p align="center">
  <img src="./screenshots/arch.png" alt="Rule Engine" width="800">
</p>

### 📡 Built-in HTTP Client
Need to test an endpoint directly? Use the integrated HTTP client to manually construct requests, test APIs on the fly, and even import your cURL or Fetch commands instantly.

<p align="center">
  <img src="./screenshots/http-client.png" alt="HTTP Client" width="800">
</p>

### 🌗 Beautiful Native Themes
We care about aesthetics as much as performance. Choose between meticulously crafted light and dark themes that fit perfectly into your OS environment.

<p align="center">
  <img src="./screenshots/theme-dark.png" alt="Dark Theme" width="400">
  <img src="./screenshots/theme-light.png" alt="Light Theme" width="400">
</p>

### 🤖 AI-Native Integration
HTTPeep features a Built-in MCP Server designed for AI agents. It works flawlessly with tools like Claude, Cursor, GitHub Copilot, and includes a CLI for scripted operations and CI/CD integration.

### And More...
- **Breakpoint Debugging** — Set breakpoints to modify headers, body, and status code on the fly.
- **Certificate Management** — Built-in CA for fast, frictionless HTTPS interception.
- **Custom DNS** — Override DNS resolution on a per-domain basis.
- **Export Capabilities** — Save your sessions in JSON, HAR, or PCAP formats.

## 🛠️ How It Works

| Step | Action | Description |
|------|--------|-------------|
| 1 | **Install & Trust Certificate** | Install HTTPeep and trust the built-in root CA certificate |
| 2 | **Capture Traffic** | Start the proxy to capture HTTP/HTTPS traffic from your apps |
| 3 | **Configure Rules** | Set up matching rules, breakpoints, and forwarding |
| 4 | **Debug & Modify** | Inspect requests/responses, modify on the fly, and solve issues |

## 💬 Feedback & Support

We'd love to hear from you! Here's how to reach us:

- **Bug Reports** — [Open an issue](https://github.com/HTTPeep/httpeep/issues/new?template=bug_report.md)
- **Feature Requests** — [Open an issue](https://github.com/HTTPeep/httpeep/issues/new?template=feature_request.md)
- **Community** — [Join our Discord](https://discord.gg/hWS5X2Hyqj)
- **Email** — support@httpeep.com
- **Updates** — Follow [@nichenqin](https://x.com/@HTTPeep001) on X

## ❓ FAQ

<details>
<summary><strong>Is HTTPeep free?</strong></summary>

HTTPeep offers a free tier with core features. See [pricing](https://httpeep.com/pricing) for details on premium plans.
</details>

<details>
<summary><strong>Which platforms are supported?</strong></summary>

macOS 10.15+, Windows 10+, and Linux (glibc 2.31+).
</details>

<details>
<summary><strong>Where is my data stored?</strong></summary>

All data is stored locally on your machine at `~/.httpeep/`. Nothing is sent to external servers.
</details>

---

<p align="center">
  <a href="https://httpeep.com">httpeep.com</a>
</p>

<p align="center">
  Made with ❤️ by the HTTPeep Team
</p>
