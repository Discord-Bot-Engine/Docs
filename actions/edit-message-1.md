# Edit Scheduled Event

**Description:** Edits an existing scheduled event.

**Inputs:**

* Scheduled Event
* Event name
* Description
* Event type (Voice, Stage, External)
* Channel
* Location
* Image URL
* Start in (hours)
* Duration (hours)
* Status (Scheduled, Active, Completed, Canceled)

**Outputs:**

* action

**Variable Types:**

* Scheduled Event
* Channel
* Text
* Number

**Behaviour:** Updates the selected scheduled event with the provided values. Time fields can only be updated while the event is still scheduled. Channel and location fields are applied depending on the event type. Status changes follow Discord’s event lifecycle rules.
