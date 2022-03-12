###############################################################################

plugin_extra_include_dirs = include_directories([
    'JuceLibraryCode',
])

if linux_embed
    plugin_srcs = files([
    ])
else
    plugin_srcs = files([
        'source/CombFilter.cpp',
        'source/DelayLine.cpp',
        'source/Envelope.cpp',
        'source/Filter.cpp',
        'source/Grain.cpp',
        'source/GrainParametersGenerator.cpp',
        'source/Granulator.cpp',
        'source/Parameters.cpp',
        'source/PitchQuantizer.cpp',
        'source/Plugin.cpp',
        'source/PluginEditor.cpp',
        'source/Program.cpp',
        'source/ProgramBank.cpp',
        'source/TimeQuantizer.cpp',
    ])
endif

plugin_name = 'argotlunar'

###############################################################################
