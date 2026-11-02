RMD LeakGuard
A privacy-first network diagnostic tool and live security monitor built for Windows.

RMD LeakGuard checks for common VPN and proxy leak vectors (IPv4, IPv6, DNS, WebRTC) and includes a live cybersecurity dashboard to monitor TCP/UDP connections, 
catch suspicious port activity, and detect potential network threats.

Features
Quick Test: Instant check for public IP, ISP, DNS leaks, and WebRTC exposure.

Extended Test: Deep parallel scanning for DoH, DNS response times, and privacy flags.

Security Monitor: Live connection tracking with process attribution.

Threat Detection: Port scan, SYN flood, and suspicious port detection.

Packet Capture: Raw IPv4 packet stream (Admin required).

IP Filters: Manage false positives and block known threats.

Is it safe to run?
Yes, it is completely safe to run.

No Telemetry: Absolutely no data is logged, stored, or uploaded to external servers.

Local Execution: Everything runs locally on your machine.

Open Source: The code is available here. You can review it or compile it yourself to see exactly what it does.

Passive Monitoring: The security monitor uses standard Windows APIs to read your network tables, the same way Task Manager does.

Requirements
Yes, you need the .NET runtime installed to run this.
This is a C# Windows Forms application. You will need:

OS: Windows 10 or 11 (64-bit)

Runtime: .NET Desktop Runtime 6.0 or 8.0 (depending on the version you built it with) OR .NET Framework 4.8.

Privileges: Run as Administrator. This is required for the Raw Packet Capture feature to function, as Windows blocks raw socket access for standard users. The rest of the app will run without admin rights.

How to Run
Download the latest .exe from the Releases tab.

Right-click the .exe and select "Run as Administrator".

Run a Quick Test to check your privacy, or open the Security Test to monitor network traffic.

Disclaimer
RMD LeakGuard is a self-diagnostic tool. It does not provide anonymity, does not encrypt your traffic, and is not a replacement for a VPN or OS hardening. 
A clean report means the endpoints it tests see no obvious leaks. It is not a guarantee of absolute privacy. Always pair it with a trusted VPN and keep Windows updated.
