# Network Traffic Analysis Report

## Objective
To capture and analyse live network traffic using Wireshark and identify protocol behaviour and potential security indicators.

## Tools Used
- Wireshark  
- MAC OS  

## Traffic Captured
- Protocols observed: TCP, DNS, HTTP, TLS  
- Capture duration: 1 minute  
- Network interface: Wi-Fi  

## Findings
- DNS queries revealed domain name resolution activity  
- TCP three-way handshake observed (SYN, SYN-ACK, ACK)  
- HTTP traffic identified unencrypted communication  
- No malicious traffic detected during capture  

## Security Observations
- Unencrypted HTTP traffic may expose sensitive data  
- DNS traffic can reveal browsing patterns  
- Large packet transfers may indicate potential data exfiltration  

## Conclusion
This analysis demonstrates the importance of packet inspection for network monitoring and cybersecurity threat detection.


## Skills Demonstrated

- Packet capture and inspection  
- Network protocol analysis  
- Traffic filtering using Wireshark  
- Security-focused observation and reporting  
- Technical documentation  
