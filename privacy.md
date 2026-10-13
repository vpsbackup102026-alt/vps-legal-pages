# Privacy Policy

**Last updated: October 13, 2026**

## Introduction

This Privacy Policy describes how VPS Backup ("we", "our", or "the App") handles information when you use our service to back up Virtual Private Server (VPS) data to Google Drive.

## Information We Collect

The App accesses and stores the following data:

- **Google Account Information**: When you authorize the App via Google OAuth, we receive an access token to interact with your Google Drive.
- **Backup Files**: Server backup archives (`.tar.gz` files) generated on your VPS.
- **Server Metadata**: Configuration files, scripts, and logs related to the backup process.

## How We Use Information

The collected information is used solely for:

- Uploading backup archives to your personal Google Drive account.
- Rotating and managing old backups (30-day retention by default).
- Sending notifications via Telegram about backup status.

## Data Sharing

We do **not** share, sell, or transfer any data to third parties. All data remains in your own Google Drive account and your VPS server.

## Data Retention

- **Local backups**: Retained for 7 days on your VPS.
- **Google Drive backups**: Retained for 30 days.
- You can delete backups at any time from your Google Drive or VPS.

## Security

- All communication with Google APIs uses OAuth 2.0 with encrypted HTTPS connections.
- Access tokens are stored securely on your VPS with restricted file permissions (600).
- No data is transmitted to any external server other than Google Drive and Telegram.

## Third-Party Services

The App uses the following third-party services:

- **Google Drive API**: For uploading and managing backup files.
- **Telegram Bot API**: For sending backup status notifications.
- **rclone**: Open-source tool for cloud storage synchronization.

Each service has its own privacy policy:
- Google: https://policies.google.com/privacy
- Telegram: https://telegram.org/privacy

## Your Rights

You can revoke the App's access to your Google Drive at any time by visiting:
https://myaccount.google.com/permissions

## Contact

For questions about this Privacy Policy, contact:

**Email**: vpsbackup102026@gmail.com

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated date.
