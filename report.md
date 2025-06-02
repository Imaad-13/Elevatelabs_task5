# 📊 Protocol Analysis Report – `capture.pcapng`

## 🔍 Summary

The packet capture reveals the following protocols in use:

| Protocol | Description                 | Packet Count |
|----------|-----------------------------|--------------|
| Ethernet | Layer 2 data link protocol  | [count]      |
| IPv4     | Internet Layer protocol     | [count]      |
| TCP      | Reliable transport protocol | [count]      |
| HTTP     | Web traffic (port 80)       | [count]      |
| DNS      | Domain resolution protocol  | [count]      |

> _Note: Replace `[count]` with actual numbers from your Wireshark Protocol Hierarchy output._

---

## 📌 Observations

- Most of the traffic is **TCP-based**, indicating standard web or application communication.
- Presence of **DNS** traffic suggests domain name resolution (e.g., website lookups).
- **HTTP** packets confirm unencrypted web communication or API access.
- No encrypted traffic (HTTPS/SSL) was found, implying data was transmitted in plaintext.
- The overall capture shows common network behavior possibly simulating client-server interaction.

---

## 📂 Deliverables

- `capture.pcapng` – Raw packet capture file.
- `protocol-summary-report.md` – Protocol breakdown and analysis.

