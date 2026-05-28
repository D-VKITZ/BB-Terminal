<div align="center">

# 💻 BB-Terminal

### Browser-Based Terminal · WebShell · DkZ CLI · Agent Interface

*Vollständiges Terminal-Interface im Browser — Dark Neon Theme, Command History, Scriptable, Agent-Kommunikation*

---

![Version](https://img.shields.io/badge/Version-1.0-fa1e4e?style=for-the-badge&logo=semver&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-00ff88?style=for-the-badge&logo=statuspage&logoColor=white)
![Terminal](https://img.shields.io/badge/Terminal-Browser-6366f1?style=for-the-badge&logo=windowsterminal&logoColor=white)
![Commands](https://img.shields.io/badge/Commands-25+-ffb800?style=for-the-badge&logo=code&logoColor=black)
![Lizenz](https://img.shields.io/badge/Lizenz-MIT-3b82f6?style=for-the-badge&logo=opensourceinitiative&logoColor=white)

![HTML5](https://img.shields.io/badge/HTML5-Semantic-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Neon_Dark-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![JetBrains Mono](https://img.shields.io/badge/Font-JetBrains_Mono-fa1e4e?style=for-the-badge&logo=jetbrains&logoColor=white)

![Keyboard](https://img.shields.io/badge/Shortcuts-Active-00ff88?style=for-the-badge&logo=keyboard&logoColor=white)
![History](https://img.shields.io/badge/History-localStorage-ffb800?style=for-the-badge&logo=clockify&logoColor=black)
![Scriptable](https://img.shields.io/badge/Scriptable-API-6366f1?style=for-the-badge&logo=code&logoColor=white)
![Agents](https://img.shields.io/badge/Agent-Bridge-fa1e4e?style=for-the-badge&logo=robot&logoColor=white)
![XSS](https://img.shields.io/badge/XSS-Protected-00ff88?style=for-the-badge&logo=shield&logoColor=white)
![Made with](https://img.shields.io/badge/Made_with-DEVKiTZ™-fa1e4e?style=for-the-badge&logo=heart&logoColor=white)

</div>

---

## 📖 Überblick

**BB-Terminal** ist ein voll funktionsfähiges Browser-Terminal mit DEVKiTZ™ Branding. Dunkles Neon-Theme, Command History, Auto-Completion, Keyboard Shortcuts und direkte Agent-Kommunikation über die NanoChat Bridge.

> **Verwendung:** Quick-Access zu DkZ-Commands, Debugging, System-Status, Agent-Kommunikation und Health Checks — alles direkt im Browser.

---

## 🏛️ Architektur

```mermaid
graph LR
    subgraph TERMINAL["💻 BB-Terminal"]
        IN["⌨️ Input<br/>Command Parser"]
        HI["📜 History<br/>localStorage"]
        AC["💡 Autocomplete<br/>Tab-Completion"]
    end

    subgraph ENGINE["⚙️ Command Engine"]
        CM["📋 Commands<br/>25+ Built-in"]
        PL["🔌 Plugins<br/>Erweiterbar"]
        FO["📤 Output<br/>Formatted"]
    end

    subgraph EXTERNAL["🌐 External"]
        NC["🤖 NanoChat<br/>Agent Bridge"]
        GH["📡 GitHub<br/>API"]
        HC["🏥 Health<br/>Check"]
    end

    IN --> CM
    HI -.-> IN
    AC -.-> IN
    CM --> PL --> FO
    CM --> NC & GH & HC

    style TERMINAL fill:#060608,stroke:#fa1e4e,stroke-width:3px,color:#fff
    style ENGINE fill:#060608,stroke:#3b82f6,stroke-width:2px,color:#fff
    style EXTERNAL fill:#060608,stroke:#00ff88,stroke-width:2px,color:#fff
```

---

## ⌨️ Commands

### System

| Command | Beschreibung | Beispiel |
|:--------|:-------------|:--------|
| `:help` | Alle Commands auflisten | `:help` |
| `:status` | System-Status anzeigen | `:status` |
| `:health` | Health-Check ausführen | `:health` |
| `:clear` | Terminal leeren | `:clear` / `Ctrl+L` |
| `:version` | Version + Build Info | `:version` |

### Module

| Command | Beschreibung | Beispiel |
|:--------|:-------------|:--------|
| `:modules` | Alle 132+ Module auflisten | `:modules` |
| `:open [name]` | Modul im Browser öffnen | `:open vibe-gallery` |
| `:search [query]` | Module durchsuchen | `:search blog` |
| `:features` | features.json anzeigen | `:features` |

### Agents

| Command | Beschreibung | Beispiel |
|:--------|:-------------|:--------|
| `:agents` | Agent Fleet Status | `:agents` |
| `:msg [agent] [text]` | Nachricht an Agent | `:msg antigravity status` |
| `:rednote` | Letzte Fehler anzeigen | `:rednote` |
| `:logs [n]` | Letzte n Log-Einträge | `:logs 20` |

### Git

| Command | Beschreibung | Beispiel |
|:--------|:-------------|:--------|
| `:git status` | Git Status | `:git status` |
| `:git log [n]` | Letzte n Commits | `:git log 5` |
| `:projects` | GitHub Projects auflisten | `:projects` |

---

## ⌨️ Shortcuts

| Tastenkürzel | Aktion |
|:-------------|:-------|
| `↑` / `↓` | Command History navigieren |
| `Tab` | Auto-Completion |
| `Ctrl+L` | Terminal leeren |
| `Ctrl+C` | Aktuellen Befehl abbrechen |
| `Escape` | Input leeren |

---

## 🔗 Ökosystem-Links

| Resource | Link |
|:---------|:-----|
| 🏠 **Dashboard** | [D-VKITZ.github.io](https://github.com/D-VKITZ/D-VKITZ.github.io) |
| 🤖 **BMAD™** | [bmad-framework](https://github.com/D-VKITZ/bmad-framework) |
| 🤖 **Agent Swarm™** | [agent-swarm](https://github.com/D-VKITZ/agent-swarm) |
| ⚙️ **KERN** | [KERN](https://github.com/D-VKITZ/KERN) |

---

<div align="center">

*Teil des [DEVKiTZ™](https://github.com/D-VKITZ) Ökosystems · Made with ❤️ by 777*

</div>