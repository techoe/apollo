load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "perception_obstacle_camera_cipv",
    srcs = ["cipv.cpp"],
    hdrs = ["cipv.h"],
    deps = [
        "@eigen//:eigen",
        "//modules/perception/lib/base:base",
        "//modules/perception/lib/config_manager:config_manager",
        "//modules/perception/obstacle/camera/common:perception_obstacle_camera_common",
        "//modules/perception/obstacle/camera/lane_post_process/common:perception_obstacle_camera_lane_post_process",
        "//modules/perception/obstacle/camera/cipv:perception_obstacle_camera_cipv"
    ]
)

cpplint()
