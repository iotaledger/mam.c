package(default_visibility = ["//visibility:public"])

cc_library(
    name = "buffers",
    srcs = ["buffers.c"],
    hdrs = ["buffers.h"],
    deps = [
        ":trits",
        "//mam:defs",
    ],
)

cc_library(
    name = "trits",
    srcs = ["trits.c"],
    hdrs = ["trits.h"],
    deps = [
        "//mam:defs",
        "@org_iota_common//common:errors",
        "@org_iota_common//common/trinary:trit_long",
        "@org_iota_common//common/trinary:trit_tryte",
    ],
)
