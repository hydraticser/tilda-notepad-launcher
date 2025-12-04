# Tilde Notepad Launcher

A simple AutoHotkey script that opens Notepad with a single keystroke of the tilde key ().

## Why?
- Need to quickly open Notepad for notes
- Don't want to use taskbar or Start menu
- Want a keyboard-centric workflow
- The tilde key is rarely used in typing, making it perfect for a hotkey

## Features
- One-key launch: just press  (tilde)
- No interference with normal typing
- Lightweight and fast
- Compiled .exe available (no AutoHotkey required)

## Installation
### Option 1: Using compiled .exe (recommended)
1. Download open_notepad-1.exe from [Releases](../../releases)
2. Place it in your startup folder (shell:startup) for auto-start
3. Press  to open Notepad!

### Option 2: From source
1. Install [AutoHotkey v1.1.37.02](https://www.autohotkey.com/download/1.1/)
2. Download open_notepad-1.ahk
3. Run the script or compile it yourself

## Usage
Just press the tilde key () - Notepad will open instantly.

## Building from source
`bash
# Using Ahk2Exe from AutoHotkey installation
Ahk2Exe.exe /in "open_notepad-1.ahk" /out "open_notepad-1.exe"