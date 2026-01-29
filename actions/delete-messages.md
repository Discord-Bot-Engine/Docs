# Delete Messages

**Description:** Deletes multiple messages from a channel with filtering.

**Inputs:**

* Channel
* Number (maximum messages to delete)
* Store message in variable
* Store message position in variable

**Outputs:**

* action
* filter

**Variable Types:**

* Channel
* Message
* Number

**Behaviour:** Fetches messages from the channel and iteratively filters them with the "filter" output. Supports continuing, returning, or breaking the loop. When done, bulk deletes the filtered messages.
