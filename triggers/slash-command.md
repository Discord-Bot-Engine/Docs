# Slash Command

**Description:** Trigger when a slash command with the name matching the trigger is used.

**Inputs:**

* Description
* Store interaction in variable
* Store user in variable
* Store member in variable
* Store channel in variable
* Store server in variable
* Options list with:
  * Name
  * Description
  * Type (Attachment, Boolean, Channel, Integer, Mentionable, Number, Role, Text, User)
  * Is Required? (True or False)
  * Store value in variable

**Variable Types:**&#x20;

* Command Interaction
* User
* Member
* Server
* Attachment
* Boolean
* Channel
* Mentionable
* Number
* Role
* Text
* User

**Behaviour:** Registers the slash command with specified options, stores the interaction and command option values into variables on interaction, then continues with the next actions.
