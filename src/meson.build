fontenc_sources = ['encparse.c', 'fontenc.c']
fontenclib = shared_library('fontenc',
                        fontenc_sources,
                        include_directories : inc,
						version : '1.0.0',
						soversion : '1',
                        dependencies : zlib_dep,
                        install : true)

install_headers('libfontenc.la', install_dir : 'lib')



