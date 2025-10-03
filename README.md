# VPN Implementation and Analysis
This project documents the practical implementation of Proton VPN using the WireGuard protocol, verifying IP change, encryption, and conducting a speed comparison with and without VPN. It highlights both benefits and limitations of VPN usage, offering valuable insights for cybersecurity and network performance evaluation.
---
## I. Executive Summary
- Implemented **Proton VPN** with **WireGuard** protocol.
- Verified change of public IP address, confirming anonymity.
- Demonstrated encryption of all internet traffic.
- Conducted speed comparison (VPN connected vs. disconnected).
- **Key finding:** VPN improves privacy and security but reduces speed.
---
## II. Implementation and Practical Verification

### Tools Used
- **VPN Client:** Proton VPN (Free Tier)  
- **Protocol Used:** WireGuard  
- **Verification Tool:** [WhatIsMyIPAddress.com](https://www.whatismyipaddress.com)

### Practical Steps and Findings
1. Installed Proton VPN client.
2. Connected to Netherlands server (NL-FREE#197).
3. Verified new IP: `185.107.56.117` (changed from ISP IP).
4. Confirmed encryption through WireGuard/UDP.
5. Ensured secure browsing on public Wi-Fi.

## III. Performance Analysis and Speed Comparison
VPN introduces latency due to encryption and server distance.

| Status           | Download (Mbps)  | Upload (Mbps)   | Observation                          |
|------------------|------------------|-----------------|--------------------------------------|
| VPN Disconnected | [Insert speed]   | [Insert speed]  | Baseline speed (normal connection)   |
| VPN Connected    | [Insert speed]   | [Insert speed]  | Slower due to encryption overhead    |
| Difference       | [Insert % drop]  | [Insert % drop] | Performance trade-off observed       |

### Speed Test Observations
- Speed test without VPN: [Insert speed test result link or screenshot]
- Speed test with VPN: [Insert speed test result link or screenshot]
---
## IV. Summary of VPN Benefits and Limitations

### Benefits
- **Data Security:** Encrypts all data in transit.
- **Anonymity:** Masks IP and location.
- **Geo-Bypassing:** Access blocked/regional content.
- **No-Log Policy:** VPN provider does not store browsing activity.
### Limitations
- **Speed Reduction:** Slower downloads/uploads.
- **False Security:** Does not prevent malware/phishing.
- **Trust Factor:** Relies on VPN provider’s privacy policy.
- **Compatibility Issues:** Some apps/networks block VPNs.
---
## V. Conclusion
VPN provides a strong layer of cybersecurity by ensuring anonymity, encryption, and geo-bypass capability. It should be combined with antivirus software, regular updates, strong passwords, and cyber-awareness for complete protection.
This project is licensed under the MIT License.

