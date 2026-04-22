# StartObjective

## Graph Type
Function

## Purpose
Starts a flow, state transition, or activation sequence.

## Reads
- ObjectivesDataTable
- LocalObjectiveStates
- bFoundExistingObjective
- FoundObjectiveIndex
- PreparedObjective
- ObjectiveStates
- ExistingObjectiveData

## Writes
- PreparedObjective
- bFoundExistingObjective
- FoundObjectiveIndex
- ObjectiveStates
- LocalObjectiveStates
- CurrentObjectiveId
- ExistingObjectiveData

## Calls
- Broadcast Current Objective Changed
- Debug Warning
- Get Sender Name
- Debug Critical
- Sync Objectives to Save
- Debug Info

## Called By
- CompleteObjective
- InitializeObjectivesForGhost

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
