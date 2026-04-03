# RestoreObjectivesFromSave

## Graph Type
Function

## Purpose
Restores runtime state from previously saved or cached data.

## Reads
- SaveManagerRef
- bEnableObjectiveDebug

## Writes
- CurrentObjectiveId
- ObjectiveStates
- bObjectivesRestoredFromSave

## Calls
- Debug
- Get Current Save Data
- Find Current Active Objective from States
- Broadcast Current Objective Changed
- To String (Text)

## Called By
- EventGraph

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
