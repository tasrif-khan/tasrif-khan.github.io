# Privacy Policy

**Last updated: April 26, 2026**

This Privacy Policy describes what data the Scheduler Bot ("the Bot")
collects, why it's collected, how it's used, and your rights regarding it.

## 1. Data we collect

The Bot stores only the data required to deliver scheduled messages.
Specifically:

**Server (guild) data:**
- Server (guild) ID
- Channel IDs where schedules are configured to post
- Role IDs that have been granted scheduling permissions
- The server's configured timezone
- Whether the server has completed initial onboarding

**Schedule data:**
- The text content of scheduled messages
- Uploaded image attachments (stored as files on disk)
- Schedule configuration: timing, intervals, target times, variant settings,
  embed settings, max-fire limits
- Role IDs and user IDs configured to receive pings
- The Discord user ID of the schedule creator
- Timestamps of when schedules were created, last fired, and are next due
- Counts of how many times each schedule has fired

**What we do NOT collect:**
- Message content from anywhere except messages explicitly configured by
  server admins as scheduled posts
- Member lists, presence data, voice activity, or any other server activity
- Direct messages
- User profile information beyond IDs needed for ping delivery
- IP addresses or device identifiers
- Analytics or telemetry of any kind

The Bot does not request privileged Discord intents (Message Content, Server
Members, Presence). It cannot read regular messages in your server.

## 2. How we use your data

Collected data is used solely to:

- Deliver scheduled messages at their configured times
- Display schedule lists, previews, and configuration to authorized users
- Persist your configuration across restarts
- Validate permissions for managing schedules

We do not sell, trade, or share collected data with third parties. We do not
use your data for advertising, profiling, training AI models, or any purpose
beyond delivering the Bot's stated functionality.

## 3. Data storage and security

Data is stored locally on the server hosting the Bot, in a SQLite database
and a directory of uploaded images. The Bot does not transmit your data to
external services other than Discord itself (which is required to deliver
the scheduled messages).

Reasonable measures are taken to protect data against unauthorized access,
but no system is 100% secure. You acknowledge this when using the Bot.

## 4. Data retention

- **Active schedules:** retained until cancelled by an authorized user.
- **Cancelled schedules:** schedule data and associated images are deleted
  immediately on cancellation.
- **Server data:** retained while the Bot is in your server. When the Bot
  is removed from a server, residual configuration data (configurator roles,
  timezone, onboarding flag) may persist until manually purged.
- **No backups are retained beyond what's needed for operational continuity.**

To request deletion of all data associated with your server, remove the Bot
from your server and contact the developers.

## 5. Your rights

You have the right to:

- Request a list of data the Bot stores about your server
- Request correction of any inaccurate data
- Request deletion of all data associated with your server
- Stop using the Bot at any time by removing it from your server

To exercise any of these rights, contact the developers via the support
channel listed in the Discord Developer Portal listing.

## 6. Children's privacy

The Bot is not intended for users under 13 (or the minimum age required to
use Discord in your country, whichever is higher). We do not knowingly
collect data from children below this age.

## 7. Third parties

The Bot interacts only with Discord's API. Discord's own privacy practices
are governed by [Discord's Privacy Policy](https://discord.com/privacy).
The Bot does not use third-party analytics, advertising networks, or
tracking services.

## 8. Changes to this policy

This Privacy Policy may be updated periodically. The "Last updated" date at
the top of this document reflects the most recent changes. Significant
changes will be announced via the Bot's support server or developer portal
listing where reasonably possible.

## 9. Contact

For privacy questions, data requests, or concerns, contact the developers
via the support channel listed in the Discord Developer Portal listing.
