include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'urdl',
  header_namespace = 'urdl',
  exported_headers = subdir_glob([
    ('include/urdl', '**/*.hpp'),
    ('include/urdl', '**/*.ipp'),
  ]),
  srcs = glob([
    'src/**/*.cpp',
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
