project('gtkd-utils', 'd')

gtkd_dep = dependency('gtkd-3')

gtkd_utils_lib = library(
    'gtkd-utils',
    'src/gtkutils.d',
    dependencies: [
        gtkd_dep
    ],
)

gtkd_utils_dep = declare_dependency(
    sources: 'src/gtkutils.d',
    link_with: gtkd_utils_lib,
    include_directories: include_directories('src/')
)
