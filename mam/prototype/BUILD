package(default_visibility = ["//visibility:public"])

cc_library(
    name = "mam",
    srcs = ["mam.c"],
    hdrs = ["mam.h"],
    deps =
        [
            ":mask",
            "@org_iota_common//common/crypto/curl-p:hamming",
            "@org_iota_common//common/trinary:trit_long",
            "@org_iota_common//utils:merkle",
        ],
)

cc_library(
    name = "mask",
    srcs = ["mask.c"],
    hdrs = ["mask.h"],
    deps =
        [
            "@org_iota_common//common/crypto/curl-p:trit",
            "@org_iota_common//common/trinary:add",
        ],
)
