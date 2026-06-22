# Day 12 - Networking Fundamentals 🌐

## Overview

Today I started learning Networking for DevOps. I learned how devices communicate over a network, how IP addresses work, how DNS resolves domain names, and how to troubleshoot basic network issues using Linux commands.

---

## Topics Covered

- IP Address
- Public IP vs Private IP
- Gateway
- Ping
- ICMP
- TCP vs UDP
- Common Ports
- DNS
- nslookup
- host
- dig
- Network Troubleshooting

---

## IP Address

An IP address uniquely identifies a device on a network.

Example:

192.168.1.10

---

## Private IP Address

Used inside local networks.

Examples:

- 192.168.x.x
- 10.x.x.x
- 172.16.x.x - 172.31.x.x

Check:

```bash
ip a
```

---

## Public IP Address

Used on the Internet.

Check:

```bash
curl ifconfig.me
```

---

## Gateway

Gateway is the router through which traffic leaves the local network.

Check:

```bash
ip route
```

Example:

```text
default via 172.19.192.1 dev wlo1
```

---

## Ping

Used to test connectivity.

```bash
ping google.com
```

---

## ICMP

Full Form:

```text
Internet Control Message Protocol
```

Used by:

```bash
ping
```

---

## TCP vs UDP

### TCP

- Reliable
- Connection Oriented
- Uses Acknowledgements

Examples:

- SSH
- HTTP
- HTTPS

### UDP

- Fast
- Connectionless
- No Acknowledgements

Examples:

- DNS
- Gaming
- Streaming

---

## Important Ports

| Port | Service |
|--------|---------|
| 22 | SSH |
| 80 | HTTP |
| 443 | HTTPS |
| 53 | DNS |
| 3306 | MySQL |
| 5432 | PostgreSQL |

---

## DNS

DNS converts domain names into IP addresses.

Example:

```text
github.com
↓
20.207.73.82
```

---

## DNS Commands

### nslookup

```bash
nslookup github.com
```

### host

```bash
host github.com
```

### dig

```bash
dig github.com
```

---

## Network Troubleshooting

### Check Internet

```bash
ping 8.8.8.8
```

### Check DNS

```bash
nslookup github.com
```

### Check Website

```bash
curl -I https://github.com
```

---

## Commands Practiced

```bash
ip a

ip route

curl ifconfig.me

ping google.com

nslookup github.com

host github.com

dig github.com
```

---

## Key Learnings

✅ IP Address

✅ Public IP

✅ Private IP

✅ Gateway

✅ Ping

✅ ICMP

✅ TCP

✅ UDP

✅ Ports

✅ DNS

✅ nslookup

✅ host

✅ dig

✅ Basic Network Troubleshooting

---

## Learning Summary

Today I learned networking fundamentals required for DevOps. I practiced finding IP addresses, identifying gateways, understanding TCP and UDP, learning common ports, and using DNS tools such as nslookup, host, and dig for troubleshooting network-related issues.

# Day 12 Complete 🚀
