Developed a Python-based network simulator that implements a comprehensive protocol stack, covering the Physical, Data Link, Network, Transport, and Application layers.

## Overview

The network simulator enables simulation of various networking functionalities, including device creation, packet transmission, routing, and application layer services.

## Functionalities Implemented

### Submission 1: Physical and Data Link Layer

- **Physical Layer:**
  - End device and hub creation.
  - Topology formation with device connections.
  - Data transmission.

- **Data Link Layer:**
  - Layer 2 devices: bridge and switch.
  - Address learning (switches).
  - Error control (Parity Check).
  - Access control (CSMA/CD).
  - Flow control (Sliding window).

### Submission 2: Network Layer

- **Network Layer:**
  - Router creation and configuration.
  - IPv4 address assignment (classless).
  - ARP for MAC address resolution.
  - Static routing.
  - Dynamic routing (RIP or OSPF).

### Submission 3: Transport and Application Layer

- **Transport Layer:**
  - Port number assignment.
  - Sliding window flow control (Go-Back-N or Selective Repeat).

- **Application Layer:**
  - Telnet service.
  - FTP service.

## File Structure

- **physical_layer.py:** Physical layer functionalities.
- **data_link_layer.py:** Data link layer functionalities.
- **network_layer.py:** Network layer functionalities.
- **transport_application_layer.py:** Transport and application layer functionalities.
- **README.md:** Overview of the project.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/sharmashubam/computer_networks_project.git
   ```
2. Run Python scripts for different layers:
   ```bash
   python physical_layer.py
   python data_link_layer.py
   python network_layer.py
   python transport_application_layer.py
   ```

## Test Cases

Included test cases demonstrate the functionality of each layer within the simulator.

## Contributors

- [Shivam Sharma](https://github.com/cvam12sharma)
- [Shubam Sharma](https://github.com/sharmashubam)
- [Podugu Manicharan](https://github.com/manicharanpodugu)

---

This version removes the "Network Simulator" heading as requested.
