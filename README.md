# Developer Setup Script for Windows

This script is designed to automate the process of setting up a fresh Windows install with all the necessary programs and tools for a developer.

## Prerequisites

- Windows operating system (tested on Windows 10)
- Administrator privileges

## Included Programs

- Git
- Visual Studio Code
- Python
- Chrome
- etc.

## Installation

1. Open PowerShell as an administrator.
2. Install chocolatey

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

3. Run the script setup.ps1 to install the necessary software.
4. Follow the prompts to complete the installation.

## Usage

You can now start using the installed programs and tools for development.

## Note

- This script is intended for educational and development purposes only.
- It may not be suitable for production environments.
- Use at your own risk.

## Contribution

You are welcome to contribute to this script by submitting a pull request with any improvements or suggestions.
