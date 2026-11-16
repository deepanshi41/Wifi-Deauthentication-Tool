# Wi-Fi Deauthentication Tool

### 🚀 This tool has been recreated with Python and is available on [ezhil56x/deauther](https://github.com/ezhil56x/deauther) ⚠️

# Wi-Fi Interface Detection and Diagnostic Tool

## Overview
A Bash-based educational project developed in Kali Linux to demonstrate network interface detection and basic interface diagnostics.

## Features
- Automatic detection of the default network interface.
- Display network adapter status.
- Manual interface detection.
- Interactive terminal menu.
- Input validation and error handling.
- Safe test mode.

## Technologies Used
- Kali Linux
- Bash scripting
- iproute2
- VMware Workstation (testing environment)

## Requirements
- Kali Linux or another Linux distribution.
- Bash shell.
- iproute2 utilities.

## Installation

Clone the repository:

```bash
git clone https://github.com/ezhil56x/Wifi-Deauthentication-Tool.git
```

Navigate to the project:

```bash
cd Wifi-Deauthentication-Tool
```

## Execution

Run the script:

```bash
bash wifideauth.sh
```

## Menu Options

1. Wi-Fi scanning - disabled in safe version.
2. Select network - disabled in safe version.
3. Client deauthentication - disabled.
4. Deauthenticate all clients - disabled.
5. Check adapter status.
6. Detect interface again.
7. Exit.

## Testing
The project was tested in Kali Linux running inside VMware Workstation.

The detected default network interface in the test environment was eth0.

## Important Limitations
The VMware virtual Ethernet adapter is not a physical wireless adapter.

Wireless scanning and disruptive deauthentication features are disabled in this safe educational version.

## Disclaimer
This project is intended for educational purposes and authorized cybersecurity learning only.

**Disclaimer:**
This tool is provided for educational purposes only. It should not be used for illegal activities. Only use it for legitimate penetration testing and security research purposes and network devices that you own or have permission to test. By using this tool, you agree that you will not engage in any unauthorized or illegal activities with it. You understand that the misuse of this tool may violate laws and regulations and can lead to severe legal consequences, including criminal charges and penalties. The author of this tool shall not be held responsible for any damages or liabilities caused by the use or misuse of this tool. Use this tool at your own risk and with proper authorization. Ensure compliance with applicable laws and obtain necessary permissions before using it.

## Introduction

Wi-Fi Deauthentication Tool is a command-line utility designed for educational purposes, allowing you to perform various actions related to Wi-Fi networks. This tool is intended for legitimate penetration testing, security research purposes, and network devices that you own or have permission to test.

## Features

- **Scan for Wi-Fi networks**: Discover nearby Wi-Fi networks and view their details.
- **Select a Wi-Fi network for further actions**: Choose a specific Wi-Fi network for additional actions.
- **Deauthenticate a client from a Wi-Fi network**: Deauthenticate a specific client from a selected Wi-Fi network.
- **Deauthenticate all clients from a Wi-Fi network**: Deauthenticate all clients connected to a selected Wi-Fi network.
- **Check Wi-Fi Adapter Status**: Get the status of the Wi-Fi adapter.
- **Change Wi-Fi Adapter Interface Name**: Modify the interface name of the Wi-Fi adapter.

## Prerequisites

Before using this tool, ensure that you have the following prerequisites:

- Linux environment
- Airodump-ng and Aireplay-ng tools installed
- Proper permissions to execute the script

If you don't have airodump-ng and aireplay-ng installed on your system, you can install them using the following steps:

1. Install aircrack-ng package:

   - For Debian-based systems, run: `sudo apt-get install aircrack-ng`
   - For Red Hat-based systems, run: `sudo yum install aircrack-ng`

2. Once the aircrack-ng package is installed, airodump-ng and aireplay-ng should be available in your system.

## Usage

1. Clone the repository or download the script.
2. Ensure that the script has executable permissions (`chmod +x wifideauth.sh`).
3. Run the script using `sudo ./wifideauth.sh`.
4. Follow the on-screen menu prompts to choose the desired actions.

Please note that unauthorized attacks on devices that you do not own or do not have permission to test are illegal and unethical. Performing such attacks can lead to severe consequences, including legal actions, criminal charges, and penalties. The author of this tool shall not be held responsible for any damages or liabilities caused by the use or misuse of this tool. Always ensure that you have proper authorization and legal permissions before using this tool. Use it responsibly, respect privacy and security, and comply with all applicable laws and regulations.

## License

This tool is released under the [MIT License](LICENSE).

---

**IMPORTANT:** This tool comes with no guarantees or warranties. The author will not be responsible for any consequences resulting from the use or misuse of this tool. Use it responsibly and at your own risk.
