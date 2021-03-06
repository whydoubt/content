---
title: Format Rust code
subsection: rust
order: 3
---

# Format Rust code

`rustfmt` is a tool for formatting Rust source code. You can install it using Cargo:

```
$ cargo install rustfmt
```

This will install an executable into `~/.cargo/bin/`. In order to use it, add it into your `$PATH` variable. In case you are using Bash, follow these steps:

```
$ echo 'export PATH=$PATH:$HOME/.cargo/bin' >> $HOME/.bashrc
$ source $HOME/.bashrc
```

Now you can use `rustfmt` to format either a single file or the whole project:

* Single file:
```
$ rustfmt src/main.rs
```

* Project:
```
$ cargo fmt
```
