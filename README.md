# 📡 Network Packet Sniffer (Python)

A simple yet powerful Python-based packet sniffer built using Scapy to capture and analyze live network traffic. This project helps in understanding how data flows across networks and the structure of packets.

---

## 🚀 Features

- Capture live network packets
- Extract Source & Destination IP addresses
- Identify protocols (TCP, UDP, ICMP)
- Display port numbers
- View packet payload (data)
- Real-time packet analysis

---

## 🛠️ Tech Stack

- Python
- Scapy

---

## 📦 Installation

1. Clone the repository:

git clone https://github.com/your-username/packet-sniffer.git  
cd packet-sniffer  

2. Install dependencies:

pip install scapy  

---

## ▶️ Usage

Run the script with administrator/root privileges:

python main.py  

NOTE: Packet sniffing requires elevated permissions.

---

## 🧪 Example Output

=== New Packet Captured ===  
Source IP      : 192.168.1.5  
Destination IP : 142.250.182.78  
Protocol       : 6  
Protocol Type  : TCP  
Source Port    : 52344  
Destination Port: 443  
Payload        : b'GET / HTTP/1.1...'  

---

## 📚 What You’ll Learn

- Basics of networking and packet flow  
- TCP/IP protocol suite  
- Packet structure and layers  
- Real-time traffic monitoring  

---

## 🧩 Future Improvements

- Filter specific traffic (HTTP, DNS, etc.)  
- Save packets to .pcap file  
- Build GUI (Wireshark-like interface)  
- Add HTTPS traffic insights (limited)  

---

## ⚠️ Disclaimer

This tool is for educational purposes only.  
Do not use it on networks without proper authorization.

---

## 🤝 Contributing

Pull requests are welcome! Feel free to fork this repo and improve the project.

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Show Your Support

If you like this project, give it a star on GitHub
