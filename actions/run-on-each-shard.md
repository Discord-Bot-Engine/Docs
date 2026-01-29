# Run On Each Shard

**Description:** Executes an action on each shard of the bot cluster.

**Inputs:** None

**Outputs:**

* action
* each

**Variable Types:** None

**Behaviour:** Broadcasts the action to all shards to run the "each" output, then continues on the main shard.
