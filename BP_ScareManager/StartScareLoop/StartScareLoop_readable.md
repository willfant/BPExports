# StartScareLoop

## Graph Type
Function

## Purpose
Starts a flow, state transition, or activation sequence.

## Reads
- bScareLoopActive
- CurrentGhostState
- CurrentWorldMode

## Writes
- bScareLoopActive
- ScareLoopTimerHandle

## Calls
- Set Timer by Function Name
- Get Scare Interval for Current Ghost State
- Get Scare Interval for Current Context

## Called By
- InitializeScaresForGhost
- RestartScareLoopForCurrentState

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
