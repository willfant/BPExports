# LoadSave

## Graph Type
Function

## Purpose
Synchronizes or persists runtime state.

## Reads
- SaveSlotName
- UserIndex
- bEnableSaveDebug

## Writes
- CurrentSaveObject

## Calls
- Load Game from Slot
- Apply Loaded Data to Manager
- Debug Log

## Called By
- InitializeSaveSystem

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
