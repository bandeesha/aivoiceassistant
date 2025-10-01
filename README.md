
<p align="center"><h1 align="center">AI VOICE ASSISTANT</h1></p>

##  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Project Structure](#-project-structure)
- [ Getting Started](#-getting-started)
  - [ Prerequisites](#-prerequisites)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
- [ Acknowledgments](#-acknowledgments)

---

##  Overview

<code>Built an AI-powered voice assistant with custom wake word detection, real-time speech-to-text, natural language processing, and smart home integration, deployed on Raspberry Pi for offline voice interaction and automated device control.</code>

---

##  Features

<code>-Custom Wake Word Detection – Always-listening assistant with personalized activation phrase.
-Real-Time Speech-to-Text – Accurate and low-latency voice transcription.
-Natural Language Processing (NLP) – Intelligent command understanding and response generation.
-Text-to-Speech Synthesis – Converts responses into natural, human-like speech.
-Smart Home Integration – Control IoT and appliances through voice commands.
-Raspberry Pi Deployment – Lightweight and fully functional on edge devices.
-Offline Functionality – Voice interaction without constant internet dependency.</code>

---

##  Project Structure

```sh
└── aivoiceassistant/
    ├── README.md
    └── ai_voice_assistant
```
##  Getting Started

###  Prerequisites

Before getting started with aivoiceassistant, ensure your runtime environment meets the following requirements:
-Programming Language: Python 3.8+,<br>
-Required Libraries:<br>
-speechrecognition – for speech-to-text conversion<br>
-pyttsx3 – for offline text-to-speech synthesis<br>
-requests – for making API calls (e.g., weather, news, etc.)<br>
-Pillow – for taking screenshots (ImageGrab)<br>
-psutil – for system monitoring (CPU, memory, battery, etc.)<br>
-Standard Libraries Used (no extra install needed):<br>
-json, time, datetime, os, subprocess, platform, socket, re, random, threading, urllib.parse,    webbrowser<br>
-Hardware Requirements:<br>
-Microphone & speakers (for voice input/output)<br>
-Raspberry Pi for deployment with smart home integrations<br>


###  Installation

Install aivoiceassistant using one of the following methods:

**Build from source:**

1. Clone the aivoiceassistant repository:
```sh
❯ git clone https://github.com/bandeesha/aivoiceassistant
```

2. Navigate to the project directory:
```sh
❯ cd aivoiceassistant
```

3. Install the project dependencies:
```sh
❯ pip install SpeechRecognition pyttsx3 requests pillow psutil

```


###  Usage
Run aivoiceassistant using the following command:
```sh
python3 ai_voice_assistant.py
```

##  Contributing

- **💬 [Join the Discussions](https://github.com/bandeesha/aivoiceassistant/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/bandeesha/aivoiceassistant/issues)**: Submit bugs found or log feature requests for the `aivoiceassistant` project.
- **💡 [Submit Pull Requests](https://github.com/bandeesha/aivoiceassistant/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/bandeesha/aivoiceassistant
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/bandeesha/aivoiceassistant/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=bandeesha/aivoiceassistant">
   </a>
</p>
</details>

---

##  Acknowledgments

I would like to express my gratitude to the open-source community and the developers of the following tools and libraries that made this project possible:<br>
-SpeechRecognition<br>
 for robust speech-to-text conversion.<br>
-pyttsx3<br>
 for enabling offline text-to-speech synthesis.<br>
-Requests<br>
 for simplifying API and web interactions.<br>
-Pillow<br>
 for providing image processing capabilities.<br>
-psutil<br>
 for system monitoring and resource management.<br>
The Python open-source ecosystem for built-in libraries that power much of the assistant’s functionality.<br>
Raspberry Pi community for continuous innovation in edge AI and IoT applications.<br>

---
