load('//:subdir_glob.bzl', 'subdir_glob')

prebuilt_cxx_library(
  name = 'optional-lite',
  header_namespace = '',
  header_only = True,
  exported_headers = subdir_glob([
    ('include', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
)
