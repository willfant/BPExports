# InitializeGhostBinding

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Reads
- GhostManagerRef
- bShuttingDown
- bGhostBindingInitialized

## Writes
- GhostBindingRetryHandle
- GhostManagerRef

## Calls
- Is Valid
- Debug Warning
- Get Sender Name
- Handle Ghost Changed
- Debug Info
- Get Game Instance
- Set Timer by Function Name

## Called By
- InitializeObjectiveManager

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
