# StartPuzzleById

## Graph Type
Function

## Purpose
Starts a flow, state transition, or activation sequence.

## Reads
- DT_Puzzles
- CompletedStepIds
- FailedStepsIds
- StartedPuzzleIds
- CurrentPuzzleId
- CurrentStepData
- CurrentStepIndex

## Writes
- CurrentPuzzleId
- CurrentPuzzleData
- bHasActivePuzzle
- CurrentStepIndex
- bStepActive

## Calls
- Is Valid
- Debug Puzzle Message
- Start Step by Index
- Broadcast Step Activation

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
