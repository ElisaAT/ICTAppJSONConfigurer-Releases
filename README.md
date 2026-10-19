# Installation & Configuration Guide

Follow these steps to set up the configuration file required by **ICT App JSON Configurer**.

---

## 1. Create the Configuration Directory & File

You can create the required configuration folder and the `server.env` file using **PowerShell**:

```powershell
# Create the configuration directory if it doesn't exist
New-Item -ItemType Directory -Force "$env:APPDATA\ICT App JSON Configurer"

# Open the server.env file in Notepad (creates a new file if it doesn't exist)
notepad "$env:APPDATA\ICT App JSON Configurer\server.env"
