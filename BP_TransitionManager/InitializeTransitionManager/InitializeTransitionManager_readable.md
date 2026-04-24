# InitializeTransitionManager

## Graph Type
Function

## Purpose
Initializes references, state, or startup flow.

## Reads
- SaveManagerRef
- WorldModeSystemRef

## Writes
- CachedGI
- CachedWorldModeSystem
- CachedSaveManager

## Calls
- Get Game Instance
- Register Transition Manager
- Ensure Fade Widget
- Handle Pending Arrival Transition

## Called By
- EventGraph

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
