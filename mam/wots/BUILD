cc_library(
    name = "wots",
    srcs = ["wots.c"],
    hdrs = ["wots.h"],
    visibility = ["//visibility:public"],
    deps = [
        "//mam:defs",
        "//mam/prng",
        "//mam/sponge:spongos",
        "//mam/trits",
        "@org_iota_common//common:errors",
        "@org_iota_common//utils:memset_safe",
    ],
)
