project('hello_library', 'cpp',
  version : '0.1',
  default_options : ['warning_level=3'])

src = ['src/hello.cpp']

# Create a shared library
libhello = shared_library('hello', src)

# Define a header file to install
install_headers('src/hello.h')

