# Network and Port Scanner 🖧

[![Project Logo](image-url)](image-url)

Developed by: **Mohamed Khaled Nassar**  
Course: **Network Security (CSE 231)** | Instructor: **Dr. Aida Nasr**  
Academic Email: [1800364@el-eng.menofia.edu.eg](mailto:mohamednassar@el-eng.menofia.edu.eg)

---

## 📝 Description

The **Network and Port Scanner** is a Python-based tool designed for both cybersecurity professionals and network administrators. It enables users to identify connected devices on a network and detect open ports on those devices or any given domain. The scanner supports the following functionalities:

- **Network Discovery**: Identifies devices on a local network and retrieves their IP and MAC addresses.
- **Port Scanning**: Scans for open ports within a user-specified range and provides the associated services (if available).

---

## 🚀 Features

- **Network Scanning**:
  - Discovers active devices on the local network.
  - Displays the IP and MAC addresses of the discovered devices in a tabular format.

- **Port Discovery**:
  - Scans a provided IP address or domain name within a user-defined port range.
  - Identifies open ports and associated services.

- **User-Friendly Interface**:
  - Intuitive menu to select the desired functionality.
  - Verification of user input to ensure proper operations.

---

## 🛠️ Setup Instructions

1. Clone this repository:
    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:
    ```bash
    cd <project-directory>
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    **Note**: Ensure Python is installed on your system.

4. Run the program:
    ```bash
    python "Network&Port Scanner.py"
    ```

---

## 🧰 Dependencies

- **Python 3.x**
- **Scapy**: A Python library for working with network packets.
- **Socket Library**: A built-in Python module for network communication.

To install Scapy, use:
```bash
pip install scapy
```

---

## 🖥️ Usage

1. On running the script, you can choose one of the following:
    - Discover devices on the local network.
    - Scan for open ports on a selected device or a domain name.
 
2. Follow the prompts to input IP addresses, IP ranges, and port ranges. Ensure you are on the same network when discovering connected devices.

3. To terminate the program, select option `[3] Exit`.

---

## ⚙️ How It Works

1. **Network Discovery**:
   - Leverages ARP requests and the Scapy library to

