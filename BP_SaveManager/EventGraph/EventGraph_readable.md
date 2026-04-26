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
- bResumeLastLevelOnStartup
- DefaultResumeLevelName

## Writes
- CachedGI
- bShuttingDown

## Calls
- Initialize Save System
- Get Game Instance
- Register Save Manager
- Clear and Invalidate Timer by Handle
- Try Initial Restore After Bootstrap
- Try Resume Last Saved Level

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
