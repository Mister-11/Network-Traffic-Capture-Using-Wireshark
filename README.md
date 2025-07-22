# 🛰️ Network Traffic Capture Using Wireshark

This project demonstrates how to capture and analyze real-time network traffic using **Wireshark**, a powerful open-source packet analyzer. The goal is to understand how various protocols such as HTTP, DNS, and TCP operate within a live network environment.

---

## 🎯 Objective

To capture live packets, apply protocol-based filters, and analyze data flow between devices and servers. The project provides insights into how data moves through the OSI model layers and helps in learning packet structure and inspection techniques.

---

## 🛠️ Tools Used

- **Wireshark** (latest version)
- **Web Browser** (to generate traffic)
- Operating System: Windows/Linux

---

## 🧪 Steps Performed

1. Launched Wireshark and selected the active network interface (e.g., Wi-Fi).
2. Started capturing live network packets.
3. Opened a browser and visited public websites to create traffic.
4. Applied filters (`http`, `dns`, `tcp`) to isolate specific protocols.
5. Analyzed selected packets for source/destination IP, protocol, and payload structure.
6. Stopped the capture and saved data for reporting.

---

## 📸 Screenshots

> Add screenshots in a `/screenshots` folder and reference them here:

- ![DNS Query Packet](screenshots/dns_packet.png)
- ![HTTP Filter View](screenshots/http_filter.png)
- ![Captured Packet List](screenshots/packet_list.png)

---

## ✅ Conclusion

This project enhanced my practical understanding of computer networks and protocols. Using Wireshark helped visualize packet flow, analyze real-time communication, and understand how networked systems exchange data securely and efficiently.

---

## 📁 Files Included

- `README.md` – Project documentation  
- `screenshots/` – Screenshots of captured packets  
- `.pcap` (optional) – Saved capture file from Wireshark

---

## 📚 References

- [Wireshark Official Site](https://www.wireshark.org/)
- [Wireshark Filtering Guide](https://wiki.wireshark.org/DisplayFilters)
