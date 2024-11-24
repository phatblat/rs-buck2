# BUCK

# A list of available rules and their signatures can be found here: <https://buck2.build/docs/prelude/globals/>

genrule(
    name = "hello_world",
    out = "out.txt",
    cmd = "echo BUILT BY BUCK2> $OUT",
)

cxx_binary(
    name = "main",
    srcs = ["main.cpp"],
    link_style = "static",
)
