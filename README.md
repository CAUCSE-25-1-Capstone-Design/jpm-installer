

# JPM (Java Project Manager with AI)

**JPM** is an AI-powered desktop application that allows you to manage Java project packages and control build processes using **natural language**, eliminating the need for complex CLI commands or manual configuration file edits.

Simply issue commands like "Install JUnit" or "Run this project" in a chat-like interface, and the built-in GPT engine will interpret your intent and automate the execution.

<img width="500" height="490" alt="image" src="https://github.com/user-attachments/assets/53edfb03-778c-4308-8cde-be2e3502cc0b" />


## ✨ Key Features

* **💬 AI-Powered Natural Language Processing**: Utilizes GPT models to accurately interpret user intent.
* **📦 Smart Package Management**:
* **Install**: Automatically searches Maven Central to identify the correct `groupId` and `artifactId` for installation.
* **Update/Remove**: Analyzes libraries currently installed in the project to manage them safely.


* **⚙️ Project Control**: Executes tasks such as **Build**, **Test**, **Run**, and **Init** via commands.
* **🖥️ Intuitive UI**: Provides a clean, JavaFX-based chat interface with real-time progress indicators.
* **📝 Log & Config Management**: Features automatic execution log saving and secure API Key management.

## 🛠️ Tech Stack

This project is built on a hybrid architecture of **Java** and **Python**.

* **Frontend (UI)**: JavaFX (Java 14+)
* **NLP Engine**: Python 3.x, OpenAI API, PyInstaller
* **Core Logic**: Java (Project Management Logic)
* **Packaging**: `jpackage` (Native Image Bundle)

## 🚀 Installation

### System Requirements

* **OS**: macOS 11+ (Intel/Apple Silicon) or Windows 10/11
* **Prerequisite**: OpenAI API Key (Valid key required)

### Download & Install

1. Download the installer for your operating system (`.dmg` or `.exe`) from the [Releases](https://github.com/CAUCSE-25-1-Capstone-Design/jpm-installer/releases/tag/JPM) page.
2. Run the installer to install the application.
3. **(For macOS)** Drag the app to the `Applications` folder. If you encounter a security warning, please run the following command in your terminal:
```bash
xattr -cr /Applications/JPM.app

```



### Getting Started

1. Launch **JPM**.
2. Click the **Settings (⚙️) button** at the bottom left.
3. Enter your OpenAI API Key in the **API Key Settings** tab and click `Apply`.
* *Your key is securely encrypted and stored locally.*



## 💡 Usage

Try entering commands in the chat window like this:

* **Install Package**: `"Install Gson library"`
* **Remove Package**: `"I want to delete Log4j"`
* **Run Project**: `"Build and run the project now"`
* **Check Info**: `"Show me the list of installed packages"`

---

**Contact**: dhkimm@snu.ac.kr
