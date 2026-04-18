# StartPuzzleByRowNameAndStep

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

## Writes
- CurrentPuzzleId
- CurrentPuzzleData
- bHasActivePuzzle
- CurrentStepIndex
- bStepActive

## Calls
- Is Valid
- Start Step by Index
- Debug Puzzle Message

## Called By
- StartFirstPuzzleForCurrentGhost
- RestorePuzzleFromSave

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
