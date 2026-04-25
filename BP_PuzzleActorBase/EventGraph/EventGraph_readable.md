# EventGraph

## Graph Type
EventGraph

## Purpose
Main runtime entry graph for this Blueprint.

## Reads
- ExpectedPuzzleId
- ExpectedStepId

## Writes
- PuzzleControllerRef
- bIsActiveForCurrentStep
- bCompleted
- ReceivedStepData
- ReceivedStepIndex

## Calls
- Get Actor Of Class
- Debug Puzzle Message
- On Puzzle Step Activated Local
- On Puzzle Step Reset Local

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
