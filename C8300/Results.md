## Catalyst 8300
- Part Number: C8300-1N1S-4T2X
- OS: IOS XE
- Software Version: 17.06.03a
### IPv4 Test Results
|     Test      | Result | 
|---------------|--------|
| PING_SERVER   | PASS   |
| TELNET_SERVER | PASS   |
| SSH_SERVER    | PASS   |
| SCP_SERVER    | PASS   |
| TFTP_SERVER   | PASS   |
| HTTP_SERVER   | PASS   |
| HTTPS_SERVER  | PASS   |
| SNMPV2_READ   | PASS   |
| SNMPV2_WRITE  | PASS   |
| SNMPV3_READ   | PASS   |
| SNMPV3_WRITE  | PASS   |
| NTP_SERVER    | PASS   |
| PING_CLIENT   | PASS   |
| TELNET_CLIENT | PASS   |
| SSH_CLIENT    | PASS   |
| TFTP_CLIENT   | PASS   |
| FTP_CLIENT    | PASS   |
| HTTP_CLIENT   | PASS   |
| HTTPS_CLIENT  | PASS   |
| SNMPV2_TRAP   | PASS   |
| SNMPV3_TRAP   | PASS   |
| NTP_CLIENT    | PASS*   |
| SYSLOG_CLIENT | PASS   |

### IPv6 Test Results
|     Test      | Result | 
|---------------|--------|
| PING_SERVER   | PASS   |
| TELNET_SERVER | PASS   |
| SSH_SERVER    | PASS   |
| SCP_SERVER    | PASS   |
| TFTP_SERVER   | PASS   |
| HTTP_SERVER   | PASS   |
| HTTPS_SERVER  | PASS   |
| SNMPV2_READ   | PASS   |
| SNMPV2_WRITE  | PASS   |
| SNMPV3_READ   | PASS   |
| SNMPV3_WRITE  | PASS   |
| NTP_SERVER    | PASS   |
| PING_CLIENT   | PASS   |
| TELNET_CLIENT | PASS   |
| SSH_CLIENT    | PASS   |
| TFTP_CLIENT   | PASS   |
| FTP_CLIENT    | PASS   |
| HTTP_CLIENT   | PASS   |
| HTTPS_CLIENT  | PASS   |
| SNMPV2_TRAP   | PASS   |
| SNMPV3_TRAP   | PASS   |
| NTP_CLIENT    | PASS*   |
| SYSLOG_CLIENT | PASS   |

*The NTP_CLIENT test may time out before NTP clocks are synchronized, causing the test to fail. This can be prevented if the clock is manually set to the current time before the test runs.
