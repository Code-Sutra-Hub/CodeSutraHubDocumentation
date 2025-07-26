**HPanelToolBox** is a modular, customizable Houdini panel built with PySide2. It offers reusable group boxes that streamline artist workflows by integrating template loading, tool execution, and more custom UI utilities into a single panel.

Designed for flexibility and future upgrades, this panel can be extended with new group boxes as per project needs.

---

## ✨ Key Features

- 🧠 **Template Loaders**
    - **Auto-Generated Names** – Reads template files and generates dropdowns.
    - **JSON-Based Loader** – Loads versioned templates from a configuration file.
- 📦 **Modular Architecture** – Each tool group is isolated and independently reusable, also we can more groupboxes with more tools.
- ⚙️ **Developer-Ready** – Clean PySide2 architecture, extendable with minimal changes.
- 🧰 **Custom Tool Buttons** – Easily add helper or project-specific scripts.
- 🖼️ **Houdini Panel Ready** – Designed to be dropped into a Python Panel tab.

---

## 📸 Screenshots / Video links

![alt text](resources/hpanel_toolbox_01.jpg)

![alt text](resources/hpanel_toolbox_02.jpg)

**Video Demonstration**

---

## 📦 Installation

1. Houdini Packages Setup
    - Replace DIR_PATH key-value `path/to/source/folder` with current path of this repo in explorer inside `HPanelToolBox_tool.json` file.
    - Copy the `HPanelToolBox_tool.json` package file inside the same houdini's `packages/` directory.:
      - On Windows:  
        `C:/Users/<YourName>/Documents/houdiniXX.X/packages/`
      - On Linux:
        `/home/<YourName>/houdiniXX.X/packages/`
2. Launch the Tool
    - Launch Houdini
    - Go to `Windows` → `Python Panel`
    - Click on `Houdini ToolBox`
    - If all goes well it will show you the panel.

---

## 🖥️ Default Included Modules

- `TemplateLoaderA`: Auto-generates template names from a directory.
- `TemplateLoaderB`: Loads structured templates via a JSON file.

---

**Portfolio link** - https://github.com/thecodeshastra

### Note this is just for technical documentation presentation, **NOT FOR SALE**
