# Auto Moderation

**Description:**\
Automates spam management by warning, muting, kicking, or banning users based on spam thresholds. Supports verbose logging and message removal.

**Inputs:**

* Is enabled?
* Warn threshold
* Mute threshold
* Kick threshold
* Ban threshold
* Unmute time (minutes)
* Verbose logging?
* Remove messages?
* Warn message
* Mute message
* Kick message
* Ban message

**Behaviour:**\
Checks messages in guilds for spam and applies actions when thresholds are met. Warns, mutes, kicks, or bans users based on counts. Optionally removes spam messages. Ignores administrators. Emits moderation actions according to specified configured messages.
