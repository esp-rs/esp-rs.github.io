## Rust on ESP Community

This organization is home to a number of community projects enabling the use of the [Rust programming language] on various SoCs and modules produced by [Espressif Systems].

If you are just getting started with writing Rust for ESP devices, please first read [The Rust on ESP book].

For a curated list of resouces for development including tools and projects, see [Awesome ESP Rust].

[rust programming language]: https://www.rust-lang.org/
[espressif systems]: https://www.espressif.com/
[the rust on esp book]: https://esp-rs.github.io/book/
[Awesome ESP Rust]: https://github.com/esp-rs/awesome-esp-rust

### Build Tools

This organization contains a fork of the Rust compiler with added support for the Xtensa ISA. Pre-built binaries for said compiler fork are additionally provided for most common operating systems and architectures.

| Repository          | Description                                                             |
| ------------------- | ----------------------------------------------------------------------- |
| [esp-rs/rust]       | Rust compiler fork with Xtensa support                                  |
| [esp-rs/rust-build] | Pre-built binaries of the Rust compiler fork, plus installation scripts |

[esp-rs/rust]: https://github.com/esp-rs/rust
[esp-rs/rust-build]: https://github.com/esp-rs/rust-build

### Hardware Abstraction Layer

We offer two choices for **H**ardware **A**bstraction **L**ayers:

| Repository           | Description                                                | Documentaton       |
| -------------------- | ---------------------------------------------------------- |--------------------|
| [esp-rs/esp-idf-hal] | _With_ support for the Rust standard library (`std`)       | [docs/esp-idf-hal] |
| [esp-rs/esp-hal]     | _Without_ support for the Rust standard library (`no_std`) | [docs/esp-hal]     |

[esp-rs/esp-idf-hal]: https://github.com/esp-rs/esp-idf-hal
[esp-rs/esp-hal]: https://github.com/esp-rs/esp-hal
[docs/esp-idf-hal]: https://docs.esp-rs.org/esp-idf-hal/esp_idf_hal/
[docs/esp-hal]: https://docs.esp-rs.org/esp-hal/

### Peripheral Access Crates

The repository [esp-pacs] contains Peripheral Access Crates for Espressif SoCs and modules.

[esp-pacs]: https://github.com/esp-rs/esp-pacs
