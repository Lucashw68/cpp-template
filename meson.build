##
## LUCASHW PROJECT, 2020
## Template
##

project('cpp-template', 'cpp', default_options : ['cpp_std=c++1z'], version: '1.0')

# Sources ======================================================================

main_src = ['Sources/Main/main.cpp']

sources = [main_src]

# Includes =====================================================================

main_inc = ['Sources/Main']

includes = [main_inc]

# Dependencies =================================================================

  # Example: sfml = dependency('sfml-graphics')

# Arguments ====================================================================

arguments=['-W', '-Wall', '-Wextra', '-Werror', '-Wfatal-errors', '-Wpedantic', '-ansi', '-g', '-std=c++17']

# Executable

executable('template', sources, dependencies: [], include_directories: include_directories(includes), cpp_args: arguments)
