# Create Channel

**Description:** Creates a new channel on a server with optional permissions.

**Inputs:**

* Server
* Channel name
* Type (Text, Voice, Announcement, Stage, Forum, Category)
* Category (hidden if Category type selected)
* Store channel in variable
* Permissions (list of targets and their permissions)

**Outputs:**

* action

**Variable Types:**

* Server
* Channel
* Role
* Member
* User

**Behaviour:** Creates a channel of the chosen type and optional parent category on the server. Applies permission overwrites for roles/members/users. Stores the created channel for further use.
