filegroup(
    name = "plz_e2e_test",
    srcs = ["plz_e2e_test.build_defs"],
    visibility = ["//test/..."],
)

filegroup(
    name = "fpm",
    srcs = ["fpm.build_defs"],
    visibility = ["//package:all"],
)

filegroup(
    name = "signing",
    srcs = ["signing.build_defs"],
    visibility = ["//package:all"],
)

filegroup(
    name = "multiversion_wheel",
    srcs = ["multiversion_wheel.build_defs"],
    visibility = ["//third_party/python:all"],
)

filegroup(
    name = "ansi_escapes",
    srcs = ["ansi_escapes.build_defs"],
    visibility = ["//src/output:all"],
)

genrule(
    name = "version",
    srcs = ["//:version"],
    outs = ["version.build_defs"],
    cmd = "echo \"VERSION = '`cat $SRCS`'\" > $OUT",
    visibility = ["PUBLIC"],
)

filegroup(
    name = "maven_library",
    srcs = ["maven_library.build_defs"],
    visibility = ["//tools/javac_worker:all"],
)
