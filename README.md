# -Capture-and-Analyze-Network-Traffic-Using-Wireshark


📌 Objective
Capture live network packets and identify basic protocols and traffic types using Wireshark.

🛠 Tools
- Wireshark (Free and open-source)

 📂 Deliverables
- A packet capture file (`.pcap`)
- A short report summarizing protocols identified

---

🚀 Steps to Perform

1. Install Wireshark
   - Download from: [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)

2. Start Capturing
   - Open Wireshark
   - Select your active network interface (Wi-Fi/Ethernet)
   - Click the blue shark fin icon to start capture

3. Generate Network Traffic
   - Browse different websites
   - Optionally run:  
     ```bash
     ping google.com
     ```
   - This will ensure packets are captured

4. Stop Capture
   - After ~1 minute, click the red square stop button

5. Filter Captured Packets
   - In the display filter bar, use:
     - `http` → Show HTTP traffic
     - `dns` → Show DNS queries/responses
     - `tcp` → Show TCP connections

6. Identify at least 3 Protocols
   - Example:
     - HTTP – Web browsing requests/responses
     - DNS – Resolving domain names to IPs
     - TCP – Transport layer communication
     - (Optional: ICMP for ping requests)

7. Export Capture
   - `File → Save As → network_capture.pcap`

8. Summarize Findings
   - Create a short table of identified protocols, packet counts, and descriptions.

🎯 Outcome
- Gained hands-on packet analysis** skills
- Learned to identify and filter network traffic by protocol
- Improved awareness of network communication patterns
