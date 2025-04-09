# 🚨 DNS Spoofing Detection Tool

A real-time DNS spoofing detection tool with an interactive GUI, live traffic graph, sound alerts, and desktop notifications — built using Python, Scapy, Tkinter, and Matplotlib.

---

## 🔍 Features

- **🔎 Live DNS Monitoring** — Captures DNS traffic in real time using Scapy.
- **🛡️ Spoofing Detection** — Compares DNS responses with a trusted resolver (`8.8.8.8`) to detect tampering.
- **⚠️ Suspicious Packet Alerts** — Flags DNS responses with missing answer sections.
- **📢 Desktop Notifications** — Get notified instantly via system tray alerts (via `plyer`).
- **🔊 Sound Alerts** — Audible beeps when spoofing or suspicious activity is detected.
- **🖥️ GUI Interface** — Tkinter-based GUI to view alerts and interact with logs.
- **📊 Live DNS Traffic Graph** — Real-time graph of DNS query volume over the last 60 seconds using Matplotlib.
- **🗂️ Filtering Options** — Filter logs to show all alerts, only spoofed responses, or only suspicious packets.
- **💾 Log Export** — Save filtered alerts to a `.txt` file for further analysis.

---

## 📸 Screenshot

> *(You can add a screenshot here for visual reference)*

---

## 🛠️ Requirements

- Python 3.x
- [`scapy`](https://pypi.org/project/scapy/)
- [`dnspython`](https://pypi.org/project/dnspython/)
- [`matplotlib`](https://pypi.org/project/matplotlib/)
- [`plyer`](https://pypi.org/project/plyer/) *(optional, for desktop notifications)*
- `tkinter` (Usually included with Python installations)

### 📦 Install Dependencies

```bash
pip install scapy dnspython matplotlib plyer
