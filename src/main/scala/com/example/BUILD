package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library", "scala_specs2_junit_test")

scala_library(
    name = "scala_example",
    srcs = [
        "Example.scala",
    ],
    deps = ["@repo_a//src/test/scala/com/example:scala_example2"],
)
