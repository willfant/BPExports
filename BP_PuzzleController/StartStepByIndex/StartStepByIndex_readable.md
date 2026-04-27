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
- Broadcast Step Activation
- Sync Puzzle Progress to Save
- Debug Puzzle Message
- Print String
- To String (Text)

## Called By
- ReportStepSuccess
- ResetCurrentStep
- StartPuzzleByRowNameAndStep

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
