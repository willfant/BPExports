# InitializeSaveSystem

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Returns
- bSuccess (Boolean)
- bSuccess (Boolean)
- bSuccess (Boolean)
- bSuccess (Boolean)
- bSuccess (Boolean)

## Reads
- SaveSlotName
- UserIndex

## Writes
- bSaveSystemReady
- AutoSaveReasonLast

## Calls
- Debug Info
- Get Sender Name
- Does Save Game Exist
- Load Save
- Debug Critical
- Create New Save
- Write Save to Disk

## Called By
- EventGraph

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
