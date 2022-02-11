eigen_dep = declare_dependency(include_directories: [
  'eigen'
])

rply_lib = static_library('rply', [
  'rply/rply.c'
])
rply_dep = declare_dependency(link_with: rply_lib, include_directories: ['rply'])