🔐 Smart Security System using Cisco Packet Tracer

 📌 Project Overview

This project presents a Smart Home Security System built using Cisco Packet Tracer, a network simulation tool. The system integrates IoT components such as motion detectors, smart doors, webcams, sirens, and smartphones to create a secure and responsive home environment.

The system is capable of detecting motion, activating alarms and cameras, and allowing the user to view and control components remotely using a smartphone interface.

---

🚀 Technologies Used

- 🔧 Cisco Packet Tracer (Simulation Platform)
- 📶 IoT Wireless Devices: Home Gateway, Motion Detector, Door, Siren, WebCam
- 📱 Smartphone Interface
- 🔐 WPA2-PSK for Wireless Security

---

 🛠 About Cisco Packet Tracer

Cisco Packet Tracer is a free, cross-platform network simulation tool developed by Cisco. It is widely used in networking education to simulate routers, switches, IoT devices, and entire networks without the need for physical hardware.

 🔍 Why Use Cisco Packet Tracer?

- ✅Realistic Network Simulation 
  Design and test networks without hardware investment.

- ✅ IoT & Smart Device Support  
  Simulate real-world IoT automation scenarios.

- ✅ Hands-on Learning  
  Ideal for students and professionals to practice network setups.

- ✅ Safe Testing
  Experiment with protocols and configurations in a risk-free environment.

---

🔑 Key Features of the Smart Security System

- 👁️ Motion detection triggers the camera and siren.
- 📲 Remote access using smartphone interface.
- 🚪 Smart door that can be locked/unlocked from inside the simulation.
- ⚙️ Condition-based automation using rules (if motion detected → activate camera + alarm).
- 🏠 All components connected via a secure Home Gateway using WPA2-PSK.

---

🧭 Implementation Steps (Summary)

1. Open Cisco Packet Tracer and create a new project.
2. Add the following components:
   - Home Gateway (Network Device > Wireless)
   - Motion Detector, Door, Siren, WebCam (End Devices > Home)
   - Smartphone (End Devices)
3. Arrange devices in a home-like setup using rectangles and labels.
4. Connect all IoT devices wirelessly to the Home Gateway.
5. Configure each device:
   - Set SSID: `HomeGateway`
   - Set password: `getconnect`
   - Connect to IoT server via Home Gateway
6. On the smartphone:
   - Open Web Browser
   - Visit: `http://192.168.25.1`
   - Login with `admin/admin`
7. Create two automation rules:
   - If motion detected → turn on Siren and WebCam
   - If no motion → turn off Siren and WebCam
8. Test the system by hovering the mouse over the motion detector while pressing `Alt`.

---

📸 Demonstration

- 🔔 When motion is detected:
  - Siren turns on
  - WebCam activates
  - Door remains locked

- 📴 When no motion:
  - Siren and camera turn off automatically

---



---

## 📚 References

- [Cisco Packet Tracer Official Download](https://www.netacad.com/courses/packet-tracer)
- [Cisco NetAcad IoT Tutorials](https://www.netacad.com/courses/iot)
