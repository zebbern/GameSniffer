# Server IP Finder for Games

Server IP finder for online games, providing live game session analysis for IP and port discovery.

- `Has to be in a live game session to have anything to grab!`
- `Install requirements`
- `Open python via cmd or just the exe for it to be no commands to run`
- `Made simple for none coders`
- `No Experience needed as simple as running the exe and choosing running game`

## Features
- **Monitor CPU Usage**: Identify top CPU-consuming processes.
- **Network Traffic Analysis**: List network interfaces and their traffic stats.
- **UDP Monitoring**: Track and analyze UDP traffic to detect active game servers.
- **User-Friendly Interface**: Step-by-step process selection and intuitive output.
- **Threshold-Based Alerts**: Alerts on significant data transfer rates to help pinpoint the active server.



## Requirements
- Python 3.6+
- Libraries:
  - `psutil`
  - `pyshark`
  - `colorama` (optional, for color-coded output)
- TShark installed and accessible in the system path.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/zebbern/Server-IP-Finder-for-Games.git
   cd Server-IP-Finder-for-Games
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   or
   pip3 install -r requirements.txt
   ```

3. Ensure TShark is installed on your system. Follow the [Wireshark documentation](https://www.wireshark.org/download.html) for installation instructions.

## Usage
1. Run the script:
   ```bash
   python server.py
   or
   python3 server.py
   ```

2. Follow the prompts to:
   - Select a process to monitor.
   - Choose a network interface.
   - Identify the active game server based on UDP traffic.

## Customization
Modify the following configurations in the script as needed:
- `PROCESS_NAME`: Default process name to monitor (`"cod.exe"`).
- `MONITOR_INTERVAL`: Monitoring interval in seconds (default: `1` second).
- `DATA_RATE_THRESHOLD`: Minimum data rate (in bytes/second) to consider as significant traffic (default: `400`).

## Example Outputs
![image](https://github.com/user-attachments/assets/3d2fa07d-4285-49f2-81a5-68b0e24ac5e8)

![image](https://github.com/user-attachments/assets/2cc6b4ee-5016-4edf-aab1-4e7f26fc1602)

![image](https://github.com/user-attachments/assets/485e8763-3486-4643-b34d-798794b4ae5a)

## License
This project is licensed under the [MIT License](LICENSE).

## Contributions
Contributions are welcome! Feel free to submit issues or pull requests to improve the tool.

## Author
[zebbern](https://github.com/zebbern)

## 🚨 Disclaimer
**This project is intended for educational purposes only.**  
It demonstrates techniques for analyzing network traffic to identify server IP addresses used in multiplayer games.  
**Unauthorized use of this tool to extract information from servers without permission may violate terms of service, local laws, or privacy rights.**

By using this project, you agree to:
- Use it responsibly.
- Avoid any illegal or unethical applications.
- Ensure you have proper authorization when analyzing network data.

The author is **not responsible for any misuse of this tool.**

---
