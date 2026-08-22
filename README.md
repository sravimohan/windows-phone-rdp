# Windows Phone RDP

A practical guide to installing the old Microsoft Remote Desktop client on Windows 10 Mobile and using it to connect to Windows 11 Pro.

**Tested on:**
- Nokia Lumia 1520
- Windows 10 Mobile 1607
- OS build `10.0.14393.2551`
- ARM32
- Microsoft Remote Desktop `8.1.9.17`
- Windows 11 Pro host

## Published guide

Once GitHub Pages is enabled for this repository:

**https://sravimohan.github.io/windows-phone-rdp/**

## Key package

```text
Microsoft.RemoteDesktop_8.1.9.17_arm__8wekyb3d8bbwe.appx
```

Microsoft Store Product ID:

```text
9WZDNCRFJ3PS
```

Expected SHA-1:

```text
7a27f3a0dd09abdcd59a58d96acb793a1ed0df8d
```

The guide explains how to locate the archived package, verify that the actual APPX download comes from Microsoft's `delivery.mp.microsoft.com` infrastructure, sideload it with Windows Device Portal, and handle Windows Hello / Microsoft-account RDP authentication.

## GitHub Pages

In the repository:

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**.
4. Save.

The site should then be available at:

**https://sravimohan.github.io/windows-phone-rdp/**

## Scope

This procedure was tested on a Lumia 1520. Other ARM Windows Phone / Windows 10 Mobile devices may work, but are not claimed as tested.
