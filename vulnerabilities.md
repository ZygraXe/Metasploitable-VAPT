## Vulnerability Name
VSFTPD 2.3.4 Backdoor

## Severity
Critical

## Description
VSFTPD version 2.3.4 contains a backdoor that allows unauthenticated remote command execution.

## Impact
An attacker can gain shell access without valid credentials.

## Exploitation
Metasploit module: exploit/unix/ftp/vsftpd_234_backdoor

## Mitigation
- Update FTP service
- Disable unnecessary FTP access
- Apply firewall rules
