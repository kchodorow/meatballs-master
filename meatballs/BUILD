cc_library(
    name = "meatballs",
    srcs = ["pile_of_meatballs.cc"],
)

cc_test(
    name = "end_to_end_test",
    srcs = ["end_to_end_test.cc"],
    deps = [
        ":meatballs",
        "//spaghetti",
    ],
)
