# InitializeGhostAudioBinding

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Reads
- DebugEnabled
- CurrentGhostState
- GhostManagerRef

## Writes
- GhostManagerRef
- CurrentGhostId
- CurrentGhostState

## Calls
- Get Actor Of Class
- Is Valid
- Debug Message
- Get Current Ghost Id
- Apply Resolved Audio State from Context

## Called By
- EventGraph

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
