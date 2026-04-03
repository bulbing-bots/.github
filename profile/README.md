<table>
<tr>
<td>
<h1>Auto Agents</h1>

*&gt; software agents & agents workflows orchestrator.*

***Made by AI for AI. Includes AI Agent***

---

</td>
<td>
<img src="assets/agent-5.jfif" alt="Auto Agents" width="800px">
</td>
</tr>
</table>

<!---------------------------------------------------------------------->
<!---------------------------------------------------------------------->
<!---------------------------------------------------------------------->

---

## 🤖 AI-Powered Software Agent Generator

Build, generate, and run **intelligent software agents** with a clear, production-ready architecture.

This project introduces a **unified model for AI-generated software agents**, designed to turn high-level specifications into fully functional, autonomous code. At its core, the `agent-model.md` file acts as both a **formal agent definition** and the **primary prompt** used by AI to generate consistent, reliable agent implementations.

### 🧠 From Idea to Autonomous Agent

Instead of handcrafted, one-off scripts, this project lets you define **what an agent is and how it behaves**, then automatically generate agents that:

* run autonomously or under human control
* follow a standardized lifecycle (start, pause, resume, stop)
* log every action with timestamps and severity levels
* track performance and execution time
* expose clear execution states and errors
* operate in fully isolated processes

Every agent execution is reproducible, auditable, and traceable.

### ⚙️ Built for Orchestration and Scale

The architecture is designed for **modern automation and orchestration workflows**:

* Node.js runtime with isolated agent processes
* IPC-based command and control
* One-run-per-process model with unique UUIDs
* Clean separation of input, output, configuration, logs, and metrics

Agents are easy to compose, monitor, restart, or integrate into larger pipelines.

### 🌍 International-Ready by Design

All logs and messages are **fully translatable**, with language selection handled dynamically via configuration or environment variables.
This makes the platform ideal for **enterprise, multi-region, and multi-language environments**.

### 🚀 Why This Project?

Because AI agents should be:

* **Predictable**, not opaque
* **Reusable**, not disposable
* **Observable**, not silent
* **Generated**, not handcrafted

This project provides a **solid foundation for AI-driven agent generation**, enabling you to create agents that process files, automate workflows, collaborate with other agents, and scale within orchestrated systems.

<!---------------------------------------------------------------------->
<!---------------------------------------------------------------------->
<!---------------------------------------------------------------------->

<table>
<tr>
<td colspan="2">

### This project includes these repositories:

</td>
</tr>

<tr>
<td>

<a href="https://github.com/auto-agents/agents"><b><h4>&bull; agents</h4></b></a>

This repository contains:
<ul>
<li>the base agent and commons <b>software agents</b> implementations</li>
<li>the <b>AI materials</b> that are used to generate the softwares (defining how agents are specified, generated, executed, and managed)</li>
</ul>
</td>
<td>
<p align="center">
<img src="assets/state-diagram.png" alt="state diagram" width="800px">
</p>
</td>
</tr>

<tr>
<td>

<a href="https://github.com/auto-agents/cli"><b><h4>&bull; cli</h4></b></a>

This repository contains the <b>Auto Agents CLI & TUI tool</b>
</td>
<td>
<img src="assets/tui.png" alt="state diagram" width="1200px">
</td>
</tr>

<tr>
<td colspan="2">

<a href="https://github.com/auto-agents/plugins"><b><h4>&bull; plugins</h4></b></a>

This repository contains **software plugins** for **cli tool**, that allows to add new features and capabilities to the **CLI** and to any **software agent** :

##### TTS

- [tts-browser](https://github.com/auto-agents/plugins/blob/main/speech) : **Text To Speech** with any browser implementing `WebSpeechAPI`
- [tts-webui](https://github.com/auto-agents/plugins/blob/main/src/TTS/tts-webui) : supports **Text To Speech** from softwares that can be installed in **`TTS WebUI`** [https://github.com/rsxdalv/TTS-WebUI](https://github.com/rsxdalv/TTS-WebUI), throught the **Gradio** API. Currently the following TTS providers are available in *auto-agents* :
    - **Kokoro TTS**
    - **Kitten TTS**
    - **OpenVoice V1**
    - **OpenVoice V2**
    - **ChatterBox**
    - **XTTS**
  
##### STT

- voice recognition : *Speak To Text* with any browser implementing `WebSpeechAPI` *(coming soon)*

##### API

- [Hugging Face](https://github.com/auto-agents/plugins/blob/main/hugging-face) : access to **hugging face API**, get model cards and allow to search the huge hugging face dabatabse for detailed informations about **models**

</td>
</tr>

<tr>
<td colspan="2">

<a href="https://github.com/auto-agents/instruct"><b><h4>&bull; instruct</h4></b></a>

This repository contains various **AI instructions** for both **agents** and the **cli tool**:

- `prompts`
- `system instructions`
- `cli batches`
- `skills`

</td>
</tr>

<tr>
<td colspan="2">

<a href="https://github.com/auto-agents/shared"><b><h4>&bull; shared</h4></b></a>

This repository contains librairies & components shared accross <b>auto-agents projects</b>

</td>
</tr>

</table>
