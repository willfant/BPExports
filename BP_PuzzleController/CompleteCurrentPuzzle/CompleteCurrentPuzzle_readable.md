# CompleteCurrentPuzzle

## Graph Type
Function

## Purpose
Completes state, runtime flow, or progression.

## Reads
- bHasActivePuzzle
- CurrentPuzzleId
- CompletedStepIds

## Writes
- bHasActivePuzzle
- bStepActive
- CurrentStepIndex
- bPuzzleRestoredFromSave
- CurrentPuzzleId

## Calls
- Debug Warning
- Get Sender Name
- Debug Critical
- Sync Puzzle Progress to Save
- Handle Puzzle Completion Consequences
- Debug Info

## Called By
- ReportStepSuccess

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
