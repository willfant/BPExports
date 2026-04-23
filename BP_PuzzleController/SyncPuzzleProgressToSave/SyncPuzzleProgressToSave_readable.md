# SyncPuzzleProgressToSave

## Graph Type
Function

## Purpose
Synchronizes or persists runtime state.

## Reads
- SaveManagerRef
- CurrentPuzzleId
- CurrentStepIndex

## Calls
- Is Valid
- Debug Puzzle Message
- Set Current Puzzle Id
- Set Current Puzzle Step Index
- Print String
- To String (Integer)

## Called By
- StartStepByIndex
- HandlePuzzleCompletionConsequences

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
