load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["harness.pb.go"],
    importpath = "github.com/lyft/protoc-gen-validate/tests/harness/go",
    visibility = ["//visibility:public"],
    deps = [
        "@com_github_golang_protobuf//proto:go_default_library",
        "@com_github_golang_protobuf//ptypes/any:go_default_library",
    ],
)
