# Privacy Policy — Imposter Detector

**Last updated:** April 16, 2026

## What data we collect

| Data | Purpose | Stored? |
|---|---|---|
| Server ID | Identify your server's configuration | ✅ Yes |
| Channel IDs | Send alerts to the right channels | ✅ Yes |
| User IDs (protected/whitelisted) | Know who to protect and who to skip | ✅ Yes |
| Detection logs (user IDs + scores) | Audit trail for moderation actions | ✅ Yes |
| Avatar images | Compare for impersonation | ❌ Processed in memory only |
| Usernames & display names | Compare for similarity | ✅ In detection logs |

## What we do NOT collect

- ❌ Message content
- ❌ Voice or video data
- ❌ DM conversations
- ❌ Data from servers where the bot is not installed
- ❌ IP addresses or location data

## How we use your data

All data is used **exclusively** for detecting impersonation attempts. We do not:
- Sell data to third parties
- Use data for advertising
- Share data with anyone outside the bot's functionality

## Data storage

Data is stored in a secure PostgreSQL database. Access is limited to the bot developer.

## Data deletion

- **Remove the bot** from your server to stop all data collection
- Server configuration is retained after removal in case you re-add the bot
- To request full data deletion, open an issue on the [GitHub repository](https://github.com/cmartin81/imposterDetector) or contact the developer

## Children's privacy

Imposter Detector does not knowingly collect data from children under 13. The bot operates within Discord's own age-restricted platform.

## Changes to this policy

This policy may be updated at any time. Changes will be reflected in the "Last updated" date above.

## Contact

For privacy questions or data deletion requests, open an issue on [GitHub](https://github.com/cmartin81/imposterDetector).
