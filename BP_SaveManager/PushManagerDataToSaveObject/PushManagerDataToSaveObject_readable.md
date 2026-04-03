# PushManagerDataToSaveObject

## Graph Type
Function

## Purpose
Synchronizes or persists runtime state.

## Reads
- CurrentSaveObject
- CurrentSaveData
- bIsabel_MR_EntrySolved
- bIsabel_DiaryComplete
- bIsabel_CandlesComplete
- bIsabel_MirrorComplete
- bEnableSaveDebug
- CurrentGhostId
- CurrentGhostState
- CurrentWorldMode
- CurrentPuzzleId
- CurrentPuzzleStepIndex
- CompletedPuzzleIds
- CurrentLevelName
- CurrentLevel

## Writes
- SaveData
- bIsabel_MR_EntrySolved
- bIsabel_DiaryComplete
- bIsabel_CandlesComplete
- bIsabel_MirrorComplete
- SavedGhostId
- SavedGhostState
- SavedWorldMode
- SavedCurrentPuzzleId
- SavedCurrentPuzzleStepIndex
- SavedCompletedPuzzleIds
- SavedCurrentLevelName
- SavedCurrentLevel

## Calls
- Debug Log

## Called By
- CreateNewSave
- WriteSaveToDisk

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
