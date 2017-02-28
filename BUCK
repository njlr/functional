include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'boost-functional',
  header_only = True,
  header_namespace = 'boost',
  exported_headers = subdir_glob([
    ('include/boost', ''),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
