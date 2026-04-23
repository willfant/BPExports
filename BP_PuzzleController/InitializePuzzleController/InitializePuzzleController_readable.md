# InitializePuzzleController

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Reads
- bInitialized
- GhostManagerRef
- ObjectiveManagerRef
- TransitionManagerRef
- ScareManagerRef
- SaveManagerRef
- WorldModeSystemRef

## Writes
- GhostManagerRef
- ObjectiveManagerRef
- TransitionManagerRef
- ScareManagerRef
- SaveManagerRef
- CachedWorldModeSystem
- bInitialized

## Calls
- Debug Info
- Get Sender Name
- Get Game Instance
- Debug Critical
- Register Puzzle Controller
- Initialize Ghost Binding
- Initialize World Mode Binding

## Called By
- EventGraph

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
