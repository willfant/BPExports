# EventGraph

## Graph Type
EventGraph

## Purpose
Main runtime entry graph for this Blueprint.

## Reads
- DebugEnabled

## Writes
- CurrentWorldMode
- CurrentGhostId
- CurrentGhostState

## Calls
- Initialize Audio Manager
- Debug Message
- To String (Text)
- Initialize World Mode Audio Binding
- Apply Resolved Audio State from Context
- Initialize Ghost Audio Binding

## Notes
- Has latent nodes: No
- Has error nodes: No
- Has warning nodes: No
