# WinSecureAI-PS

**Enterprise-Grade Vulnerability Assessment & Remediation Tool** powered by PowerShell and Google Gemini AI.

## Features
- **Comprehensive Scanning**: System, Network, Active Directory, and Vulnerability analysis.
- **AI-Powered Analysis**: Uses Gemini AI to explain findings and suggest contextual fixes.
- **Remediation Engine**: 50+ built-in security fixes with "Dry Run", Backup, and Rollback capabilities.
- **Threat Hunting**: Detects persistence mechanisms, LoLBins, and credential dumping artifacts.
- **Compliance Mapping**: Maps findings to NIST and CIS standards.
- **Reporting**: Generates interactive HTML dashboards and PDF reports.

## Installation
1. Download the `WinSecureAI-PS` folder.
2. Right-click `Install-WinSecureAI.ps1` and select **Run with PowerShell**.
   - Accepts prompts to unblock files and create a Desktop Shortcut.
3. (Optional) Run `.\WinSecureAI-PS.ps1 -Schedule` to enable daily scans.

## Quick Start
Open PowerShell as Administrator and run:
```powershell
# Full System Scan
.\WinSecureAI-PS.ps1 -Scan -Full
```

## Documentation
- [Usage Examples](Docs/EXAMPLES.md)
- [Troubleshooting](Docs/TROUBLESHOOTING.md)

## Requirements
- Windows 10/11 or Windows Server 2016+
- PowerShell 5.1 or newer
- Internet access for AI Analysis (Google Gemini API)

## License
Copyright (c) 2025 WinSecureAI. All Rights Reserved.
