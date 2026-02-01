# Set Cooldown

**Description:** Sets a cooldown for a specific member or user for a given amount of seconds.&#x20;

**Inputs:**

* Member or user
* Seconds
* Store time remaining in variable

**Outputs:**

* action
* on cooldown
* on end

**Variable Types:**&#x20;

* Member
* Number
* User

**Behaviour:** Starts a cooldown for the selected member or user. If they are not on cooldown, execution continues through the action output. If they are already on cooldown, the remaining time (in seconds) is stored in the selected number variable and execution continues through the on cooldown output. Once the cooldown expires, the on end output is fired automatically.
