# HTTP/2 Rapid Reset: CVE-2023-44487

## Description

This repository contains proof-of-concept (PoC) code for the HTTP/2 Rapid Reset vulnerability identified as CVE-2023-44487.

## Vulnerability Overview

- **CVE ID**: CVE-2023-44487
- **Impact**: Denial of Service (DoS)
- **Affected Protocols**: HTTP/2
- **Affected Components**: Web servers, Reverse Proxies, Load Balancers
- **Disclosure Date**: 2023-10-10


## Getting Started

### Prerequisites

- Python 3.x
- `hyper` 

Install prerequisites:

```bash
pip install hyper
```

### Usage

1. Clone the repository:

```bash
git clone https://github.com/imabee101/CVE-2023-44487.git
```

2. Navigate into the directory:

```bash
cd CVE-2023-44487
```

3. Execute the PoC:

```bash
python main.py
```



## References

- [Official CVE Record](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2023-44487)
- [Vendor Advisory](https://github.com/caddyserver/caddy/issues/5877)
- [Other Related Research](https://blog.cloudflare.com/technical-breakdown-http2-rapid-reset-ddos-attack/)

