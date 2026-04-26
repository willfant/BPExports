# InitializeWorldModeAudioBinding

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Reads
- bShuttingDown
- bWorldModeBindingInitialized
- WorldModeSystemRef
- WorldModeBindingRetryHandle

## Writes
- WorldModeBindingRetryHandle
- WorldModeSystemRef
- bWorldModeBindingInitialized

## Calls
- Is Valid
- Get Game Instance
- Clear and Invalidate Timer by Handle
- Set Timer by Function Name

## Called By
- InitializeAudioManager

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
