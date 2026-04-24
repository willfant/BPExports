# ExecuteAutoSave

## Graph Type
Function

## Purpose
Synchronizes or persists runtime state.

## Reads
- AutoSaveReasonLast
- bAutoSavePending
- PendingReasonL

## Writes
- PendingReasonL
- bAutoSavePending
- AutoSaveReasonLast

## Calls
- To String (Text)
- Build Snapshot from Managers
- Write Save to Disk

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
