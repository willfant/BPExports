# StartObjective

## Graph Type
Function

## Purpose
Starts a flow, state transition, or activation sequence.

## Reads
- ObjectivesDataTable
- ObjectiveStates
- LocalObjectiveStates
- bFoundExistingObjective
- FoundObjectiveIndex
- PreparedObjective

## Writes
- CurrentObjectiveId
- PreparedObjective
- LocalObjectiveStates
- bFoundExistingObjective
- FoundObjectiveIndex
- ObjectiveStates

## Calls
- Debug
- Sync Objectives to Save
- Broadcast Current Objective Changed
- To String (Text)

## Called By
- CompleteObjective
- InitializeObjectivesForGhost

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
