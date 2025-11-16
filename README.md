# Privacy Policy for Role Reactor.
Last Updated: 16/11/2025

This document explains what data Role Reactor ("the Bot") collects, why it collects it, and how that data is stored and used.

## 1. What Data We Collect
We only collect and store data that is essential for the Bot's features to work.

### Data We Store:
⦁	Server (Guild) Settings: When an administrator uses the /setup command, we store the guild_id, the specified role_id, and the emoji.
⦁	Bot Owner Settings: When the Bot Owner uses the /globalreact command, we store the Bot Owner's user_id and the specified emoji.

### Data We Do Not Store:
⦁	We do not store any message content, message history, or user messages from any server.
⦁	We do not store any other information about users, roles, or channels.
⦁	The "keep-alive" web server used for hosting does not log or store any user data or IP addresses.

### Data We See (but do not store):
⦁	The Bot reads messages in channels to check the author's ID and role list. This information is processed in memory and is never saved to our database.
⦁	When the Bot joins a new server, it DMs the Bot Owner with the new server's name, ID, and total server count for administrative purposes. This information is not stored in the database.

## 2. Why We Collect Data (Purpose)
Server Settings (guild_id, role_id, emoji) are used to know which role to watch for and what to react with in a specific server.
Bot Owner Settings (user_id, emoji) are used to provide the global reaction feature for the Bot Owner.

## 3. Data Storage and Security
All stored data is kept in a secure Postgres database hosted by Render. We take reasonable measures to protect this data, but no service is 100% secure.

## 4. Data Sharing
We do not sell, trade, or share your data with any third parties. The data we collect is used only for the Bot's core functionality.

## 5. Data Retention & Deletion
Server Settings are retained in the database as long as the Bot is in your server. This data may be retained for a short period after the bot is kicked.
Bot Owner Settings are retained until they are cleared with the /stopglobalreact command.
You can request the permanent deletion of your server's or user's data at any time by contacting us.

## 6. Contact
If you have any questions about this Privacy Policy or wish to request data deletion, please contact us at Discord: lemonade6767.
