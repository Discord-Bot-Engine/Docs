# Show Modal

**Description:**\
Shows a modal to a user from an interaction. Supports text, text inputs, select menus, and file uploads, and stores submitted values into variables.

**Inputs:**

* Interaction
* Custom ID
* Title
* Store interaction in variable
* Store member in variable
* Store user in variable
* Store message in variable
* Store channel in variable
* Store server in variable
* Components (list)

**Outputs:**

* action
* on submit

**Variable Types:**

* User
* Member
* Channel
* Server
* Context Menu Interaction
* Command Interaction
* Select Menu Interaction
* Modal Interaction
* List

**Behaviour:**\
Builds and displays a modal using the provided interaction, adding components like text, text inputs, select menus, and file uploads. Stores the interaction, user, member, message, channel, server, and any submitted component values into variables, then runs the next action through the action output, and after the user submits the modal, continues through the on submit output.
