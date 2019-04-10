project('tomlc99', 'c')
  
inc = include_directories('.')
tomlc99 = static_library('toml', 'toml.c', include_directories : '.', install : true)
tomlc99_dep = declare_dependency(include_directories : '.', link_with : tomlc99)
