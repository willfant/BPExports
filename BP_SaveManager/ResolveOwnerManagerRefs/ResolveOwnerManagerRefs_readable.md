# ResolveOwnerManagerRefs

## Graph Type
Function

## Purpose
Resolves contextual state or external information.

## Returns
- bSuccess (Boolean)
- GhostManagerRef (BP_GhostManager_C)
- WorldModeSystemRef (BP_WorldModeSystem_C)
- ObjectiveManagerRef (BP_ObjectiveManager_C)
- PuzzleControllerRef (BP_PuzzleController_C)
- TransitionManagerRef (BP_TransitionManager_C)
- AudioManagerRef (BP_AudioManager_C)
- ScareManagerRef (BP_ScareManager_C)
- bSuccess (Boolean)
- GhostManagerRef (BP_GhostManager_C)
- WorldModeSystemRef (BP_WorldModeSystem_C)
- ObjectiveManagerRef (BP_ObjectiveManager_C)
- PuzzleControllerRef (BP_PuzzleController_C)
- TransitionManagerRef (BP_TransitionManager_C)
- AudioManagerRef (BP_AudioManager_C)
- ScareManagerRef (BP_ScareManager_C)

## Reads
- CachedGI
- GhostManagerRef
- WorldModeSystemRef
- ObjectiveManagerRef
- PuzzleControllerRef
- TransitionManagerRef
- AudioManagerRef
- ScareManagerRef

## Writes
- CachedGI

## Calls
- Is Valid
- Get Game Instance

## Called By
- BuildSnapshotFromManagers
- ApplySnapshotToManagers
- RestoreFullGameState

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
