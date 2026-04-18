# DebugPuzzleMessage

## Graph Type
Function

## Purpose
Provides debug or developer-facing behavior.

## Reads
- bDebugPuzzle
- DebugSenderName

## Calls
- Debug Message
- To String (Text)

## Called By
- InitializeManagerReferences
- ResolveCurrentGhostId
- DebugCurrentPuzzleCatalog
- StartFirstPuzzleForCurrentGhost
- StartPuzzleById
- StartStepByIndex
- CompleteCurrentPuzzle
- BroadcastStepActivation
- ReportStepSuccess
- HandleStepSuccessConsequences
- ReportStepFailure
- HandlePuzzleCompletionConsequences
- ResetCurrentPuzzle
- RestorePuzzleFromSave
- StartPuzzleByRowNameAndStep
- SyncPuzzleProgressToSave
- StartNextValidPuzzleForCurrentContext

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
