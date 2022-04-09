cc_binary (
  name = "hello_world",
  srcs = ["hello_world.cc"]
)

cc_library (
  name = "example_lib",
  hdrs = [
    "example_lib.h"
  ]
)

cc_test (
  name = "example_lib_test",
  srcs = ["example_lib_test.cc"],
  deps = [":example_lib"]
)