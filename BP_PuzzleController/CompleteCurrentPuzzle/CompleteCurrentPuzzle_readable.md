# CompleteCurrentPuzzle

## Graph Type
Function

## Purpose
Completes state, runtime flow, or progression.

## Reads
- bHasActivePuzzle
- CompletedStepIds
- CurrentPuzzleId
- SaveManagerRef
- CompletedPuzzleIds

## Writes
- bHasActivePuzzle
- bStepActive
- CurrentStepIndex

## Calls
- Debug Puzzle Message
- Mark Puzzle Completed
- Handle Puzzle Completion Consequences

## Called By
- ReportStepSuccess

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
