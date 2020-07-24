load("@rules_foreign_cc//tools/build_defs:cmake.bzl", "cmake_external")

cmake_external(
	name = "bpp_core_lib",
	lib_name = "libbpp-core",
	lib_source = "@bpp_core//:all",
)

cmake_external(
    name = "bpp_seq_lib",
    lib_name = "libbpp-seq",
    lib_source = "@bpp_seq//:all",
    deps = [":bpp_core_lib"],
)
