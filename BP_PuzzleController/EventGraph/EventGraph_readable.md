# EventGraph

## Graph Type
EventGraph

## Purpose
Main runtime entry graph for this Blueprint.

## Reads
- GhostManagerRef
- TransitionManagerRef
- CachedWorldModeSystem
- ObjectiveManagerRef

## Calls
- Initialize Manager References
- Resolve Current Ghost Id
- Restore Puzzle from Save
- Get World Mode
- Start Next Valid Puzzle for Current Context
- Complete Objective
- Start Objective

## Branch Points
- Branch
- Switch on E_WorldMode

## Notes
- Has latent nodes: Yes
- Has error nodes: No
- Has warning nodes: No
