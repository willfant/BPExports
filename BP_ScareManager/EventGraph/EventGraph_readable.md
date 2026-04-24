# EventGraph

## Graph Type
EventGraph

## Purpose
Main runtime entry graph for this Blueprint.

## Reads
- WorldModeBindingRetryHandle

## Writes
- CurrentScareActor
- bShuttingDown

## Calls
- Start Scare Cooldown
- Initialize Scare Manager
- Clear and Invalidate Timer by Handle

## Notes
- Has latent nodes: No
- Has error nodes: Yes
- Has warning nodes: No
