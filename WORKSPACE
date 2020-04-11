load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

http_archive(
    name = "cpprest",
    build_file = "third_party/cpprestsdk/BUILD",
    sha256 = "23c217fcfc8f8ec86744f4f68039bb5c3604d17087e457e21cb105635fd56d44",
    urls = ["https://github.com/microsoft/cpprestsdk/archive/v2.10.15.zip"],
)

git_repository(
    name = "boringssl",
    commit = "efddb248cb6ca0471ed15764cf60345d417dc497",
    remote = "https://github.com/google/boringssl.git",
)
