# Schedule Event

**Description:** Creates a new scheduled event in a server.

**Inputs:**

* Server
* Event name
* Description
* Event type (Voice, Stage, External)
* Channel (for Voice/Stage events)
* Location (for External events)
* Image URL
* Start in (hours)
* Duration (hours, for External events)
* Store event in variable

**Outputs:**

* action

**Variable Types:**

* Server
* Channel
* Scheduled Event
* Text
* Number

**Behaviour:** Creates a scheduled event in the specified server using the provided configuration. The start time is calculated based on the current time plus the given hours. For External events, a duration and location are required. The created event is stored in the selected variable.
