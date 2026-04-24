# StartMemoryTransition

## Graph Type
Function

## Purpose
Starts a flow, state transition, or activation sequence.

## Reads
- bTransitionInProgress
- CachedGI
- FadeWidgetRef
- TransictionDataL

## Writes
- bTransitionInProgress
- CurrentTransitionData
- TransictionDataL

## Calls
- Play Transition SFX
- Set Startup Pending Transition
- Is Valid
- Play Fade Out
- Ensure Fade Widget
- Execute Level Travel
- Set Timer by Event

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
