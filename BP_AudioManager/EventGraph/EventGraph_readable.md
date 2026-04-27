# EventGraph

## Graph Type
EventGraph

## Purpose
Main runtime entry graph for this Blueprint.

## Reads
- DebugEnabled
- WorldModeBindingRetryHandle
- GhostAudioBindingRetryHandle
- AudioContextRefreshRetryHandle

## Writes
- CurrentWorldMode
- CurrentGhostId
- CurrentGhostState
- bShuttingDown

## Calls
- Initialize Audio Manager
- Debug Message
- To String (Text)
- Apply Resolved Audio State from Context
- Clear and Invalidate Timer by Handle
- Stop All Looping Cues
- Stop Ambience Sound
- Stop Music Sound

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
