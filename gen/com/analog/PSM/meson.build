# Generated file; do not modify.
generated_sources += custom_target(
    'com/analog/PSM__cpp'.underscorify(),
    input: [ '../../../../yaml/com/analog/PSM.errors.yaml',  ],
    output: [ 'error.cpp', 'error.hpp',  ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'cpp',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/analog/PSM',
    ],
)

subdir('FaultLog')
generated_others += custom_target(
    'com/analog/PSM/FaultLog__markdown'.underscorify(),
    input: [ '../../../../yaml/com/analog/PSM/FaultLog.interface.yaml',  ],
    output: [ 'FaultLog.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/analog/PSM/FaultLog',
    ],
)

