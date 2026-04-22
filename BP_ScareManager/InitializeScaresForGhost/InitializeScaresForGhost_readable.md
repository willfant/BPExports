# InitializeScaresForGhost

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Reads
- ValidScareIds
- ValidScareCandidates

## Writes
- CurrentGhostId
- ActiveScareIds
- CurrentGhostState
- SelectedScareId

## Calls
- Debug Warning
- Get Sender Name
- Stop Scare Loop
- To String (Text)
- Debug Info
- Restart Scare Loop for Current State

## Called By
- HandleGhostChanged

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
