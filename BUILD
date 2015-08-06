cc_library(
  name = "gumbo",
  srcs = glob(["src/gumbo/*.c"]),
  hdrs = glob(["src/gumbo/*.h"]),
  copts = ["-std=c99","-O3"],
)

cc_library(
  name = "litehtml",
  srcs = glob(["src/*.cpp"]),
  hdrs = ["include/litehtml.h"],
  deps = [
    ":gumbo"
  ],
  copts = ["-std=c++11","-O3"],
)