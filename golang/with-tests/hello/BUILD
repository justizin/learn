load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "hello",
    srcs = ["hello.go"],
    importpath = "learn/golang/with-tests/hello",
    visibility = ["//visibility:public"],
)

go_test(
    name = "hello_test",
    srcs = ["hello_test.go"],
    embed = [":hello"],
)
