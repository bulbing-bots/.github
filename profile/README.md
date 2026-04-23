<table>
<tr>
<td>
<h1>Bulbing Bots</h1>

LLM Agent Framework and tool

---

- commands, batches
- tools, skills
- multi agents
- sub agents
- voice agents
- agent collaboration
- sessions
- memory
- plugins

</td>
<td>
<img src="assets/agent-5.jfif" alt="Auto Agents" width="800px">

*agent **TUI** - helpful & sympathic assistant*

</td>
</tr>
</table>

<!---------------------------------------------------------------------->
<!---------------------------------------------------------------------->
<!---------------------------------------------------------------------->

---

## 🤖 multi purpose AI assistant



<!---------------------------------------------------------------------->
<!---------------------------------------------------------------------->
<!---------------------------------------------------------------------->

<table>
<tr>
<td colspan="2">

### Repositories:

</td>
</tr>



<tr>
<td>

<a href="https://github.com/auto-agents/cli"><b><h4>&bull; cli</h4></b></a>

This repository contains the **CLI** and **TUI** tool</b>
</td>
<td>
<img src="assets/tui.png" alt="state diagram" width="1200px">
</td>
</tr>

<tr>
<td colspan="2">

<a href="https://github.com/auto-agents/plugins"><b><h4>&bull; plugins</h4></b></a>

This repository contains **software plugins** for **cli tool**, that allows to add new features and capabilities to the **CLI** and to any **agent** : :
- plugin 
- commands
- tools
- skills

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

- [Hugging Face](https://github.com/auto-agents/plugins/blob/main/src/API/hugging-face/exports/) : access to **hugging face API**, get model cards and allow to search the huge hugging face dabatabase for detailed informations about **models**

##### WEB

- [Puppeteer](https://github.com/auto-agents/plugins/tree/main/src/WEB/puppeteer-browser/exports) : the browser chromium/firefox commander plugin, that allows to control a browser and use it as a tool & skill for agents. It includes the following features :
    - google search
    - page scraper

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

This repository contains the core framework librairies & components shared accross the projects</b>

</td>
</tr>

</table>
