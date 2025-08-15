# VPN-Privacy-and-Speed-Test
VPN setup, IP change verification, and internet speed comparison before and after using ProtonVPN
# VPN Privacy and Speed Test

## Overview
This repository contains the results of a hands-on VPN exercise. The goal was to set up a VPN, verify that the IP address changes when connected, and compare internet speeds before and after using the VPN.

## Steps Followed
1. **VPN Selection & Setup**
   - Selected ProtonVPN (Free tier) as the VPN provider.
   - Installed the VPN client.

2. **Connection**
   - Connected to a VPN server in Japan.

3. **IP Address Verification**
   - Checked IP before VPN connection: 103.120.95.109 (India)
   - Checked IP after VPN connection: 149.88.103.47 (Japan)
   - Used https://whatismyipaddress.com for verification.

4. **Speed Test**
   - Ran speed test before and after VPN using Speedtest.net.
   - Recorded download/upload speeds and latency.

5. **Connection Status**
   - Captured VPN connection status from ProtonVPN interface.

## Results
- **Before VPN**
  - IP: 103.120.95.109 (India)
  - Speed: Download ~97.12 Mbps / Upload ~99.69 Mbps
- **After VPN**
  - IP: 149.88.103.47 (Japan)
  - Speed: Download ~90.95 Mbps / Upload ~82.39 Mbps

## Key Observations
- IP address changed successfully, masking original location.
- Slight decrease in speed after VPN connection due to encryption and routing.
- VPN provides encryption, privacy, and location masking but may reduce speed.

## Benefits of VPN
- Hides real IP and location.
- Encrypts internet traffic.
- Protects data from interception on public Wi-Fi.
- Helps bypass geo-restrictions.

## Limitations of VPN
- Cannot guarantee 100% anonymity.
- Slightly reduced internet speed.
- VPN provider can still see your traffic.
- Some sites block known VPN IP addresses.

## Files in This Repository
- `screenshots/ip_before_vpn.png`
- `screenshots/ip_after_vpn.png`
- `screenshots/speedtest_before_vpn.png`
- `screenshots/speedtest_after_vpn.png`
- `screenshots/vpn_connection_status.png`

---
**Author:** Naman Patil
