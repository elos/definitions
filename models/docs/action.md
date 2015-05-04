An action is something a user can be doing. An action should not be confused with an event, which is anything that can happen to a user. For example, you can imagine synchronous events - a user can be studying, and at the library. The events could be split: studying would mirror being at the library. The action would only ever be studying. Perhaps "walking to the library" would be another.

An action is owned by a user, has a name, a start time and an end time, a boolean field marking it's completion, and an associated actionable, which "created" the task.
