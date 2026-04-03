# InitializeWorldModeSystem

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Reads
- bDebugEnabled
- SaveManagerRef

## Writes
- CachedGameInstance
- bInitialized
- SaveManagerRef

## Calls
- Get Game Instance
- Debug Message
- Is Valid

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
