# RestoreObjectivesFromSave

## Graph Type
Function

## Purpose
Restores runtime state from previously saved or cached data.

## Returns
- bSuccess (Boolean)
- bSuccess (Boolean)
- bSuccess (Boolean)

## Writes
- CurrentQuestId
- ObjectiveStates
- bObjectivesRestoredFromSave
- CurrentObjectiveId

## Calls
- Find Current Active Objective from States
- Broadcast Current Objective Changed
- Debug Info
- Get Display Name
- String To Name
- Debug Warning

## Called By
- EventGraph

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
