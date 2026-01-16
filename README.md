# Siemens TIA Portal Installation Guide (Windows)

This guide provides the required **prerequisites, system configurations, installation steps, download references, and license fixes** for installing **Siemens TIA Portal** successfully on Windows.

---

## Prerequisites

Before installing TIA Portal, download and install the following:

### 1. Visual C++ Redistributable (All-in-One)
- Package: Visual C++ Redistributable Runtimes All-in-One  
- Server: Closest to your location  
- Download Link:  
  https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/

### 2. .NET Framework 3.5 SP1
- Download Link:  
  https://dotnet.microsoft.com/en-us/download/dotnet-framework/net35-sp1

---

## Windows Configuration Settings

Apply the following settings **before installation**:

### Enable (.NET Framework 3.5)

1. Press **Windows + R**
2. Type: **optionalfeatures**
3. Press **Enter**
4. Check **.NET Framework 3.5 (includes .NET 2.0 and 3.0)**
5. Click **OK** and wait for Windows to complete the installation

### Disable (Temporarily)

Use **Windows Search** or **Settings** to locate the following:

- **Reputation-Based Protection**  
- Windows Security → App & browser control → Reputation-based protection settings

- **Core Isolation**  
- Windows Security → Device security → Core isolation → Memory integrity (OFF)

- **Virus & Threat Protection**  
- Windows Security → Virus & threat protection → Manage settings → Real-time protection (OFF)

- **Wi-Fi Connection**  
- Click the Wi-Fi icon in the system tray → Turn Wi-Fi OFF  
- (Recommended during installation)

>  These steps help prevent freezing, installation errors, and licensing issues.

---

## Installation Files

- TIA Portal Installation Video Guide (Google Drive):  
  https://drive.google.com/file/d/1vsY7MDwcIw4QTer8_qkcoe9N0aMV8jny/view?usp=sharing

**Download Password: plc4me.com**  


**Reference Website:**  
- https://plc4me.com

---

## Registry Path (If Required)

Check the following registry path if runtime or installation issues occur:


>  Modify registry values only if necessary and with caution.

---

##  Siemens License Fix

If Automation License Manager fails to detect licenses, follow this guide:

- License Fix Reference:  
  https://plc247.com/automation-license-manager-fix-siemens-license/

**Password: plc247.com**  


---

## Final Recommendations

- Always **run installers as Administrator**
- Temporarily disable antivirus and firewall
- Restart your PC after installation
- Re-enable security settings once installation is complete and verified

---

## Source Reference

This README is based on the provided installation document and related references.

