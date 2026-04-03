# EventGraph

## Graph Type
EventGraph

## Purpose
Main runtime entry graph for this Blueprint.

## Reads
- SaveManagerRef
- DefaultGhostId
- CurrentGhostId

## Writes
- GhostManagerRef

## Calls
- Initialize Ghost Manager
- Get Game Instance
- Notify Scare Manager for Ghost
- Restore Ghost from Save
- Get Current Ghost Id
- Set Active Ghost

## Branch Points
- Branch

## Notes
- Has latent nodes: Yes
- Has error nodes: No
- Has warning nodes: No
