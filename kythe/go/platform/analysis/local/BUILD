load("@io_bazel_rules_go//go:def.bzl", "go_library")

package(default_visibility = ["//kythe:default_visibility"])

go_library(
    name = "local",
    srcs = ["local.go"],
    deps = [
        "//kythe/go/platform/analysis",
        "//kythe/go/platform/analysis/driver",
        "//kythe/go/platform/kindex",
    ],
)
