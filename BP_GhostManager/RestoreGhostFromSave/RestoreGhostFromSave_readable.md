# RestoreGhostFromSave

## Graph Type
Function

## Purpose
Restores runtime state from previously saved or cached data.

## Reads
- SaveManagerRef
- CurrentGhostId
- CurrentGhostState
- DebugEnabled

## Writes
- bIsRestoringFromSave

## Calls
- Is Valid
- Debug Message
- Set Active Ghost
- Set Ghost State

## Called By
- EventGraph

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
