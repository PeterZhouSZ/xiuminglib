# For blaze on Google's infra.

py_library(
    name = "xiuminglib",
    srcs = glob(["xiuminglib/**/*.py"]),
    data = glob(["data/**/*"]),
    srcs_version = "PY3",
    deps = [
        "//pyglib:gfile",
        "//third_party/py/cvx2",
        "//third_party/py/matplotlib",
        "//third_party/py/mpl_toolkits/axes_grid1",
        "//third_party/py/mpl_toolkits/mplot3d",
        "//third_party/py/numpy",
        "//third_party/py/scipy",
    ],
)
