load("@io_bazel_rules_go//go:def.bzl", "go_binary")

# gazelle:ignore

go_binary(
    name = "hello",
    srcs = ["hello.go"],
    deps = ["//golang/with-tests/hello:hello"],
    visibility = ["//visibility:public"],
)

go_binary(
    name = "greetserver",
    srcs = ["greetserver.go"],
    deps = ["//golang/with-tests/greet:greet"],
    visibility = ["//visibility:public"],
)
