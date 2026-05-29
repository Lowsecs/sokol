project('sokol', 'c',
        version : '1.0.0',
        default_options : ['warning_level=1'])

# Sokol is a header-only library
sokol_inc = include_directories('.')

sokol_dep = declare_dependency(
    include_directories : sokol_inc
)

set_variable('sokol_dep', sokol_dep)
set_variable('sokol_inc', sokol_inc)