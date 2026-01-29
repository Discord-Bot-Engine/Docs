# Send Message

**Description:** Sends a message to a channel, member, or user with optional files and components.

**Inputs:**

* Channel, member or user
* Interactive components mode (Persistent, Temporary)
* Store message in variable
* Files (list)
* Components (list)

**Outputs:**

* action
* dynamic outputs per buttons/select menus

**Variable Types:**

* Message
* User
* Member
* Channel
* Server
* Button Interaction
* Select Menu Interaction
* List

**Behaviour:** Sends a new message with the specified content and components, registers component event handlers, stores the sent message, then continues.
