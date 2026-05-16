![Draft for review only](https://isotc204.org/assets/img/draft_for_review.svg)

# ITS Location Referencing Core

Core abstractions for spatial concepts, including features, geometries, and feature collections used across multiple location-referencing methodologies.

This pattern imports the following files:

- [https://w3id.org/itsdata/core/v1/](https://w3id.org/itsdata/core/v1/)

This pattern consists of the following classes:

- [Coded Geometry](CodedGeometry.md)
- [Coordinate Geometry](CoordinateGeometry.md)
- [Coordinate Reference System](CoordinateReferenceSystem.md)
- [Feature](Feature.md)
- [Geometry](Geometry.md)
- [Location Code](LocationCode.md)
- [Location Group](LocationGroup.md)
- [Location Thing](LocationThing.md)
- [Spatial Object](SpatialObject.md)
This module defines the following properties:

- [coordinateEpoch](../properties/coordinateEpoch.md)
- [geometryOf](../properties/geometryOf.md)
- [hasCRS](../properties/hasCRS.md)
- [hasLookupCode](../properties/hasLookupCode.md)
- [hasMember](../properties/hasMember.md)
- [LocationDataProperty](../properties/LocationDataProperty.md)
- [LocationObjectProperty](../properties/LocationObjectProperty.md)


The formal definition of this pattern is available in TURTLE Syntax in two files, the [core semantics](../core-pattern.ttl) and the SHACL [restrictions](../core-shacl.ttl).
