# Reaction Listener

**Description:**\
Monitors reactions on a specified message and stores related data in variables. Supports persistent and temporary modes.

**Inputs:**

* Message
* Mode (Persistent, Temporary)
* Store reaction in variable
* Store member in variable
* Store user in variable
* Store channel in variable
* Store server in variable
* Emojis (list with option to auto-add to message)

**Outputs:**

* action
* \[Emoji] added
* \[Emoji] removed

**Variable Types:**

* Message
* User
* Member
* Channel
* Server
* Reaction

**Behaviour:**\
Listens for reactions added or removed on the specified message. For each monitored emoji, stores the reaction, member, user, channel, and server in the selected variables.
