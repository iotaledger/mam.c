cc_test(
    name = "test_mam",
    timeout = "long",
    srcs = ["test_mam.c"],
    linkopts = ["-lpthread"],
    deps =
        [
            "//mam/prototype:mam",
            "@org_iota_common//common/trinary:trit_tryte",
            "@unity",
        ],
)

cc_test(
    name = "test_mask",
    timeout = "short",
    srcs = ["test_mask.c"],
    deps =
        [
            "//mam/prototype:mask",
            "@org_iota_common//common/trinary:trit_tryte",
            "@unity",
        ],
)
