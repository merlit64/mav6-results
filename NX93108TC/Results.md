## NX93108TC
- Part Number: N9K-C93108TC-FX
- OS: NXOS
- Software Version: 9.3(1)
### IPv4 Test Results
|     Test      | Result | 
|---------------|--------|
| PING_SERVER   | PASS   |
| TELNET_SERVER | PASS   |
| SSH_SERVER    | PASS   |
| SCP_SERVER    | PASS   |
| TFTP_SERVER   | N/A   |
| HTTP_SERVER   | N/A   |
| HTTPS_SERVER  | N/A   |
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
| HTTPS_CLIENT  | N/A   |
| SNMPV2_TRAP   | PASS   |
| SNMPV3_TRAP   | PASS   |
| NTP_CLIENT    | PASS*   |
| SYSLOG_CLIENT | FAIL   |

### IPv6 Test Results
|     Test      | Result | 
|---------------|--------|
| PING_SERVER   | PASS   |
| TELNET_SERVER | PASS   |
| SSH_SERVER    | PASS   |
| SCP_SERVER    | PASS   |
| TFTP_SERVER   | N/A   |
| HTTP_SERVER   | N/A   |
| HTTPS_SERVER  | N/A   |
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
| HTTPS_CLIENT  | N/A   |
| SNMPV2_TRAP   | PASS   |
| SNMPV3_TRAP   | PASS   |
| NTP_CLIENT    | PASS*   |
| SYSLOG_CLIENT | PASS   |

*The NTP_CLIENT test may time out before NTP clocks are synchronized, causing the test to fail. This can be prevented if the clock is manually set to the current time before the test runs.
