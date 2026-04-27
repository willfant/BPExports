# RefreshAudioContextFromManagers

## Graph Type
Function

## Purpose
Auto-generated function summary.

## Reads
- WorldModeSystemRef
- GhostManagerRef
- CurrentGhostId
- CurrentGhostState
- CurrentWorldMode
- bShuttingDown

## Writes
- CurrentWorldMode
- CurrentGhostId
- CurrentGhostState
- GhostManagerRef
- AudioContextRefreshRetryHandle
- WorldModeSystemRef

## Calls
- Is Valid
- Get World Mode
- Has Active Ghost
- Debug Warning
- Get Sender Name
- Apply Resolved Audio State from Context
- Debug Info
- Get Game Instance
- Set Timer by Function Name
- To String (Text)

## Called By
- HandleWorldModeAudioContextChanged
- HandleGhostAudioContextChanged
- HandleGhostStateAudioContextChanged
- HandleGhostClearedAudioContextChanged

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
