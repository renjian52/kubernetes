package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = ["proxy.go"],
    tags = ["automanaged"],
    deps = [
        "//pkg/api:go_default_library",
        "//pkg/api/rest:go_default_library",
        "//pkg/capabilities:go_default_library",
        "//pkg/genericapiserver/api/request:go_default_library",
        "//pkg/kubelet/client:go_default_library",
        "//pkg/registry/core/node:go_default_library",
        "//pkg/registry/generic/registry:go_default_library",
        "//pkg/registry/generic/rest:go_default_library",
        "//pkg/runtime:go_default_library",
    ],
)
