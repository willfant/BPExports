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
- PreparedCompletedObjective
- NextObjectiveIdLocal

## Writes
- LocalObjectiveStates
- bFoundObjectiveToComplete
- FoundObjectiveIndex
- NextObjectiveIdLocal
- PreparedCompletedObjective
- ObjectiveStates

## Calls
- Debug
- Start Objective
- Sync Objectives to Save
- Broadcast Current Objective Changed
- To String (Text)
- Debug Message

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
