# Dashboard Value Changed

**Description:** Trigger when a dashboard input value changes and the input matches the provided one.

**Inputs:**

* Input
* Store server in variable
* Store value in variable

**Variable Types:**&#x20;

* Server
* Text
* Role
* Channel
* Member
* Mentionable

**Behaviour:** Fetches the server, converts the input value to the appropriate type (role, channel, member, mentionable) and stores both the server and value variables. Then continues with the next actions.
