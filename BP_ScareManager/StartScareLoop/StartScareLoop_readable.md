# StartScareLoop

## Graph Type
Function

## Purpose
Starts a flow, state transition, or activation sequence.

## Reads
- bScareLoopActive
- CurrentGhostState
- CurrentGhostId
- ScareLoopTimerHandle
- ScareLoopInterval

## Writes
- bScareLoopActive
- ScareLoopInterval
- ScareLoopTimerHandle

## Calls
- Get Scare Interval for Current Context
- Debug Info
- Get Sender Name
- Debug Warning
- Clear and Invalidate Timer by Handle
- Set Timer by Function Name
- To String (Text)

## Called By
- InitializeScaresForGhost
- RestartScareLoopForCurrentState

## Branch Points
- Branch

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
