# RequestAutoSave

## Graph Type
Function

## Purpose
Synchronizes or persists runtime state.

## Reads
- bEnableAutoSave
- bEnableSaveDebug
- bAutoSavePending
- AutoSaveReasonLast
- AutoSaveDelay

## Writes
- AutoSaveReasonLast
- bAutoSavePending

## Calls
- Debug Log
- Set Timer by Function Name

## Called By
- SetCurrentGhostId
- SetCurrentGhostState
- SetCurrentWorldMode
- SetCurrentPuzzleId
- SetCurrentPuzzleStepIndex
- MarkPuzzleCompleted
- SetCurrentLevelName
- SetCurrentLevel

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
