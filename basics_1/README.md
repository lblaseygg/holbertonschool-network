# Network Basics 1

This directory contains scripts for basic network operations and configurations.

## Scripts

### 0-change_your_home_IP
A script that modifies the `/etc/hosts` file to:
- Change localhost to resolve to 127.0.0.2
- Change facebook.com to resolve to 8.8.8.8

Usage:
```bash
sudo ./0-change_your_home_IP
```

### 1-show_attached_IPs
A script that displays all active IPv4 IPs on the machine.

Usage:
```bash
./1-show_attached_IPs
```

Example output:
```
10.0.2.15
127.0.0.1
```

### 2-port_listening_on_localhost
A script that listens on port 98 on localhost for incoming connections.

Usage:
```bash
# Terminal 1
sudo ./2-port_listening_on_localhost

# Terminal 2
telnet localhost 98
```

## Requirements
- All scripts must be executable
- Scripts must be run on Ubuntu 22.04
- Some scripts require sudo privileges
- All scripts start with `#!/usr/bin/env bash`
- All scripts include a comment explaining their purpose 