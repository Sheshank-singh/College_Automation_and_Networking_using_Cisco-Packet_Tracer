# 📡 College_Automation_and_Networking_using_Cisco-Packet_Tracer

A smart campus simulation project developed using **Cisco Packet Tracer 8.2** to demonstrate IoT-based automation, secure access control, and robust network architecture using ASA firewall and static routing.

## 🚀 Project Overview

This project showcases the **automation and networking** of a college campus using:
- **IoT devices** like motion sensors, smart fans, fire detectors, and lawn sprinklers.
- **Secure access systems** using RFID authentication.
- **Networking components** including routers, switches, ASA firewall.
- A **Home Gateway** acting as a central hub for IoT communication.

The aim is to reduce power consumption, improve campus security, and provide a scalable and secure network infrastructure.

## 🛠️ Tools & Technologies

- **Cisco Packet Tracer 8.2**
- **IoT Components**: Motion Detector, Fan, Lamp, Fire Detector, Lawn Sprinkler, RFID Reader
- **Networking Devices**: Routers, Switches, ASA Firewall, Wireless Home Gateway
- **MCU Board**
- **Tablet/PC Interface** for writing automation rules

## 🧠 Features Implemented

### ✅ IoT Automation:
- Light & Fan control based on motion and door status
- Fire detection system to shut down fan and trigger alarm
- Lawn watering automation using water level sensor and sprinkler
- All devices connected via a **Home Gateway** (SSID: `HomeGateway`)

### 🔐 Security Features:
- **RFID-Based Access Control**:
  - Faculty vs Student access differentiation
  - Secured department/classroom entry
- **ASA Firewall**:
  - Access Control Lists (ACLs) to permit/deny traffic
  - Internal-external interface protection
  - Malicious zone simulation for attack prevention

### 🌐 Network Configuration:
- Segmentation: IoT Zone, Server Zone, Student Lab, Admin Dept.
- Static Routing for inter-VLAN communication
- IoT devices wired/wirelessly configured through the Home Gateway
- No password required for device pairing (for simulation purposes)

## 🤝 Contributing

Feel free to fork this repo, submit issues or pull requests. Contributions are always welcome to make this project more robust and feature-rich.

## 🧑‍💻 Author

**Sheshank Anangpal Singh**  
Computer Engineering, Vidyalankar Institute of Technology 

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## ⭐ Acknowledgements

- Cisco Packet Tracer Team
- Vidyalankar Institute of Technology
- Faculty and mentors for guidance
