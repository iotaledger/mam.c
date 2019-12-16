cc_library(
    name = "prng",
    srcs = ["prng.c"],
    hdrs = ["prng.h"],
    visibility = ["//visibility:public"],
    deps = [
        "//mam:defs",
        "//mam/pb3",
        "//mam/sponge",
        "//mam/trits",
        "@org_iota_common//common:errors",
        "@org_iota_common//utils:memset_safe",
    ],
)
