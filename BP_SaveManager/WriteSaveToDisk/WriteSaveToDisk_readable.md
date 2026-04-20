# WriteSaveToDisk

## Graph Type
Function

## Purpose
Synchronizes or persists runtime state.

## Returns
- bSuccess (Boolean)
- bSuccess (Boolean)
- bSuccess (Boolean)
- bSuccess (Boolean)

## Reads
- CurrentSaveObject
- CurrentSaveData
- SaveSlotName
- UserIndex

## Writes
- SaveData

## Calls
- Debug Info
- Get Sender Name
- Build Snapshot from Managers
- Debug Critical
- Is Valid
- Save Game to Slot

## Called By
- InitializeSaveSystem
- ExecuteAutoSave

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
