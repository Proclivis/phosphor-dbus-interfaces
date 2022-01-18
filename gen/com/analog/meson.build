# Generated file; do not modify.
subdir('PSM')
generated_others += custom_target(
    'com/analog/PSM__markdown'.underscorify(),
    input: [ '../../../yaml/com/analog/PSM.errors.yaml',  ],
    output: [ 'PSM.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../yaml',
        'com/analog/PSM',
    ],
)
