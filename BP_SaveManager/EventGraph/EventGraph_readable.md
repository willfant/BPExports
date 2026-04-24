# EventGraph

## Graph Type
EventGraph

## Purpose
Main runtime entry graph for this Blueprint.

## Reads
- bAutoInitializeSaveOnBeginPlay
- CachedGI
- InitialRestoreRetryHandle
- bAutoLoadOnBeginPlay

## Writes
- CachedGI
- bShuttingDown

## Calls
- Initialize Save System
- Get Game Instance
- Register Save Manager
- Clear and Invalidate Timer by Handle
- Try Initial Restore After Bootstrap

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
