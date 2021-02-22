# Cesium 3D Metadata Specification

This specification defines a standard metadata format for 3D data. It define a set of core concepts to be used by multiple 3D formats, in particular 3D Tiles and glTF.

For actual use, refer to the implementations of this specification including:

* [`3DTILES_metadata`](../../../extensions/3DTILES_metadata) - 3D Tiles extension that assigns metadata to various components of 3D Tiles
* [`EXT_feature_metadata`](https://github.com/CesiumGS/glTF/pull/3) - glTF extension that assigns metadata to features in a model on a per-vertex or per-texel basis

See the [Cesium Metadata Semantic Reference](Semantics/README.md) for built-in semantics for 3D Tiles and glTF.

## Changelog

* [**Version 0.0.0**](0.0.0/README.md) November 6, 2020
    * Initial draft
* [**Version 1.0.0**](1.0.0/README.md) [TODO: date]
    * The specification has been revised to focus on the core concepts of schemas (including classes, enums, and properties) and formats for encoding metadata. It is now language independent. The JSON schema has been removed.
    * Added schemas which contain classes and enums
    * Added enum support
    * Added ability to assign a semantic identifiers to properties
    * Removed blob support
    * Removed special handling for fixed-length strings