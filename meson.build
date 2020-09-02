project('libfontenc', 'c',
  version : '1.1.4',
  license : 'MIT')
add_global_arguments('-DFONT_ENCODINGS_DIRECTORY="/usr/share/font"', language : 'c')
zlib_dep = dependency('zlib')

inc = include_directories('include')

subdir('include')
subdir('src')

pkg_mod = import('pkgconfig')
pkg_mod.generate(libraries : fontenclib,
                 version : '1.1.4',
                 name : 'fontenc',
                 filebase : 'fontenc',
                 description : 'The fontenc Library')

