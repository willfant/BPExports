# StartPuzzleByRowName

## Graph Type
Function

## Purpose
Starts a flow, state transition, or activation sequence.

## Reads
- DT_Puzzles
- CompletedStepIds
- FailedStepsIds
- CurrentPuzzleId
- StartedPuzzleIds

## Writes
- CurrentPuzzleId
- bHasActivePuzzle
- bStepActive
- CurrentStepIndex
- CurrentPuzzleData

## Calls
- Is Valid
- Start Step by Index

## Called By
- StartNextValidPuzzleForCurrentContext

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
