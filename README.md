# 🛡️ SCR4WP Shield v3.2.1

## ⚡ Advanced Linux Privacy & OPSEC Security Framework

SCR4WP Shield is a Linux security automation framework designed for
privacy control, network hardening and defensive security operations.

It provides two security profiles:

-   🔴 NORMAL MODE --- Standard network operation
-   🟢 OPSEC MODE --- Hardened privacy and security profile

------------------------------------------------------------------------

# 🚀 Features

## 🕵️ OPSEC Mode

When enabled:

-   🧅 Tor SOCKS routing
-   🔐 DNS leak protection
-   🔒 DNS lock enforcement
-   🔥 nftables firewall protection
-   🛑 Kill-switch validation
-   🌐 IPv6 leak checks
-   ✅ Automated verification

## 🌐 NORMAL Mode

Restores:

-   Normal internet access
-   Standard DNS routing
-   Non-Tor operation
-   Normal firewall state

All changes are reversible.

------------------------------------------------------------------------

# 📦 Installation

Requirements:

-   Linux
-   systemd
-   nftables
-   systemd-resolved
-   Tor

## Install:

``` bash
sudo cp scr4wp-shield /usr/local/sbin/scr4wp-shield
sudo chmod +x /usr/local/sbin/scr4wp-shield
```

Check:

``` bash
sudo scr4wp-shield status
```

## Uninstall

Remove SCR4WP Shield:

```bash
sudo rm -f /usr/local/sbin/scr4wp-shield
sudo rm -rf /var/lib/scr4wp-shield
sudo rm -rf /etc/scr4wp-shield
```

---

# ⚡ Usage

## Enable OPSEC

```bash
sudo scr4wp-shield opsec
```

Verify:

```bash
sudo scr4wp-shield verify
```

## Return NORMAL

``` bash
sudo scr4wp-shield normal
```

## Diagnostics

``` bash
sudo scr4wp-shield doctor
```

## Integrity Check

``` bash
sudo scr4wp-shield integrity
```

## Security Score

``` bash
sudo scr4wp-shield score
```

## Reports

``` bash
sudo scr4wp-shield report
sudo scr4wp-shield report --json
```

## Snapshot

``` bash
sudo scr4wp-shield snapshot
```

------------------------------------------------------------------------

# 📊 Security Score

SCR4WP evaluates:

    🧅 TOR             +20
    🔐 DNS LOCK        +20
    🔥 NFT FIREWALL    +20
    🛑 KILLSWITCH      +15
    👁 WATCHDOG        +10
    🧬 INTEGRITY       +10
    ✅ VERIFY           +5

    🏆 MAX SCORE       100/100

------------------------------------------------------------------------

# 🧠 Security Engine

Includes:

-   Automatic backups
-   Audit logging
-   SHA256 integrity verification
-   Health diagnostics
-   Security scoring
-   JSON reporting

------------------------------------------------------------------------

# 🧪 Tested Environment

-   Kali Linux
-   Linux Kernel 7.x
-   systemd
-   nftables
-   Tor
-   systemd-resolved

------------------------------------------------------------------------

# 🎯 Project Goals

-   Defensive security
-   Privacy engineering
-   Network automation
-   Safe reversible changes
-   Minimal dependencies

------------------------------------------------------------------------

# ⚠️ Disclaimer

This project is intended for legitimate privacy protection, defensive
security research, authorized penetration testing and Linux system
administration.

------------------------------------------------------------------------

# 📜 License

GNU General Public License v3.0

SCR4WP Shield is licensed under the GPL-3.0 license.

See the [LICENSE](LICENSE) file for details.

------------------------------------------------------------------------

# 🏷️ Release

SCR4WP Shield v3.2.1 — Watchdog Bug Fix
