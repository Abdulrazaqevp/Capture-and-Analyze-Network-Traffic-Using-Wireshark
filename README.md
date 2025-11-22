# Wireshark Packet Capture and Analysis

## Objective
The objective of this task is to capture live network packets using Wireshark and analyze the network traffic to identify basic protocols and traffic types. This exercise helps in understanding how data flows in a network and how different protocols operate.

## Tools Used
- **Wireshark**: A free and open-source network protocol analyzer that allows capturing and inspecting network packets in real-time.
- **Kali Linux / Windows**: Environment where Wireshark was installed and executed.

## Steps Performed

1. **Install Wireshark**
   - On Linux: `sudo apt install wireshark`
   - On Windows: Download and install from [Wireshark official site](https://www.wireshark.org/).

2. **Launch Wireshark**
   - Open Wireshark and select the network interface you want to capture traffic from.

3. **Capture Network Packets**
   - Click on the start capture button.
   - Let it capture packets for a few minutes while performing normal network activities (browsing, pinging, etc.).

4. **Stop Capture**
   - Click the stop button once enough packets have been captured.

5. **Analyze Captured Packets**
   - Observe protocols like TCP, UDP, ICMP, HTTP, DNS.
   - Filter packets using Wireshark display filters. Examples:
     - `tcp` → Show only TCP traffic
     - `http` → Show only HTTP traffic
     - `dns` → Show only DNS queries/responses

6. **Save Capture**
   - Save the capture file as `wireshark_captured.pcapng` for documentation and further analysis.

## Observations
- Common protocols observed: TCP, UDP, ICMP, HTTP, DNS.
- Packet sources and destinations corresponded to local devices and external servers.
- The traffic flow demonstrated typical client-server communication.

## Deliverables
1. Packet capture file: `wireshark_captured.pcapng`
2. Screenshot of Wireshark capturing packets are included in report pdf.
