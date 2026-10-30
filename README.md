# Isai – Sovereign Personal AI Agent Framework

```
╭─────────────────────────────────────────────────────────────────────────────╮
│                                    💧                                       │
│                                  . : : .                                    │
│                                :       :                                   │
│                               :   (இ)   :                                  │
│                                :       :                                   │
│                                  ' - '                                     │
│            ___   ____     _       ___      _     ____  _____ _   _ _____     │
│           |_ _| / ___|   / \     |_ _|    / \   / ___|| ____| \ | |_   _|    │
│            | |  \___ \  / _ \     | |    / _ \ | |  _ |  _| |  \| | | |      │
│            | |   ___) |/ ___ \    | |   / ___ \| |_| || |___| |\  | | |      │
│           |___| |____//_/   \_\  |___| /_/   \_\\____||_____|_| \_| |_|      │
│                                                                             │
│                   S O V E R E I G N   A G E N T   F R A M E W O R K         │
│         Autonomous Orchestration · Nebius AI Cloud · NVIDIA Nemotron-3       │
╰─────────────────────────────────────────────────────────────────────────────╯
```

**Isai** (இ) is a sovereign personal AI agent framework designed for high-performance autonomous execution, private edge computing, and hybrid cloud inference. Built with deep architectural minimalism, Isai pairs the speed and intelligence of the **Nebius Token Factory** (**NVIDIA Nemotron-3 Nano**) with a localized **Sovereign Edge Fallback** engine.

---

## ⚡ Key Highlights

- **Sovereign Interactive Terminal**: An ultra-responsive command-line interface featuring TrueColor golden amber accents, clear glassmorphism-inspired ASCII borders, and streaming token output.
- **Autonomous Tool Router**: Automatic intent detection with zero-latency dispatch to integrated tools:
  - 🌐 `web_search`: Live sovereign web retrieval via DuckDuckGo with edge knowledge synthesis fallback.
  - 🧮 `calculate`: Safe AST-based mathematical evaluation.
  - 📊 `system_telemetry`: Real-time node diagnostics, OS details, and runtime metrics.
  - 🎨 `style_expansion`: Dynamic sensory and analytical prompt expansions.
- **Dynamic Style Pipeline**: Seamlessly transform prompts into specialized modalities:
  - `sovereign`: First-principles sovereign analysis, formal precision, and deterministic execution vectors.
  - `cinematic`: Arri Alexa LF 35mm anamorphic glass, subtle halation, and dramatic chiaroscuro.
  - `anime`: Makoto Shinkai aesthetic, luminous skies, and painterly celestial atmospheres.
  - `comic`: Bold black Indian ink linework, vintage halftone Ben-Day dots, and Kirby crackle.
  - `technical`: Low-level systems architecture, throughput optimization, and zero-copy pipelines.
- **Hybrid Inference Architecture**:
  - Primary: High-throughput token dispatch via **Nebius AI Cloud** (`api.tokenfactory.nebius.com/v1`) using `nvidia/nemotron-3-nano-30b`.
  - Fallback: Localized **Sovereign Edge Execution** guaranteeing complete privacy and uninterrupted uptime even when offline.

---

## 🚀 Quickstart

### 1. Installation

Clone the repository and set up a Python virtual environment:

```bash
git clone https://github.com/arulselvan2007/Isai.git
cd Isai

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### 2. Configure Nebius Token Factory (Optional)

To enable live inference through Nebius AI Cloud:

```bash
export NEBIUS_API_KEY="your-nebius-token-factory-key"
# Optional overrides:
export NEBIUS_BASE_URL="https://api.tokenfactory.nebius.com/v1"
export NEBIUS_MODEL="nvidia/nemotron-3-nano-30b"
```

*Note: If no API key is provided, Isai automatically switches to the Sovereign Edge Fallback Engine.*

### 3. Launch the Interactive Agent

Start the sovereign conversational session in your terminal:

```bash
python orchestrator.py
```

### 4. Single-Shot CLI Execution

You can also route one-off prompts and automated scripts directly through the orchestrator:

```bash
python orchestrator.py "Orchestrate dynamic style expansion and execute search tool."
```

---

## 🛠️ Slash Commands

Within the interactive terminal session, the following sovereign commands are available:

| Command | Description |
| :--- | :--- |
| `/style [name]` | View available styles or switch active dynamic style profile (`sovereign`, `cinematic`, `anime`, `comic`, `technical`). |
| `/tools` | Inspect registered autonomous tools and capabilities. |
| `/status` | View real-time node telemetry, OS specifications, and session memory turns. |
| `/model` | Inspect the active inference gateway and model identifiers. |
| `/clear` | Clear conversation memory and reset context. |
| `/help` | Display the interactive command reference. |
| `/exit`, `/quit` | Conclude the sovereign session gracefully. |

---

## 🏛️ Architecture Overview

```
                      ┌────────────────────────┐
                      │    User Input / CLI    │
                      └───────────┬────────────┘
                                  │
                                  ▼
                      ┌────────────────────────┐
                      │     Isai Router        │
                      └─────┬────────────┬─────┘
                            │            │
         ┌──────────────────▼─┐        ┌─▼──────────────────┐
         │ Dynamic Style Pipe │        │  Autonomous Tools  │
         │ (Cinematic, Anime, │        │ (Web Search, Math, │
         │   Sovereign Logic) │        │     Telemetry)     │
         └──────────────────┬─┘        └─┬──────────────────┘
                            │            │
                            └─────┬──────┘
                                  ▼
                      ┌────────────────────────┐
                      │  Inference Gateway     │
                      └─────┬────────────┬─────┘
           [Key Available]  │            │  [Mock / Offline]
                            ▼            ▼
             ┌────────────────┐        ┌────────────────┐
             │ Nebius Cloud   │        │ Sovereign Edge │
             │ NVIDIA Nemotron│        │ Fallback Core  │
             └────────────────┘        └────────────────┘
```

---

## 🔒 Sovereignty & Privacy

Isai is built from the ground up to respect data sovereignty. When running in sovereign edge mode, zero prompt data or telemetry leaves your local environment.

---

## 📄 License

MIT License. Sovereign Personal AI Agent Framework.
