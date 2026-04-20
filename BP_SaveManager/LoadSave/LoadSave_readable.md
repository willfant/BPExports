# LoadSave

## Graph Type
Function

## Purpose
Synchronizes or persists runtime state.

## Returns
- bSuccess (Boolean)

## Reads
- SaveSlotName
- UserIndex
- bEnableSaveDebug

## Writes
- CurrentSaveObject

## Calls
- Load Game from Slot
- Apply Snapshot to Managers
- Debug Log

## Called By
- InitializeSaveSystem
- RestoreFullGameState

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
