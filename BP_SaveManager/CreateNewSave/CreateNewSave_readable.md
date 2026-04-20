# CreateNewSave

## Graph Type
Function

## Purpose
Synchronizes or persists runtime state.

## Reads
- bEnableSaveDebug

## Writes
- CurrentSaveObject
- CurrentSaveData

## Calls
- Create Save Game Object
- Build Snapshot from Managers
- Debug Log

## Called By
- InitializeSaveSystem

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
