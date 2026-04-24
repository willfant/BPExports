# LoadSave

## Graph Type
Function

## Purpose
Synchronizes or persists runtime state.

## Returns
- bSuccess (Boolean)
- bSuccess (Boolean)
- bSuccess (Boolean)

## Reads
- SaveSlotName
- UserIndex
- SaveData

## Writes
- CurrentSaveObject
- CurrentSaveData

## Calls
- Load Game from Slot
- Debug Info
- Get Sender Name
- Is Valid

## Called By
- InitializeSaveSystem
- RestoreFullGameState

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
