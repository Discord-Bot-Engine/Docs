# Seek Queue

**Description:** Seeks the current playing track in the queue to a specified duration.

**Inputs:**

* Server
* Duration (seconds)

**Outputs:**

* action

**Variable Types:** None

**Behaviour:** Sets the playback position of the current track in the queue to the given duration and toggles the ffmpeg filter, then continues.
