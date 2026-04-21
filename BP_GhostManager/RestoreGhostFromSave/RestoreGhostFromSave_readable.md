# RestoreGhostFromSave

## Graph Type
Function

## Purpose
Restores runtime state from previously saved or cached data.

## Returns
- bSuccess (Boolean)
- bSuccess (Boolean)
- bSuccess (Boolean)

## Reads
- CurrentGhostId

## Writes
- bIsRestoringFromSave
- ClearedGhostIds

## Calls
- Set Active Ghost
- Debug Critical
- Get Display Name
- String To Name
- Clear Active Ghost
- Set Ghost State
- Debug Info

## Called By
- EventGraph

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
