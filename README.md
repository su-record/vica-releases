# Vica

Vica is a desktop coding agent. Ask it to work on a project, follow its progress, and inspect file changes and results. Connect a provider API, a supported subscription login, or a model running on your computer.

[English](https://torylabs.dev/vica) · [한국어](https://torylabs.dev/ko/vica) · [日本語](https://torylabs.dev/ja/vica)

## Download and install

| Platform | Current release | Install |
| --- | --- | --- |
| macOS · Apple Silicon | [0.1.9](https://github.com/su-record/vica-releases/releases/tag/v0.1.9) | Download `Vica_0.1.9_aarch64.dmg` and move Vica to Applications. The app is Apple signed and notarized. |
| Windows · x64 beta | [0.1.7 MSI](https://github.com/su-record/vica-releases/releases/download/v0.1.7/Vica_0.1.7_x64_ko-KR.msi) | Run the MSI on Windows 10 1809 or later. The installer is not code signed. It downloads WebView2 if needed. |

The Windows beta may differ from the latest Mac version. Installed apps check for updates through their platform's update channel. There is no public Linux installer in this repository.

## Start a project

1. Open Vica and choose a project folder.
2. Open **Settings → Agents** and connect an API key, a supported subscription login, or a local model. A provider CLI is needed for its CLI connection or specific tools; API keys and local models can be used without it.
3. Choose a connected model in chat and describe the work. Select the permission mode that determines when Vica asks before edits and commands.
4. Follow progress, inspect changed files and check results. You can stop a running task or answer questions from Vica.

The optional **vica-laya** decision model is available under **Settings → Agents → Vica built-in**. It is not required to install the app or connect another model.

Vica is free and does not require a Vica account. API and subscription charges follow each provider's pricing and terms. Local models use your computer's resources.

## What you can do

- Read and edit project files, run commands, and inspect execution records.
- Compare answers in a brainstorm or save a cowork with steps and models.
- Keep conversations, terminals, files and project groups in one window.
- Choose from 14 screen themes in the latest Mac release.
- Connect LG EXAONE's K-EXAONE 2.5 API for text and tool calls on Mac 0.1.9. Image input is not supported.
- Connect a phone or tablet through an encrypted relay while Vica runs on your computer. See the [remote access guide](https://torylabs.dev/relay). Device permissions and setup affect voice and push notifications.

## Privacy and help

Requests to a hosted model include the relevant text, code or files that model needs. Local model inference runs on your computer; tools may contact web services as requested. Remote messages between your devices and computer are end-to-end encrypted through the relay.

[Privacy policy](https://torylabs.dev/privacy) · [Report a bug](https://github.com/su-record/vica-releases/issues/new) · [All releases](https://github.com/su-record/vica-releases/releases)

For bug reports, include your OS, Vica version, steps and the error message. Remove API keys and private project content from screenshots and logs. This repository hosts public downloads and issues; it does not contain the app's source code.
