# Incident Response Automation

This PowerShell script provides a comprehensive solution for automating the incident response process on Windows systems. It collects a wide range of system information, volatile data, malware indicators, and forensic artifacts, which can then be analyzed and used for mitigation actions.

## Features

- Collects detailed system information, including operating system details, computer system specifications, running processes, network configuration, and event logs.
- Gathers volatile data, such as the ARP table, network connections, and TCP/UDP endpoints.
- Identifies potential malware indicators, including suspicious registry keys, processes, and files.
- Collects forensic artifacts, such as recent user activity, Prefetch files, and AMCache data.
- Saves the collected data to a ZIP file and uploads it to a secure server for further investigation.
- Provides a modular and extensible design, allowing for easy customization and integration with other security tools.

## Usage

1. Clone the repository:
  ```powershell
  git clone https://github.com/YegorCherov/incident-response-automation.git
  ```

2. Open the PowerShell script file (`IncidentResponse.ps1`) and review the configuration options, such as the secure server upload URL.
3. Run the script:
```powershell
.\IncidentResponse.ps1
```
4. The script will execute the incident response process and save the collected data to a ZIP file in the current directory.

## Contributing

Contributions to this project are welcome. If you have any ideas, bug fixes, or feature enhancements, please feel free to submit a pull request.

## License

This project is licensed under the MIT License.
