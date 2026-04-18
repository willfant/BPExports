# WriteSaveToDisk

## Graph Type
Function

## Purpose
Synchronizes or persists runtime state.

## Reads
- CurrentSaveObject
- SaveSlotName
- UserIndex
- bEnableSaveDebug

## Calls
- Push Manager Data to Save Object
- Save Game to Slot
- Print String
- Debug Log

## Called By
- InitializeSaveSystem
- ExecuteAutoSave

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
