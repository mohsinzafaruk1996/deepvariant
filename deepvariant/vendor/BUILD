# load("//devtools/python/blaze:python3.bzl", "py2and3_test")

package(
    default_visibility = [
        "//visibility:public",
    ],
)

py_library(
    name = "timer",
    srcs = ["timer.py"],
)

py_test(
    name = "timer_test",
    size = "small",
    srcs = ["timer_test.py"],
    python_version = "PY3",
    srcs_version = "PY3",
    deps = [
        ":timer",
        "@absl_py//absl/testing:absltest",
    ],
)
