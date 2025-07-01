# SAMPLE - MAKE SURE YOU CHANGE THIS

# OSI vs TCP/IP Model

## 🧠 Summary
A comparison of the OSI 7-layer model vs. the TCP/IP 4-layer model used in modern networking.

---

## 📊 OSI Model

| Layer | Name              | Example Protocols |
|-------|-------------------|-------------------|
| 7     | Application       | HTTP, FTP         |
| 6     | Presentation      | SSL, TLS          |
| 5     | Session           | NetBIOS           |
| 4     | Transport         | TCP, UDP          |
| 3     | Network           | IP, ICMP          |
| 2     | Data Link         | Ethernet, ARP     |
| 1     | Physical          | Cables, Hubs      |

---

## 🔁 TCP/IP Model

| Layer | Name              | OSI Equivalent Layers |
|-------|-------------------|------------------------|
| 4     | Application       | 5–7                    |
| 3     | Transport         | 4                      |
| 2     | Internet          | 3                      |
| 1     | Network Access    | 1–2                    |

---

## 🧩 Key Differences
- OSI is theoretical; TCP/IP is practical
- OSI splits more functions into separate layers

## 📝 Notes
- Always understand TCP/IP in the context of modern networks
- Learn to map Wireshark packets to these layers
