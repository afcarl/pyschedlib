py_library(
    name = "job",
    srcs = ["job.py"],
    deps = [":logger"],
)

py_library(
    name = "slurm",
    srcs = ["slurm.py"],
    deps = [":logger", ":job"],
    visibility = ["//visibility:public"],
)

py_library(
    name = "local",
    srcs = ["local.py"],
    deps = [":logger", ":job"],
    visibility = ["//visibility:public"],
)

py_library(
    name = "logger",
    srcs = ["logger.py"],
    deps = [],
)
