owl - "Optix Wrappers Library" on top of Optix 7
================================================


Directory Structure
===================

- `owl/`: The Optix Wrappers *library*
  - `owl/ll/`: the owl *low-level* API layer
  - `owl/ng/`: the owl *node graph* API layer (currently disabled because not yet working)

- `samples/`: Samples/Tutorials/TestCases for OWL
  - `samples/ll/`: samples for the ll layer
  - `samples/ng/`: samples for the ng layer (currently disabled because not yet working)

Revision History
================

v0.3.x - User Geometries
------------------------

*v0.3.0*: First example of user geometry working

- can create user geometries through `createUserGeom`, and set
  type's isec program through `setGeomTypeIntersect`
- supports passing of new `userGeomSetBoundsBuffer` fct to pass user
  geoms through a buffer
- first example (8 sphere geometries, each with one sphere per geom)
  available as `s03-userGeometry`

v0.2.x
------

*v0.2.1*: multiple triangle meshes working
- multiple triangle meshes in same group debugged and working
- added `ll02-multipleTriangleGroups` sample that generates 8 boxes

*v0.2.0*: first triangle mesh with trace and SBT data working
- finalized `llTest` sample that ray traced image of one (tessellated) box

v0.1.x
------

- first version that does "some" sort of launch with mostly functional SBT
