load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "exitcode",
    srcs = ["exitcode.go"],
    importpath = "learn/golang/scratch/exitcode",
    visibility = ["//visibility:public"],
)

go_test(
    name = "exitcode_test",
    srcs = ["exitcode_test.go"],
    embed = [":exitcode"],
)
