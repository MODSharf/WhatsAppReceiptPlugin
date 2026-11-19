# Privacy and Security Notes

This document must be reviewed against the actual implementation before release. It is not a substitute for a formal privacy policy or legal advice.

## Store responsibilities

- Use the store's own WhatsApp Business assets and credentials.
- Obtain and retain any customer consent required for the chosen messaging flow.
- Follow applicable Meta policies and local privacy/data-protection laws.
- Protect access tokens and restrict access to the POS computer and configuration files.

## Never publish

- WhatsApp access tokens, app secrets, API keys, licence keys, or activation secrets.
- Customer names, phone numbers, receipt PDFs, or unredacted logs.
- Store database backups or real business data.

## Implementation review required before release

- Verify how credentials are stored, protected, masked, and cleared.
- Verify whether logs contain tokens, phone numbers, receipt content, or customer data.
- Verify network endpoints and TLS usage.
- Verify deletion/retention behavior for temporary PDF files.
- Provide a contact for private vulnerability reports: **TODO: security contact email**.
