# Keylogger Project

## Overview

This project is a basic implementation of a keylogger using Python. The keylogger captures all keystrokes on the keyboard, logs them into a text file (`keylogger.txt`), and sends the recorded key logs via email.

## Features

- **Key Logging**: Captures all keystrokes, including special keys (e.g., Enter, Backspace, Tab, Space).
- **File Writing**: Appends captured keystrokes to a text file (`keylogger.txt`).
- **Email Notification**: Sends the logged key data to a specified email address when the keylogger stops.
- **Cross-Platform**: Can be run on Windows, macOS, and Linux.

## Prerequisites

- Python 3.x
- Python libraries:
  - `pynput`
  - `smtplib`
  - `ssl`

You can install the required libraries using `pip`:
```bash
pip install pynput
