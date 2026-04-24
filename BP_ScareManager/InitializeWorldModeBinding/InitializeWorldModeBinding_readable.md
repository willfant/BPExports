# InitializeWorldModeBinding

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
- CurrentWorldMode
- bWorldModeBindingInitialized

## Calls
- Is Valid
- Get Game Instance
- Clear and Invalidate Timer by Handle
- Set Timer by Function Name
- Get World Mode

## Called By
- InitializeScareManager

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
