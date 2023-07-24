project('antijump', 'c')

cc = meson.get_compiler('c')

c_args = []
link_opts = []
dependencies = [
  dependency('raylib', version: '>=4.0.0')
]

inc_dir = include_directories('src')
sources = files('src/main.c')
executable('antijump',
  sources,
  c_args: c_args,
  dependencies: dependencies,
  include_directories: inc_dir,
  link_args: link_opts,
)
