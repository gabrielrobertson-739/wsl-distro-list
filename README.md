![WSL Distro List](assets/hero.png)

# WSL Distro List

*What is installed in WSL, as a table.*

## What WSL Distro List is

This repository is **WSL Distro List**, a desktop utility. What is installed in WSL, as a table.

wsl -l -v is fine. A CSV for a ticket is better.

Files stay on the machine that runs the tool. Originals are left alone unless you choose otherwise.

## What's included

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## What it does

- Name, state, version
- CSV optional
- Read-only
- Notes missing WSL

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/gabrielrobertson-739/wsl-distro-list

MIT license. See `LICENSE`.
