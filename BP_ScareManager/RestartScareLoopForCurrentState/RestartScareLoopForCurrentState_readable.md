# RestartScareLoopForCurrentState

## Graph Type
Function

## Purpose
Starts a flow, state transition, or activation sequence.

## Reads
- ScareLoopTimerHandle

## Writes
- bScareLoopActive

## Calls
- Clear and Invalidate Timer by Handle
- Start Scare Loop

## Called By
- UpdateGhostState
- HandleWorldModeChanged

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
