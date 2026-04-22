# StartMemoryTransition

## Graph Type
Function

## Purpose
Starts a flow, state transition, or activation sequence.

## Reads
- bTransitionInProgress
- CachedGI
- FadeWidgetRef
- bDebugTransitions

## Writes
- bTransitionInProgress
- CurrentTransitionData

## Calls
- Play Transition SFX
- Is Valid
- Set Startup Pending Transition
- Play Fade Out
- Set Timer by Event
- Debug Message

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
