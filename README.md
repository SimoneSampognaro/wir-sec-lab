## Wireless Security Course Laboratories

This repository contains two practical laboratory reports from the *Wireless Security* course held at Politecnico di Torino, 2024/2025. The labs explore vulnerabilities and performance characteristics of wireless technologies through hands-on experiments and analysis.

### 📡 Lab 1 — GNSS Signal Analysis and Spoofing

This lab focuses on:

* Collecting and analyzing raw GNSS measurements using Android smartphones and the **GnssLogger** app.
* Evaluating positioning accuracy under different environmental conditions (open sky, battery-saving mode, obstructed reception).
* Applying filters to improve positioning precision.
* Simulating **GNSS spoofing attacks** and analyzing their impact on positioning and receiver bias using MATLAB scripts.

**Key findings:**

* GNSS accuracy is significantly affected by environment and signal quality.
* Spoofing attacks can effectively mislead GNSS receivers, highlighting the need for countermeasures like anomaly detection and signal authentication.

### 📶 Lab 2 — WiFi Performance Evaluation

This lab explores:

* Performance benchmarking of WiFi connections (802.11ac) using **Wireshark** and **iperf3**.
* Multiple network scenarios: WiFi-to-WiFi, Ethernet-to-WiFi, and Ethernet-to-Ethernet.
* Impact of TCP/UDP protocols, bitrate tuning, and packet length on network goodput.
* WiFi asymmetry, congestion, and bufferbloat effects on throughput and latency.

**Key findings:**

* Wireless links are more prone to performance variability and packet loss compared to wired ones.
* Careful tuning of parameters (e.g., UDP bitrate and packet size) can significantly improve performance.
* TCP performance is affected by network congestion, leading to ACK delays and reduced throughput.

---

### 📂 Contents

* `GNSS_Lab.pdf` — Report on GNSS spoofing experiments and analysis.
* `WiFi_Lab.pdf` — Report on WiFi performance analysis under different network setups.

---

### 📘 Course

* **Course Name**: Wireless Security
* **Institution**: Politecnico di Torino
* **Academic Year**: 2024–2025
* **Authors**: Simone Sampognaro, Luca Nobili, Vito Cucinelli
