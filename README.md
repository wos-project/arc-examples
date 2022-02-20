# arc-examples README #
Augmented Reality Creation (ARC) Examples

This is a collection of ARC examples.  ARCs are JSON-based files that describe augmented reality creations existing in a world.  ARCs can be pinned to a world location using coordinate system references.  The physical world uses geographic-based SRID 4326 elipsoidal degree decimal coordinates including elevation.  

ARCs begin with an index.json that include:

- version - version of the ARC format
- kind - what kind object it is
- metadata - key:value pairs that can include any descriptive information about the ARC
- spec - required information that defines the ARC

These examples include pinning objects, including pin points and paths.
