# Store Scheduled Event Info

**Description:** Stores various information of a scheduled event.

**Inputs:**

* Scheduled Event
* Info (Id, Name, Description, Status, Type, Channel, Location, Creator, Server, Start Time, End Time, Created At, User Count, Subscribers, Image URL, URL)
* Store value in variable

**Outputs:**

* action

**Variable Types:**

* Scheduled Event
* Channel
* Text
* User
* Member
* Server
* Date
* Boolean
* Number
* List

**Behaviour:** Gets the specified information property from the scheduled event and stores it in the selected variable. For Subscribers, it fetches subscribers and returns their associated members when available.
