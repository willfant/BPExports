# InitializeWorldModeSystem

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Reads
- SaveManagerRef
- bInitialized

## Writes
- CachedGameInstance
- bInitialized
- SaveManagerRef

## Calls
- Get Game Instance
- Register World Mode System

## Called By
- EventGraph
- SetWorldMode
- SyncFromGameInstance

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
