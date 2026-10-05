# Libraries & Software

Reference list of the software and libraries this project will use once implementation begins. No code — just what each piece is for.

## Platform

- **Raspberry Pi OS (Linux)** — operating system running on the Raspberry Pi 5.
- **Python 3** — primary language for the agent and all tools.
- **VS Code + Remote-SSH** — editor used to write code directly on the Pi.
- **Git / GitHub** — version control once code exists.
- **SSH** — remote access to the Pi's command line.

## Reasoning

- **Claude API (Anthropic)** or **OpenAI API** — handles planning, reasoning, and tool selection.

## Audio Pipeline

- **pvporcupine** or **openwakeword** — wake-word detection.
- **speech_recognition** or **Whisper** — speech-to-text.
- **pyttsx3** or a cloud TTS API — text-to-speech.

## Execution Layer

- **os, shutil, pathlib** (Python standard library) — file operations: find, create, move, rename.
- **pyautogui, mss** — screenshots and GUI-control fallback, used only when no direct tool exists for a task.
- **logging, json** (Python standard library) — audit logging.

## Deployment

- **systemd** — autostart service on boot.
