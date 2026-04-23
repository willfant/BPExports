# StartPuzzleByRowNameAndStep

## Graph Type
Function

## Purpose
Starts a flow, state transition, or activation sequence.

## Returns
- bStartedPuzzle (Boolean)
- bStartedPuzzle (Boolean)
- bStartedPuzzle (Boolean)
- bStartedPuzzle (Boolean)
- bStartedPuzzle (Boolean)
- bStartedPuzzle (Boolean)

## Reads
- DT_Puzzles
- PuzzleDataL
- StepCountL
- CompletedStepIds
- FailedStepsIds
- StartedPuzzleIds

## Writes
- PuzzleDataL
- StepCountL
- CurrentPuzzleId
- CurrentPuzzleData
- bHasActivePuzzle
- bStepActive
- CurrentStepIndex

## Calls
- Is Valid
- Debug Warning
- Get Sender Name
- Debug Critical
- To String (Text)
- Can Puzzle be Selected for Current Context
- Debug Info

## Called By
- StartFirstPuzzleForCurrentGhost
- RestorePuzzleFromSave

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
