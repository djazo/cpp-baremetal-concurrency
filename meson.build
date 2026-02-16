project(
    'baremetal-concurrency',
    ['cpp'],
    license: 'BSL-1.0',
    version: '0.1.0',
    default_options: ['cpp_std=c++23'],
    meson_version: '>=1.1',
)

inc = include_directories('include')
add_project_arguments('-DSIMULATE_FREESTANDING', language: 'cpp')

baremetal_concurrency_dep = declare_dependency(
    include_directories: inc,
    compile_args: ['-DSIMULATE_FREESTANDING'],
)
