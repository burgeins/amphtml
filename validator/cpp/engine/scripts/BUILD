package(default_visibility = ["//visibility:public"])

licenses(["notice"])

cc_binary(
    name = "filecontents_to_cpp_header",
    srcs = [
        "filecontents_to_cpp_header.cc",
    ],
    deps = [
        "@htmlparser//:defer",
    ],
)

cc_binary(
    name = "validator_example",
    srcs = [
        "validator_example.cc",
    ],
    deps = [
        "@ampvalidator//:validator",
        "@validator//:validator_cc_proto",
    ],
)
