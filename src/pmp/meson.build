

pmp_lib = static_library('pmp', [
  'surface_mesh.cpp',
  'algorithms/curvature.cpp',
  'algorithms/decimation.cpp',
  'algorithms/differential_geometry.cpp',
  'algorithms/distance_point_triangle.cpp',
  'algorithms/fairing.cpp',
  'algorithms/features.cpp',
  'algorithms/geodesics.cpp',
  'algorithms/hole_filling.cpp',
  'algorithms/laplace.cpp',
  'algorithms/normals.cpp',
  'algorithms/numerics.cpp',
  'algorithms/parameterization.cpp',
  'algorithms/remeshing.cpp',
  'algorithms/shapes.cpp',
  'algorithms/smoothing.cpp',
  'algorithms/subdivision.cpp',
  'algorithms/triangulation.cpp',
  'algorithms/utilities.cpp',
  'io/io.cpp',
  'io/read_obj.cpp',
  'io/read_off.cpp',
  'io/read_pmp.cpp',
  'io/read_stl.cpp',
  'io/write_obj.cpp',
  'io/write_off.cpp',
  'io/write_pmp.cpp',
  'io/write_stl.cpp'
],

include_directories: [
  '..'
],
dependencies: [
  eigen_dep,
],
cpp_args: [
  '-D_USE_MATH_DEFINES'
])

pmp_dep = declare_dependency(link_with: pmp_lib, include_directories: ['..'], dependencies: [eigen_dep] )