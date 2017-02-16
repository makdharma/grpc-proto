bind(
    name = "protobuf",
    actual = "@submodule_protobuf//:protobuf",
)

bind(
    name = "protobuf_clib",
    actual = "@submodule_protobuf//:protoc_lib",
)

bind(
    name = "protocol_compiler",
    actual = "@submodule_protobuf//:protoc",
)

#git_repository(
#    name   = "submodule_protobuf_prime",
#    commit = "593e917c176b5bc5aafa57bf9f6030d749d91cd5", # v3.2.0
#    remote = "https://github.com/google/protobuf.git",
#)

#bind(
#    name   = "gflags",
#    actual = "@com_github_gflags_gflags//:gflags",
#    #actual = "//third_party/gflags",
#)
#
new_local_repository(
    name = "submodule_protobuf",
    path = "third_party/protobuf",
    build_file = "third_party/protobuf/BUILD",
)
