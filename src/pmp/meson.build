

pmp_lib = static_library('pmp', [
  'SurfaceMesh.cpp',
  'SurfaceMeshIO.cpp',
  'algorithms\DifferentialGeometry.cpp',
  'algorithms\DistancePointTriangle.cpp',
  'algorithms\SurfaceCurvature.cpp',
  'algorithms\SurfaceFactory.cpp',
  'algorithms\SurfaceFairing.cpp',
  'algorithms\SurfaceFeatures.cpp',
  'algorithms\SurfaceGeodesic.cpp',
  'algorithms\SurfaceHoleFilling.cpp',
  'algorithms\SurfaceNormals.cpp',
  'algorithms\SurfaceParameterization.cpp',
  'algorithms\SurfaceRemeshing.cpp',
  'algorithms\SurfaceSimplification.cpp',
  'algorithms\SurfaceSmoothing.cpp',
  'algorithms\SurfaceSubdivision.cpp',
  'algorithms\SurfaceTriangulation.cpp',
  'algorithms\TriangleKdTree.cpp',
],
include_directories: [
  '..'
],
dependencies: [
  eigen_dep,
  rply_dep,
],
cpp_args: [
  '-D_USE_MATH_DEFINES'
])

pmp_dep = declare_dependency(link_with: pmp_lib, include_directories: ['..'] )