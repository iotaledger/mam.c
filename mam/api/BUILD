package(default_visibility = ["//visibility:public"])

load("@org_iota_common//utils/containers:map_generator.bzl", "map_generate")

cc_library(
    name = "api",
    srcs = ["api.c"],
    hdrs = ["api.h"],
    deps = [
        ":trit_t_to_mam_msg_read_context_t_map",
        ":trit_t_to_mam_msg_write_context_t_map",
        "//mam/mam:message",
        "@org_iota_common//common:errors",
        "@org_iota_common//common/model:bundle",
        "@org_iota_common//utils:time",
    ],
)

map_generate(
    additional_deps = ["//mam/mam:message"],
    additional_include_path = "mam/mam/message.h",
    key_type = "trit_t",
    parent_directory = "mam/api",
    value_type = "mam_msg_write_context_t",
)

map_generate(
    additional_deps = ["//mam/mam:message"],
    additional_include_path = "mam/mam/message.h",
    key_type = "trit_t",
    parent_directory = "mam/api",
    value_type = "mam_msg_read_context_t",
)
