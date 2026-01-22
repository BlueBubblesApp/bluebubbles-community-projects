# BlueBubbles Community Projects 🚀

Welcome to the official directory for community-led projects within the **BlueBubbles** ecosystem. This repository serves as a curated list of third-party applications, scripts, and tools that leverage the BlueBubbles Server API, Socket.IO streams, and our cross-platform architecture.

---

## 🛠 Project Categories

### 📱 Client Applications

Alternative interfaces or platform-specific clients built using Flutter, web technologies, or native frameworks.

| Project Name | Description | Author | Link |
| :--- | :--- | :--- | :--- |
| **BlueBubbles ChatGPT Agent** | A ChatGPT agent that integrates with BlueBubbles (iMessage) and optional Google Calendar + other tools. Built with Spring Boot + OpenAPI. | [@omega-bred](https://github.com/omega-bred) | [Repo](https://github.com/omega-bred/bluebubbles-chatgpt-agent/) |
| **Clawdbot** | Clawdbot is a personal AI assistant you run on your own devices. It answers you on the channels you already use (WhatsApp, Telegram, Slack, Discord, Signal, iMessage, Microsoft Teams, WebChat), plus extension channels like BlueBubbles, Matrix, Zalo, and Zalo Personal. It can speak and listen on macOS/iOS/Android, and can render a live Canvas you control. The Gateway is just the control plane — the product is the assistant. | [@clawdbot](https://github.com/clawdbot) | [Repo](https://github.com/clawdbot/clawdbot/) |
| **BlueBubbles MCP Server** | A Model Context Protocol (MCP) server that provides Claude Desktop with the ability to interact with a BlueBubbles instance for iMessage management. | [@jfiggins](https://github.com/jfiggins) | [Repo](https://github.com/jfiggins/bluebubbles-mcp-server/) |
| **BlueBubbles for HomeAssistant** | This integration allows you to send messages (iMessage/RCS/SMS/MMS) from Home Assistant using a BlueBubbles server. It connects to your BlueBubbles instance and exposes a service for sending messages. | [@jfiggins](https://github.com/helv-io) | [Repo](https://github.com/helv-io/ha-bluebubbles/) |

### ⚙️ Server Add-ons & Scripts

Tools that extend the functionality of the BlueBubbles Electron Server or interact with the Private API.

_N/A_

### 🎨 Themes & Customization

Custom CSS for the Web Client or JSON-based theme files for the Flutter Android/Desktop clients.

_N/A_

---

## 🏗 Developing for BlueBubbles

If you are looking to build your own project, please refer to our core technical documentation:

* **Server API:** The Electron server exposes a **REST API** (standard port 1234) and a **Socket.IO** connection for real-time events.
* **Data Models:** Familiarize yourself with our **ObjectBox** schema if you are contributing to the core Flutter client.
* **Security:** Ensure all third-party apps respect the sensitive nature of iMessage data and utilize our encrypted communication protocols.

---

## 📥 How to Submit

We welcome all contributions! To add your project to this list:

1.  **Fork** this repository.
2.  Add your project to the appropriate table in this `README.md`.
3.  Submit a **Pull Request**. 

*Note: Projects must be actively maintained and align with the security standards of the BlueBubbles Organization.*

---

## ⚖️ Disclaimer

These projects are developed by the community and are not officially maintained by the BlueBubbles Development Team. Use them at your own discretion.
