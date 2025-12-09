<div align="center">

<br>

```
 ██████╗  █████╗ ████████╗███████╗
██╔════╝ ██╔══██╗╚══██╔══╝██╔════╝
██║  ███╗███████║   ██║   █████╗  
██║   ██║██╔══██║   ██║   ██╔══╝  
╚██████╔╝██║  ██║   ██║   ███████╗
 ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚══════╝
███████╗ ██████╗ █████╗ ███╗   ██╗
██╔════╝██╔════╝██╔══██╗████╗  ██║
███████╗██║     ███████║██╔██╗ ██║
╚════██║██║     ██╔══██║██║╚██╗██║
███████║╚██████╗██║  ██║██║ ╚████║
╚══════╝ ╚═════╝╚═╝  ╚═╝╚═╝  ╚═══╝
```

<br>

### Payment Gateway Reconnaissance Tool

Discover and analyze payment integrations across the web

<br>

[![Python](https://img.shields.io/badge/Python-3.8+-16161d?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/License-Private-16161d?style=flat-square)](LICENSE)
[![Discord](https://img.shields.io/badge/Discord-Join_Us-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/rgWcEw5G8a)
[![GitHub](https://img.shields.io/badge/GitHub-Repo-16161d?style=flat-square&logo=github&logoColor=white)](https://github.com/walterwhite-69/Gateway-Finder)

<br>

---

</div>

<br>

## About

Gate Scan is an advanced reconnaissance tool that leverages intelligent Google dorking and pattern matching to discover payment gateway integrations on websites. Built for speed and precision with asynchronous scanning capabilities.

<br>

## Features

| Feature | Description |
|:--------|:------------|
| **Smart Dorking** | Intelligent Google search patterns to find payment pages |
| **Multi-Gateway Detection** | Identifies 15+ payment processors with regex matching |
| **Async Scanning** | High-speed concurrent requests for faster results |
| **Rich CLI** | Beautiful terminal interface with progress indicators |
| **License System** | Secure HWID-bound licensing for authorized access |

<br>

## Supported Gateways

<div align="center">

| Payment Processor | Detection Status |
|:------------------|:----------------:|
| Stripe | Active |
| PayPal | Active |
| Braintree | Active |
| Square | Active |
| Shopify Payments | Active |
| WooCommerce | Active |
| Coinbase Commerce | Active |
| Authorize.net | Active |
| Adyen | Active |
| Razorpay | Active |
| GoCardless | Active |
| Venmo | Active |
| Crypto Wallets | Active |

</div>

<br>

## Requirements

### System Requirements

- **Python** 3.8 or higher
- **Internet** Stable connection required
- **License** Valid license key from Discord

### Dependencies

Install all required packages:

```bash
pip install -r requirements.txt
```

#### Required Packages

| Package | Version | Purpose |
|:--------|:--------|:--------|
| `aiohttp` | Latest | Async HTTP client for fast web requests |
| `beautifulsoup4` | Latest | HTML parsing and content extraction |
| `fake-useragent` | Latest | User agent rotation to avoid detection |
| `rich` | Latest | Beautiful terminal output and progress bars |
| `libsql-client` | Latest | License validation and database connectivity |

<br>

## Installation

```bash
# Clone the repository
git clone https://github.com/walterwhite-69/Gateway-Finder.git

# Navigate to directory
cd Gateway-Finder

# Install dependencies
pip install aiohttp beautifulsoup4 fake-useragent rich libsql-client
```

<br>

## Usage

```bash
python scan.py
```

On first run, you will be prompted to enter your license key. The license is bound to your device and validated on each use.

<br>

## How It Works

```
1. License Validation    →    Verifies your access credentials
2. Dork Selection        →    Choose or randomize search patterns  
3. Google Search         →    Queries are sent to find payment pages
4. URL Extraction        →    Relevant URLs are collected
5. Gateway Detection     →    Each page is scanned for payment patterns
6. Results Display       →    Matched gateways shown with live keys
```

<br>

## License

This software requires a valid license key to operate.  
Licenses are distributed exclusively through our Discord server.

<br>

<div align="center">

---

<br>

**[Get Your License](https://discord.gg/rgWcEw5G8a)**

<br>

<sub>Built for reconnaissance professionals</sub>

</div>
