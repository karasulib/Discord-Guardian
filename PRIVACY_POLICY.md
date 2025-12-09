# Discord Guild Shiled Bot - Privacy Policy

**Last Updated:** December 9, 2025

## Introduction

Discord Guard Bot ("we", "our", "the bot") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and protect information when you use our Discord bot.

## Data Collection

### What Data We Collect

The bot collects and processes the following types of data:

1. **Guild Information**
   - Guild ID
   - Guild name
   - Security settings and preferences

2. **User Information (Temporary)**
   - User ID
   - Account creation date (for threat analysis)
   - Join timestamp (for raid detection)
   - Message count (for spam detection)

3. **Action Logs**
   - Moderation actions (bans, kicks, timeouts)
   - Timestamps
   - Reasons for actions
   - Suspicion scores

### What We Do NOT Collect

- **Message Content**: Messages are processed in real-time for security purposes but are NOT stored
- **Personal Information**: We do not collect names, emails, or any personally identifiable information beyond Discord IDs
- **Private Messages**: The bot does not access or store private messages

## How We Use Your Data

### Security & Moderation

- **Threat Detection**: Analyze user behavior to detect spam, raids, and nuke attacks
- **Rate Limiting**: Track message frequency to prevent spam
- **Automated Moderation**: Take action against malicious users based on detected threats
- **Audit Logging**: Maintain records of moderation actions for server administrators

### Data Storage

- **PostgreSQL Database**: Permanent storage of guild settings, action logs, and rules
- **Redis Cache**: Temporary storage of rate limits, counters, and suspicion scores
  - All cached data has automatic expiration (TTL)
  - Typical expiration: 10-60 seconds for counters, up to 5 minutes for settings cache

## Data Retention

- **Guild Settings**: Retained as long as the bot is in your server
- **Action Logs**: Retained for audit purposes (configurable per guild)
- **Temporary Data**: Automatically deleted after expiration (10-60 seconds)
- **Upon Bot Removal**: All guild-specific data is deleted from our systems

## Data Sharing

We do NOT:
- Sell your data to third parties
- Share data with advertisers
- Use data for AI/ML training
- Share data outside of security and moderation purposes

## Your Rights

### Server Administrators

- **Access**: View all stored data through the bot's dashboard (coming soon)
- **Deletion**: Remove the bot to delete all associated data
- **Configuration**: Control which features are enabled and what data is collected

### Individual Users

- **Opt-Out**: Contact your server administrator to disable specific features
- **Data Access**: Request information about stored data through your server administrator

## Security Measures

- **Encryption**: All data in transit is encrypted (HTTPS/TLS)
- **Access Control**: Data is only accessible to authorized bot processes
- **Regular Cleanup**: Automatic deletion of expired temporary data
- **Secure Storage**: Database and cache are hosted on secure, compliant platforms

## Third-Party Services

The bot uses the following third-party services:

- **Discord API**: For bot functionality
- **PostgreSQL** (Railway): For data storage
- **Redis** (Upstash): For caching and rate limiting

These services have their own privacy policies and security measures.

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify users of significant changes by:
- Updating the "Last Updated" date
- Posting a notice in our support server
- Updating the bot's help command


## Compliance

This bot complies with:
- Discord's Terms of Service
- Discord's Developer Policy
- GDPR (for EU users)
- General data protection best practices

## Data Deletion Request

To request deletion of your data:

1. Remove the bot from your server (this automatically triggers data deletion)
2. Contact us through GitHub Issues or support channels
3. Provide your Guild ID for verification

We will process deletion requests within 30 days.

---

**By using Discord Guard Bot, you agree to this Privacy Policy.**

