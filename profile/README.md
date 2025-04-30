## Welcome to the `flarrow` project!

The `flarrow` project is a collection of libraries and binaries that provide a fast and efficient way to make dataflow applications.

It's split into multiple main modules:

- [`flarrow-runtime`](https://github.com/flarrow-rs/flarrow-runtime): Provides the main crates to make it possible to build and run dataflow applications on a single runtime (single machine).
- [`flarrow-runtime-plan`](): Provides a way to build and run dataflow applications with a YAML plan. It also provides the CLI `flr-runtime`.

- [`flarrow-daemon`](): Provides a way to define and run dataflow applications on a distributed system with multiple runtimes.
- [`flarrow-daemon-plan`](): Provides a way to build and run dataflow applications with a YAML plan. It also provides the CLI `flr-daemon`.

- [`flarrow-cli`](): Provides a CLI `flr` to make projects, build applications and run them.

By nature a `runtime` can be pluggable, meaning that it can be easily extended to support new features or integrate with other systems. Here are the
official plugins:

- [`flarrow-python`](https://github.com/flarrow-rs/flarrow-python): Provides a Python **node** API and a `.py` **FileExtPlugin** for the runtime.
