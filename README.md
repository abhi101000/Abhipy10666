# Task 4 – Basic Firewall Configuration on Windows

## Objective:
Configure and test basic firewall rules to block Telnet (port 23).

## Steps Followed:
1. Opened Windows Defender Firewall.
2. Created a new inbound rule to block TCP port 23.
3. Enabled Telnet Client via Windows Features.
4. Tested the rule using `telnet localhost 23`.
5. Verified the connection was blocked (connect failed).
6. (Optional) Removed the rule to restore original settings.

## Tools Used:
- Windows Firewall
- Telnet Client
- Command Prompt

## Outcome:
Successfully learned how to block specific ports using Windows Firewall.
