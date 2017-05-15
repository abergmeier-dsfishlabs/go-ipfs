
workspace(name = "io_ipfs_go-ipfs")

# Import Go rules and toolchain.
http_archive(
    name = "io_bazel_rules_go",
    url = "https://github.com/bazelbuild/rules_go/archive/0.4.4.zip",
    strip_prefix = "rules_go-0.4.4",
)
load("@io_bazel_rules_go//go:def.bzl", "go_repositories")

http_archive(
    name = "io_ipfs_go-cid",
    url = "https://github.com/ipfs/go-cid/archive/7e7f6811b40a5d049c3036defc53faa0af86716e.zip",
    strip_prefix = "7e7f6811b40a5d049c3036defc53faa0af86716e-7e7f6811b40a5d049c3036defc53faa0af86716e",
)

http_archive(
    name = "io_multiformats_go-multihash",
    url = "https://github.com/multiformats/go-multihash/archive/7aa9f26a231c6f34f4e9fad52bf580fd36627285.zip",
    strip_prefix = "7aa9f26a231c6f34f4e9fad52bf580fd36627285-7aa9f26a231c6f34f4e9fad52bf580fd36627285",
)

