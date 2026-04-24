# TryInitialRestoreAfterBootstrap

## Graph Type
Function

## Purpose
Restores runtime state from previously saved or cached data.

## Reads
- bShuttingDown
- bInitialRestoreCompleted
- InitialRestoreRetryHandle

## Writes
- bInitialRestoreCompleted
- InitialRestoreRetryHandle

## Calls
- Is Save System Ready
- Resolve Owner Manager Refs
- Restore Full Game State
- Clear and Invalidate Timer by Handle
- Set Timer by Function Name
- Is Valid

## Called By
- EventGraph

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
