# Redmi AX5 (RA67) OpenWrt with Wi-Fi

This repository automatically builds custom OpenWrt firmware with **2.4G & 5G Wi-Fi 6** (ath11k) for **Redmi AX5 (RA67 / IPQ6018)**.

## Features
- **Wi-Fi 6 Enabled**: Includes `ipq-wifi-redmi_ax5` and `kmod-ath11k-ahb` drivers.
- **NSS / PPE Hardware Acceleration**: Fast gigabit packet routing.
- **ZRAM Swap Optimized**: Pre-configured zram compressed swap to prevent Out-Of-Memory (OOM) on 256MB RAM.
- **Clean & Fast**: Lightweight LuCI base system.

## How to build
Go to **Actions** -> **Build OpenWrt for Redmi AX5** -> **Run workflow**.
