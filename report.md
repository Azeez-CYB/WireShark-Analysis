# Network Traffic Analysis Report

## Objective

The objective of this project was to capture and analyse live network traffic using Wireshark in order to understand network communication behaviour, identify common protocols, and observe potential security-related indicators.

---

## Tools Used

- Wireshark  
- Windows Operating System  
- Home Wi-Fi Network  

---

## Capture Details

- Capture duration: Approximately 1 minute  
- Network interface used: Wi-Fi  
- Traffic type: Live local network traffic  

---

## Protocols Observed

During the capture, the following protocols were identified:

- TCP (Transmission Control Protocol)  
- DNS (Domain Name System)  
- HTTP / HTTPS (Web traffic)  
- TLS (Encrypted communication)  

These protocols represent common network communication used by web browsing and application traffic.

---

## Traffic Analysis

### DNS Traffic

DNS packets were observed resolving domain names into IP addresses. This demonstrates how devices locate websites and online services.

Example observation:
- Client device sent DNS query  
- DNS server responded with destination IP address  

This type of traffic can be monitored to identify suspicious domain requests.

---

### TCP Communication

TCP packets showed the three-way handshake process:

- SYN (connection request)  
- SYN-ACK (server response)  
- ACK (connection established)  

This confirms normal connection establishment behaviour between devices.

---

### HTTP and HTTPS Traffic

Both encrypted (HTTPS/TLS) and unencrypted (HTTP) traffic were observed.

Security observation:
- HTTPS traffic encrypts sensitive information  
- HTTP traffic transfers data in plain text and may expose user data  

This highlights the importance of encrypted communication for security.

---

## Security Observations

The following security-related observations were identified:

- Unencrypted HTTP traffic may expose credentials and personal data  
- DNS traffic reveals browsing patterns and domain activity  
- Large packet transfers may indicate potential data exfiltration or file downloads  
- Monitoring TCP flags can help identify abnormal connection behaviour  

No malicious activity was detected during this capture session.

---

## Conclusion

This project demonstrated how Wireshark can be used to capture and analyse network traffic for security monitoring purposes. The analysis improved understanding of network protocols, packet structure, and the importance of encryption and traffic inspection in cybersecurity operations.

This hands-on exercise reflects basic SOC analyst responsibilities such as traffic filtering, protocol analysis, and threat visibility.

---

## Skills Demonstrated

- Packet capture and inspection  
- Network protocol analysis  
- Traffic filtering using Wireshark  
- Security-focused observation and reporting  
- Technical documentation  
