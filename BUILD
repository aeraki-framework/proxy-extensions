package(default_visibility = ["//visibility:public"])

load(
    "@envoy//bazel:envoy_build_system.bzl",
    "envoy_cc_binary",
)

envoy_cc_binary(
    name = "envoy",
    repository = "@envoy",
    deps = [
        "//src/extensions/network/dubbo_rbac:config_lib",
        "@envoy//source/exe:envoy_main_entry_lib",
    ],
)
