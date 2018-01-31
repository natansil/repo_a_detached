package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library", "scala_specs2_junit_test")

scala_library(
    name = "scala_example2",
    srcs = [
        "Example2.scala",
    ],
)

scala_specs2_junit_test(
    name = "scala_example_test",
    size = "small",
    srcs = ["ExampleTest.scala"],
    suffixes = ["Test"],
    deps = ["@repo_a_inner_project//scala/com/example:scala_example"],
)
