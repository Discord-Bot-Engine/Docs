# Reaction Added

**Description:** Trigger when a reaction is added to a message.

**Inputs:**

* Store burst in variable (boolean, whether the reaction was burst)
* Store reaction in variable
* Store user in variable
* Store member in variable
* Store message in variable
* Store channel in variable
* Store server in variable

**Variable Types:**&#x20;

* Message
* Boolean
* User
* Member
* Channel
* Reaction
* Server

**Behaviour:** Stores details of the reaction added event including burst status, reaction object, the user who reacted, member, original message, channel and server. Then continues with the next actions.
