## Network Scanner

A Python script to scan a network and discover IP and MAC addresses of connected devices.

### Features

- Scan a specified IP range or target network
- Display IP and MAC addresses of connected clients

### Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Daniel-Ikenna/network_scanner
   ```

2. **Run the Script**:
   ```bash
   sudo python network_scanner.py -t <target_ip_range>
   ```
   Example:
   ```bash
   sudo python network_scanner.py -t 192.168.1.1/24
   ```

### Requirements

- Python 3.x
- `scapy` library (install via `pip install scapy`)
- Superuser privileges (use `sudo`)

### Authors

- [Zaid Sabih](https://ie.linkedin.com/in/zaid-sabih-al-quraishi-5444a6127)
- [Uzoeshi Daniel](https://www.linkedin.com/in/daniel-ikenna-33b709235)
