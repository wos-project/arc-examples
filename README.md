# arc-examples README #
Augmented Reality Creation (ARC) Examples

This is a collection of ARC examples.  ARCs are JSON-based files that describe augmented reality creations that exist in a world.  ARCs can be pinned to a location in a world using a coordinate system for the world.  The physical world uses geographic-based degree decimal coordinates that include elevation.

ARCs begin with an index.json that include:

- version - version of the ARC format
- kind - what kind object it is
- metadata - key:value pairs that can include any descriptive information about the ARC
- spec - required information that defines the ARC
