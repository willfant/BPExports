# InitializeWorldModeBinding

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Reads
- bShuttingDown
- bWorldModeBindingInitialized
- CachedWorldModeSystem
- WorldModeBindingRetryHandle
- WorldModeSystemRef

## Writes
- WorldModeBindingRetryHandle
- CachedWorldModeSystem
- bWorldModeBindingInitialized

## Calls
- Is Valid
- Get Game Instance
- Clear and Invalidate Timer by Handle
- Set Timer by Function Name

## Called By
- InitializePuzzleController

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
