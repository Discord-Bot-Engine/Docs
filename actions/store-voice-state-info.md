# Store Voice State Info

**Description:** Stores details about a voice state.

**Inputs:**

* Voice State
* Info (Channel, Server, Session ID, Is Deaf, Is Muted, Is Streaming, Request to Speak Timestamp, etc.)
* Store value in variable

**Outputs:**

* action

**Variable Types:**

* Voice State
* Channel
* Boolean
* Text
* Number
* Server

**Behaviour:** Fetches the specified voice state info and stores it, returning null if voice state is missing.
