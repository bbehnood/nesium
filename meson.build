project(
  'nesium',
  'cpp',
  default_options: [
    'cpp_std=c++17',
    'warning_level=3' 
  ]
)

add_project_arguments(
  language: 'cpp'
)

src = files(
  'src/main.cpp',
)

inc = include_directories('include')

executable(
  'nesium',
  src,
  include_directories: inc,
)
