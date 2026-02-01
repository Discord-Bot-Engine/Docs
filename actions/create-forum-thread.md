# Create Forum Thread

**Description:** Creates a new thread inside a forum channel with optional files and interactive components.

**Inputs:**

* Forum Channel
* Thread name
* Auto-archive duration&#x20;
* Interactive components mode (Persistent, Temporary)
* Store thread in variable
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

**Behaviour:** Creates a forum post with the specified content and components, registers component event handlers, stores the created thread, then continues.

