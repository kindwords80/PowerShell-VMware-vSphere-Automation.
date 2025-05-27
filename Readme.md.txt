# VMware Snapshot Manager 🚀

A PowerShell-based automation tool that helps VMware administrators manage VM snapshots efficiently using PowerCLI.

## 🔧 Features
- Create snapshots with timestamp and notes
- List all VMs with existing snapshots
- Automatically delete snapshots older than X days
- Logging enabled for auditing

## 💻 Tech Stack
- PowerShell
- VMware PowerCLI
- vSphere / vCenter

## 🚀 Getting Started

### Prerequisites
- PowerShell
- PowerCLI installed (Install-Module -Name VMware.PowerCLI)
- Access to vCenter server

### Run the Script
.\snapshot-manager.ps1 -vCenter "192.168.1.100" -DaysToKeep 7

### Parameters
- -vCenter: IP or hostname of your vCenter Server (required)
- -DaysToKeep: Number of days to keep snapshots (default: 7)

## 📁 Logs
All actions (created or removed snapshots) are logged in snapshot-log.txt.

## 🛠️ Future Improvements
- Add HTML or email reporting
- Integrate with Windows Task Scheduler
- GUI version (PowerShell WPF)

##
