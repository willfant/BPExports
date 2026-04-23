# StartStepByIndex

## Graph Type
Function

## Purpose
Starts a flow, state transition, or activation sequence.

## Reads
- bHasActivePuzzle
- CurrentPuzzleData
- CurrentPuzzleId
- CurrentStepIndex
- CurrentStepData

## Writes
- CurrentStepIndex
- CurrentStepData
- bStepActive

## Calls
- Debug Puzzle Message
- Broadcast Step Activation
- Sync Puzzle Progress to Save

## Called By
- StartPuzzleById
- ReportStepSuccess
- ResetCurrentStep
- StartPuzzleByRowName

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
