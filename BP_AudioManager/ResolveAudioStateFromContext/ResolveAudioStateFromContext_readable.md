# ResolveAudioStateFromContext

## Graph Type
Function

## Purpose
Resolves contextual state or external information.

## Returns
- Found (Boolean)
- ResolvedStateId (Name)
- Found (Boolean)
- ResolvedStateId (Name)
- Found (Boolean)
- ResolvedStateId (Name)
- Found (Boolean)
- ResolvedStateId (Name)

## Reads
- DT_AudioStates
- DebugEnabled
- CurrentWorldMode
- CurrentGhostState
- CurrentGhostId
- bHasExactMatch
- ExactStateId
- bHasFallback
- FallbackStateId

## Writes
- ExactStateId
- bHasExactMatch
- FallbackStateId
- bHasFallback

## Calls
- Is Valid
- Debug Message
- Get Data Table Row Names
- To String (Text)

## Called By
- ApplyResolvedAudioStateFromContext

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
