# SubmitDebugMessage

## Graph Type
Function

## Purpose
Provides debug or developer-facing behavior.

## Reads
- bDebugSystemEnabled
- StampedMessage
- ProcessedMessage
- ResolvedSettings

## Writes
- StampedMessage
- ResolvedSettings
- ProcessedMessage

## Calls
- Stamp Debug Context
- Is Debug Message Allowed
- Process Once and Throttle
- Get Game Time in Seconds
- Append Debug History
- Route Debug Message

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
