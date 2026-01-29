# Edit Message

**Description:** Edits a message's content, components, and attachments.

**Inputs:**

* Message
* Interactive components mode (Persistent, Temporary)
* Files (list)
* Components (list)

**Outputs:**

* action
* \[Dynamic outputs]: button clicks and select menu selections

**Variable Types:**

* Message
* User
* Member
* Channel
* Server
* Button Interaction
* Select Menu Interaction
* List

**Behaviour:** Allows editing the message with various rich content components and files. Registers event listeners for buttons and select menus included. Runs respective outputs on interactions.
