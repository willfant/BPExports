# InitializeAudioManager

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Reads
- bInitialized
- WorldModeSystemRef
- GhostManagerRef

## Writes
- CachedGameInstance
- WorldModeSystemRef
- GhostManagerRef
- bInitialized

## Calls
- Debug Info
- Get Sender Name
- Get Game Instance
- Debug Critical
- Register Audio Manager
- Initialize World Mode Audio Binding
- Initialize Ghost Audio Binding

## Called By
- EventGraph

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
