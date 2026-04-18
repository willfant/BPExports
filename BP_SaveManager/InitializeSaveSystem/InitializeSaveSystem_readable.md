# InitializeSaveSystem

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Reads
- SaveSlotName
- UserIndex
- bEnableSaveDebug

## Writes
- bSaveSystemReady

## Calls
- Does Save Game Exist
- Load Save
- Create New Save
- Write Save to Disk
- Debug Log

## Called By
- EventGraph

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
