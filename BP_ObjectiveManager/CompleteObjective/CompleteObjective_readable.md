# CompleteObjective

## Graph Type
Function

## Purpose
Completes state, runtime flow, or progression.

## Reads
- ObjectiveStates
- LocalObjectiveStates
- bFoundObjectiveToComplete
- FoundObjectiveIndex
- ExistingObjectiveData
- PreparedCompletedObjective
- NextObjectiveIdLocal

## Writes
- LocalObjectiveStates
- bFoundObjectiveToComplete
- FoundObjectiveIndex
- NextObjectiveIdLocal
- ExistingObjectiveData
- PreparedCompletedObjective
- ObjectiveStates
- CurrentObjectiveId

## Calls
- Debug Warning
- Get Sender Name
- Debug Info
- Start Objective
- Sync Objectives to Save
- Broadcast Current Objective Changed

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
