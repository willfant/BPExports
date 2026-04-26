# InitializeGhostAudioBinding

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Reads
- GhostManagerRef
- bShuttingDown
- bGhostAudioBindingInitialized
- GhostAudioBindingRetryHandle

## Writes
- GhostManagerRef
- GhostAudioBindingRetryHandle
- bGhostAudioBindingInitialized

## Calls
- Is Valid
- Get Game Instance
- Set Timer by Function Name
- Clear and Invalidate Timer by Handle

## Called By
- InitializeAudioManager

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
