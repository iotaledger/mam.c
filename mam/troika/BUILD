package(default_visibility = ["//visibility:public"])

cc_library(
    name = "troika",
    srcs = ["troika.c"],
    hdrs = ["troika.h"],
    deps = [
        "@org_iota_common//common:stdint",
        "@org_iota_common//common/crypto/ftroika",
        "@org_iota_common//common/crypto/troika",
        "//mam:defs",
        "//mam/trits",
    ],
)
