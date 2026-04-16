# Terms of Service — Imposter Detector

**Last updated:** April 16, 2026

## 1. Acceptance of Terms

By adding Imposter Detector to your Discord server, you agree to these terms.

## 2. Service Description

Imposter Detector is a Discord bot that detects potential impersonation attempts by comparing member profiles (usernames, display names, avatars) against a list of protected members configured by server administrators.

## 3. Data Collection

The bot collects and stores:
- **Server IDs** and configuration settings (channels, thresholds)
- **User IDs** of protected and whitelisted members
- **Detection logs** including user IDs, similarity scores, and actions taken
- **Avatar images** are processed in memory for comparison but are **not stored**

The bot does **not** collect:
- Message content
- Voice data
- DM content
- Any data from servers where the bot is not installed

## 4. Data Usage

All collected data is used solely for the purpose of detecting and preventing impersonation. Data is never sold, shared with third parties, or used for advertising.

## 5. Data Retention

- Detection logs are retained indefinitely for audit purposes
- Server configuration is deleted when the bot is removed from a server
- Users can request data deletion by contacting the bot developer

## 6. User Responsibilities

Server administrators are responsible for:
- Configuring the bot appropriately for their server
- Reviewing detection alerts before taking action
- Ensuring auto-kick/ban settings are appropriate for their community

## 7. Limitation of Liability

Imposter Detector is provided "as is" without warranty. The developer is not liable for any incorrect detections, wrongful kicks/bans, or other actions taken by the bot.

## 8. Changes to Terms

These terms may be updated at any time. Continued use of the bot constitutes acceptance of updated terms.

## 9. Contact

For questions or data deletion requests, open an issue on the [GitHub repository](https://github.com/cmartin81/imposterDetector).
