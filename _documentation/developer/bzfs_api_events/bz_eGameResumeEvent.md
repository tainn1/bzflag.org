---
dataType: bz_GamePauseResumeEventData_V2
since: 2.4.4
plugins: ~
parameters:
  - dataType: bz_ApiString
    description: The callsign of whoever triggered the event. By default, it's "SERVER"
    name: actionBy
  - dataType: int
    description: The ID of the player who triggered this action. By default, it's 253
    name: playerID
  - dataType: double
    description: The server time the event occurred (in seconds).
    name: eventTime
---

This event is triggered when a timed game resumes
