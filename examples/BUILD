load("@io_bazel_rules_rust//rust:rust.bzl", "rust_binary")

rust_binary(
    name = "hello_world",
    srcs = ["hello_world.rs"],
    crate_type = "cdylib",
    edition = "2018",
    out_binary = True,
    deps = [
        "//:proxy_wasm",
        "//cargo:chrono",
        "//cargo:log",
    ],
)

rust_binary(
    name = "http_auth_random",
    srcs = ["http_auth_random.rs"],
    crate_type = "cdylib",
    edition = "2018",
    out_binary = True,
    deps = [
        "//:proxy_wasm",
        "//cargo:log",
    ],
)

rust_binary(
    name = "http_headers",
    srcs = ["http_headers.rs"],
    crate_type = "cdylib",
    edition = "2018",
    out_binary = True,
    deps = [
        "//:proxy_wasm",
        "//cargo:log",
    ],
)

rust_binary(
    name = "http_body",
    srcs = ["http_body.rs"],
    crate_type = "cdylib",
    edition = "2018",
    out_binary = True,
    deps = [
        "//:proxy_wasm",
        "//cargo:log",
    ],
)
