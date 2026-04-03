# ResetCurrentStep

## Graph Type
Function

## Purpose
Resets runtime state or reinitializes a sub-flow.

## Reads
- CurrentStepIndex
- CurrentPuzzleId
- CurrentStepData

## Writes
- bStepActive

## Calls
- Broadcast Step Reset
- Start Step by Index

## Called By
- HandleStepFailureConsequences

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
