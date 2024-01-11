<h1 align="center">
<img src='./doc/icon.png' width='30'>
<span>Chatbox</span>
</h1>
<p align="center">
    <em>Your Ultimate AI Copilot on the Desktop. <br />Chatbox is a desktop client for ChatGPT, Claude and other LLMs, available on Windows, Mac, Linux</em>
</p>


## 🌟 Features

-   Data is stored locally and will not be lost
-   Supports multiple cutting-edge LLM models and providers
    -   OpenAI (ChatGPT)
    -   Azure OpenAI
    -   Claude
    -   Google Gemini Pro
    -   Ollama (enabling easy access to locally deployed models such as llama2, Mistral, Mixtral, codellama, vicuna, yi, and solar)
    -   ChatGLM-6B
-   Supports Dall-E-3, real-time image generation
-   Enhanced prompting capability
-   Keyboard shortcuts for improved productivity
-   Markdown & Code Highlighting
-   Prompt Library, Message Quoting
-   Streaming reply
-   Ergonomic UI design & Night Mode
-   Suitable for team collaboration, supporting the sharing of OpenAI API resources within the team. View [tutorial](./team-sharing/README.md)
-   Providing installation packages, no deployment required
-   Cross-platform, available on Windows, Mac, Linux
-   Web version, available on any device with a browser
-   iOS & Android version, coming soon
-   Multilingual Support
    -   English
    -   Français
    -   Deutsch
    -   Русский
-   More...

## FAQ

-   [Frequently Asked Questions](./FAQ.md)

## Why I made Chatbox?

I developed Chatbox initially because I was debugging some prompts and found myself in need of a simple and easy-to-use prompt and API debugging tool. I thought there might be more people who needed such a tool, so I open-sourced it.

At first, I didn't know that it would be so popular. I listened to the feedback from the open-source community and continued to develop and improve it. Now, it has become a very useful AI desktop application. There are many users who love Chatbox, and they not only use it for developing and debugging prompts, but also for daily chatting, and even to do some more interesting things like using well-designed prompts to make AI play various professional roles to assist them in everyday work...

## Roadmap

-   [x] AI chat and session management
-   [x] Store all your important message data locally.
-   [x] Markdown
-   [x] Streaming reply
-   [x] API Host configuration
-   [x] Automatically generate tab titles
-   [x] Button for clearing messages.
-   [x] Night/Dark mode
-   [x] message token estimating
-   [x] GPT4
-   [x] i18n
-   [x] Copy button for code blocks
-   [x] Stop button for AI message generation
-   [x] Drag-and-drop sorting of tabs
-   [x] [Web version](https://web.chatboxai.app)
-   [x] Azure OpenAI API compatibility
-   [x] Improved prompt settings
-   [x] Prompt Library
-   [x] Built-in AI services
-   [x] Shortcut keys
-   [x] Claude
-   [x] Temperature Setting
-   [x] Conversation Special Settings
-   [x] OpenAI Custom Model
-   [x] Dall-E-3
-   [x] Message Search
-   [x] Data Export
-   [x] Support for Google Gemini Pro
-   [x] Support for Ollama (llama2, Mistral, Mixtral, codellama, vicuna, yi, and solar)
-   [x] Thread archive, history message list
-   [x] Mobile (Android, iOS)
-   [ ] Talk with files
-   [ ] Talk with URLs
-   [ ] Cross-device synchronization
-   More...

## How to Contribute

Any form of contribution is welcome, including but not limited to:

-   Submitting issues
-   Submitting pull requests
-   Submitting feature requests
-   Submitting bug reports
-   Submitting documentation revisions
-   Submitting translations
-   Submitting any other forms of contribution

## Build Instructions for Chatboxai (Mac, Windows, Linux)

1. Clone the repository from Github using the following command:

```bash
git clone https://github.com/ccorte20/React-Tauri-Chatbox-OpenAI.git
```

2. Install the required dependencies by running the following command:

```bash
npm install
```

3. Start the application by running the following command:

```bash
npm start
```