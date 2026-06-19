# ParentControl v2.2

**Real-Time Device Monitoring and Management Solution**

[![Version](https://img.shields.io/badge/Version-2.2-blue)](https://github.com/InsideADM/Parent-Control/)
[![Android](https://img.shields.io/badge/Android-9.0%2B-green)](https://github.com/InsideADM/Parent-Control/)
[![License](https://img.shields.io/badge/License-Proprietary-red)](LICENSE.md)
[![Status](https://img.shields.io/badge/Status-Active-success)](https://github.com/InsideADM/Parent-Control/)

**Table of Contents**
- [Overview](#overview)
- [Core Capabilities](#core-capabilities)
- [Control Interfaces](#control-interfaces)
- [System Requirements](#system-requirements)
- [Licensing](#licensing-and-pricing)
- [Installation](#installation-and-setup)
- [Features](#features-by-version)
- [Security](#security-and-privacy)
- [Legal](#legal-compliance)
- [Support](#support-and-service)
- [Purchase](#purchase-and-licensing)
- [Contact](#contact-information)

---

## Overview

ParentControl is a professional device monitoring and management platform designed for parents, organizations, and authorized personnel who need to oversee Android devices. The solution provides comprehensive real-time visibility through two integrated control interfaces: a Telegram-based command system and a web-based management dashboard.

Whether you are a parent monitoring your child's device, an organization managing employee devices, or an IT administrator overseeing multiple devices, ParentControl delivers the monitoring capabilities you need with a straightforward, non-intrusive architecture.

---

## Core Capabilities

### Device Status and Intelligence

- Real-time battery level, network connectivity, and storage information
- GPS location tracking with historical location data
- Device application inventory and system information
- Automated alerts for critical device events

### Surveillance and Recording

- Screenshot capture with configurable frequency
- Front and rear camera photo and video capture
- Ambient audio recording (up to 120 seconds)
- Continuous keystroke monitoring across all applications

### Communications Monitoring

- Incoming and outgoing SMS message review
- Call history and log analysis with timestamps
- Contact list export and management
- Clipboard content monitoring in real-time

### Application Management

- Application usage tracking and time-spent analytics
- App installation and uninstallation monitoring
- Selective application blocking with whitelist/blacklist control
- Global block management override functionality

### Security and Device Control

- Remote device locking with PIN authentication
- PIN creation, modification, and enforcement
- Emergency force unlock capability
- Scheduled automatic locking (bedtime mode, study hours)
- Device Owner mode for maximum control

### Administrative Features

- Multi-administrator support (up to 10 authorized users)
- Command audit logging with timestamps
- Emergency contact number configuration
- Session management and security controls

---

## Control Interfaces

### Command-Line Interface (Telegram Bot)

The Telegram bot provides a lightweight, always-available command interface for remote device management:

```
/status              Display device metrics and connectivity
/screenshot          Capture current device screen
/backcam             Obtain rear camera photograph
/record [duration]   Record ambient audio
/location            Retrieve current GPS coordinates
/lock                Initiate remote device lock
/setpin [PIN]        Configure device unlock PIN
/block [package]     Block specified application
/unblock [package]   Remove application block
/help                Display available commands
```

**Advantages:**
- Accessible from any device with Telegram installed
- Commands queue during connectivity gaps
- Instant push notifications for critical alerts
- No additional software installation required

### Web Management Dashboard

A comprehensive browser-based control panel for detailed monitoring and analysis:

- Device status overview with real-time metrics
- Screenshot gallery with chronological organization
- Complete activity timeline with action timestamps
- SMS, call, and contact data export functionality
- Usage analytics with visual charts and breakdowns
- Command execution history with status tracking
- Administrative settings and user management

**Advantages:**
- Detailed data visualization and reporting
- Multi-device management from single interface
- No client-side installation necessary
- Responsive design for desktop and mobile browsers
- Comprehensive data export capabilities

---

## System Requirements

| Requirement | Specification |
|-------------|---|
| Target Device | Android 9.0 or later |
| Control Devices | Any device with Telegram or web browser |
| Network | Internet connectivity (WiFi or cellular) |
| Permissions | Accessibility Service, Device Administration |

---

## Licensing and Pricing

ParentControl is a licensed software product. Each license covers installation on a specified number of devices.

### License Options

| License Type | Price | Devices | Support | Usage |
|---|---|---|---|---|
| **Single Device** | $49 USD | 1 | 12 months | Lifetime |
| **Family Pack** | $199 USD | Up to 5 | 12 months | Lifetime |
| **Enterprise** | Custom | 10+ | Custom | Lifetime |
| **Source Code** | Custom | Unlimited | Custom | Unlimited |

**Inclusions:**
- Full-featured APK installation
- Telegram bot setup and configuration
- Web dashboard access
- Technical support during support period
- Lifetime software updates

All licenses include one year of complimentary technical support and software updates.

---

## Installation and Setup

Installation requires four essential steps:

1. **APK Installation** - Install the provided signed APK on target device
2. **Permission Configuration** - Grant Accessibility Service and Device Admin permissions
3. **Bot Configuration** - Connect target device to pre-configured Telegram bot
4. **Dashboard Access** - Log in to web dashboard with provided credentials

Complete setup typically requires 5-10 minutes per device. Detailed setup documentation is provided to licensed customers.

---

## Features by Version

### Version 2.2 (Current)

- Added `/about`, `/github`, and `/community` commands
- Resolved `/setdevnumber` command reliability
- Optimized lockscreen overlay performance (20% improvement)
- Implemented optional anti-tampering protection
- Fixed Android 14+ compatibility issues

### Version 2.1

- Implemented lockscreen overlay with PIN protection
- Added camera recording functionality (video and audio)
- Improved callback handling reliability
- Enhanced battery consumption optimization

### Version 2.0

- Firebase Realtime Database integration
- Multi-device synchronization
- Application blocking engine implementation
- Usage tracking and analytics system
- Web dashboard redesign

### Version 1.5

- Keystroke monitoring system
- Automated screenshot scheduling
- Bedtime lock scheduler

### Version 1.0

- Initial release with core command set
- SMS and call log reading
- GPS location tracking

---

## Security and Privacy

### Data Protection Measures

- All data collection occurs locally on target device
- No data transfer to external servers (except Telegram commands)
- End-to-end encryption for Telegram communications
- Local database encryption for sensitive information
- No third-party data sharing

### User Responsibilities

- Licensee maintains responsibility for data security
- Automatic backups recommended
- Credentials and authentication data must be protected
- Compliance with applicable data protection regulations required

### Privacy Statement

We do not:
- Collect usage analytics from target devices
- Serve advertisements
- Sell or share monitoring data
- Track Telegram commands or device locations
- Maintain logs beyond customer support requirements

---

## Legal Compliance

ParentControl is designed for lawful use only, including:

- Parents monitoring devices assigned to their children
- Employers monitoring company-owned devices with employee consent
- Device owners monitoring their own devices
- Authorized personnel in legal recovery scenarios

Licensee is solely responsible for:

- Obtaining proper authorization from monitored device owners
- Complying with surveillance and privacy laws in their jurisdiction
- Understanding and adhering to local regulations

**Prohibited uses** include stalking, hacking, unauthorized surveillance, and any activity violating applicable law.

---

## Support and Service

### Support Availability

| Channel | Contact | Response Time |
|---|---|---|
| Email | admofficialhq@gmail.com | 24 hours |
| Telegram | @Iam_Bravo1 | 4 hours average |

**Operating Hours:** Monday-Friday 10 AM - 8 PM EAT, Saturday 2 PM - 6 PM EAT

### Support Coverage

**Included support provides:**
- Installation and configuration assistance
- Technical troubleshooting and bug fixes
- Software updates and patches
- Command and feature guidance

**Not included:**
- Custom application development
- Legal or regulatory consultation
- Device data recovery services

### Support Duration

- 12 months complimentary with license purchase
- Extended support available for enterprise customers
- Post-support updates available for additional fee

---

## Purchase and Licensing

To acquire ParentControl:

1. Contact the licensing department with your requirements
2. Specify device count and license type
3. Receive invoice and payment instructions
4. Complete payment through preferred method
5. Receive APK, credentials, and setup documentation

### Payment Methods

- Wire transfer (international and Uganda)
- Mobile money (MTN, Airtel - Uganda)
- Cryptocurrency (BTC, USDT)
- PayPal (international)

### Refund Policy

- Full refund within 7 days of purchase
- After 7 days, no refunds issued
- Support and updates remain available after refund period

---

## Contact Information

| Information | Details |
|---|---|
| Developer | Ibrahim |
| Company | iBT Labs / ADM |
| Location | Kampala, Uganda |
| Email | admofficialhq@gmail.com |
| Telegram | @Iam_Bravo1 |
| Community | https://t.me/+zTvA2cigWowyMGQ0 |
| GitHub | https://github.com/InsideADM |

---

## Legal Notice

ParentControl is provided "as is" without warranty of any kind. Licensor assumes no liability for damages, data loss, or legal consequences resulting from use of this software.

By installing or using ParentControl, you agree to comply with all applicable laws and accept full responsibility for your use of this software.

For complete license terms, see [LICENSE.md](LICENSE.md)

---

Copyright © 2026 ADM. All rights reserved.
