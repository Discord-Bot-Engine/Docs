# Set Member Data

**Description:** Sets a custom data field for a member in the bot's data storage.

**Inputs:**

* Member
* Field (key)
* Value

**Outputs:**

* action

**Variable Types:**

* Member

**Behaviour:** Creates a unique key combining member id, guild id, and given field, stores the value, then continues.
