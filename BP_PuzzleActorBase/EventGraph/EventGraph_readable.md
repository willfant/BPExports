# EventGraph

## Graph Type
EventGraph

## Purpose
Main runtime entry graph for this Blueprint.

## Reads
- ExpectedPuzzleId
- ExpectedStepId

## Writes
- bIsActiveForCurrentStep
- bCompleted
- ReceivedStepIndex
- ReceivedStepData

## Calls
- Resolve Puzzle Controller Ref
- On Puzzle Step Reset Local
- On Puzzle Step Activated Local
- To String (Text)

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
