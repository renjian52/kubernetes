package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
    "go_test",
)

go_library(
    name = "go_default_library",
    srcs = ["basicauth.go"],
    tags = ["automanaged"],
    deps = [
        "//pkg/auth/authenticator:go_default_library",
        "//vendor:k8s.io/apiserver/pkg/authentication/user",
    ],
)

go_test(
    name = "go_default_test",
    srcs = ["basicauth_test.go"],
    library = ":go_default_library",
    tags = ["automanaged"],
    deps = [
        "//pkg/auth/authenticator:go_default_library",
        "//vendor:k8s.io/apiserver/pkg/authentication/user",
    ],
)
