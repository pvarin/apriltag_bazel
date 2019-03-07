load("@bazel_tools//tools/build_defs/repo:git.bzl", "new_git_repository")

# Apriltags
new_git_repository(
    name = 'apriltags',
    build_file = 'apriltags.BUILD.bazel',
    remote = 'https://github.com/AprilRobotics/apriltags',
    # commit='master',
    commit='c89cf4cad4216db79da0a1fc1f5f81a54e3d2e2f',
)

# OpenCV
new_local_repository(
    name = 'opencv',
    build_file = 'external/opencv.BUILD.bazel',
    path = "/usr/local",
)
