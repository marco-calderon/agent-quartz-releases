# AgentQuartz Releases

Public download host and **issue tracker** for **AgentQuartz** macOS builds.

This repository distributes **unsigned** `.app` zip archives only. It does **not** contain application source code.

## Download

Get the latest build from the [latest GitHub Release](https://github.com/marco-calderon/agent-quartz-releases/releases/latest).

Website: [agentquartz.vercel.app](https://agentquartz.vercel.app)

## Report a problem

Use **[GitHub Issues](https://github.com/marco-calderon/agent-quartz-releases/issues)** on this repository:

- [Bug report](https://github.com/marco-calderon/agent-quartz-releases/issues/new?template=bug_report.yml) — something broken or unexpected
- [Feature request](https://github.com/marco-calderon/agent-quartz-releases/issues/new?template=feature_request.yml) — ideas and improvements

Please **do not** paste API keys, session cookies, or other secrets into issues.

## First open on macOS (Gatekeeper)

Because builds are unsigned, macOS may block the app on first launch:

1. Download and unzip the release asset.
2. Move `AgentQuartz.app` to Applications (or another location you prefer).
3. Right-click (or Control-click) the app and choose **Open**, then confirm **Open** in the dialog.
4. If needed, allow the app under **System Settings → Privacy & Security**.
