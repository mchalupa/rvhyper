project(
  'rvhyper',
  'cpp',
  meson_version : '>= 1.3.0',
  version : '0.3.0-ista',
  default_options : ['warning_level=3', 'cpp_std=c++17'],
)


spot_dep = dependency('libspot', version: '2.8.7')

incdir = include_directories('include/rvhyper')

subdir('src')
subdir('include')

