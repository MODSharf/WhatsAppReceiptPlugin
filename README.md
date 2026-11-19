# WhatsApp Receipt Plugin for Aronium POS

<img width="1366" height="730" alt="1Untitled" src="https://github.com/user-attachments/assets/6d577504-5719-44ba-aa98-1f6240c1fc42" />

**Deliver sales receipts to customers as PDF documents through WhatsApp.**

WhatsApp Receipt Plugin is an independent add-on for Aronium POS. It is intended to help participating stores deliver a copy of a sales receipt to a customer's WhatsApp number.

> **Release status:** Public download will be enabled only after the release package, installation procedure, compatibility, and security checks have been verified. Do not treat this repository template as a downloadable release.

## Demo

[Watch the product demo](https://youtu.be/ULREzw3dT6M)

## What it does

- Prepares a sales receipt as a PDF for WhatsApp delivery.
- Provides plugin settings for the store's WhatsApp integration.
- Supports the product's licensing workflow.

Feature availability depends on the published version. Refer to each release's notes.

## Download

[View all releases](https://github.com/MODSharf/WhatsAppReceiptPlugin/releases)

When a stable release is published, download the ZIP asset attached to the latest release. Do not download the repository source ZIP as an installer.

## Requirements

Confirm the exact supported versions before publishing a release:

- Aronium POS: **TO BE VERIFIED**
- Windows: **TO BE VERIFIED**
- .NET Framework/runtime requirements: **TO BE VERIFIED**
- WhatsApp Business Platform / Cloud API configuration: required for the supported API-based sending flow
- Store-owned WhatsApp Business assets and valid credentials

## Installation

See [Installation Guide](docs/INSTALLATION.md). The guide must be completed and tested against a clean Aronium installation before the first public release.

## WhatsApp setup and responsibility

Each store must use and manage its own WhatsApp Business assets, phone number, access credentials, customer consent, and compliance with applicable Meta policies and messaging fees. Never post access tokens, app secrets, phone-number IDs, customer phone numbers, or receipt PDFs in public issues.

## Support

- [Report a bug](https://github.com/MODSharf/WhatsAppReceiptPlugin/issues/new?template=bug_report.yml)
- [Request a feature](https://github.com/MODSharf/WhatsAppReceiptPlugin/issues/new?template=feature_request.yml)
- Before opening an issue, remove tokens, customer details, and other confidential information from logs and screenshots.

## Licensing and commercial use

This is an independently developed third-party add-on. Commercial licensing, redistribution, and reseller permissions are governed by the licence or agreement supplied with each release. **No open-source licence is granted by this repository unless a licence file is explicitly added.**

## Disclaimer

WhatsApp Receipt Plugin is not affiliated with, endorsed by, or officially supported by Aronium or Meta. Aronium and WhatsApp are trademarks of their respective owners.
