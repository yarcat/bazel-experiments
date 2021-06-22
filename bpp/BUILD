load("@rules_foreign_cc//foreign_cc:defs.bzl", "cmake")

cmake(
	name = "bpp_core_lib",
	lib_name = "libbpp-core",
	lib_source = "@bpp_core//:all",
)

cmake(
    name = "bpp_seq_lib",
    lib_name = "libbpp-seq",
    lib_source = "@bpp_seq//:all",
    deps = [":bpp_core_lib"],
)
