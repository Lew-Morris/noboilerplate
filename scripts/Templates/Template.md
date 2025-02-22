<style>
:root {--r-code-font: "FiraCode Nerd Font";}
.reveal .hljs {min-height: 50%;}
</style>
%%

f7f7f7 background slide colour

# Cargo.toml 
```toml
[package]
name = "template"
version = "0.1.0"
edition = "2021"

[build-dependencies]

[dev-dependencies]

[dependencies]
```

# Lint tweaks
```rust
#![allow(dead_code)]
#![allow(unused_variables)]
```

# extern crates

```rust

```

# imports
```rust
```

# setup

```rust
fn main() {
	println!("Rust talk");

```
%%

![[rust-logo.png]]

# RUST: TITLE
Compiler-checked markdown video scripts:
[github.com/0atman/noboilerplate](github.com/0atman/noboilerplate)


notes:
%%
Tell them what you're going to tell them,
tell them,
then tell them what you told them.
%%
Hi friends my name is Tris and this is No Boilerplate, focusing on fast, technical videos.


---


## Open Source Videos

```sh
$ git clone git@github.com:0atman/noboilerplate.git
$ cd noboilerplate/scripts

$ make deps  # to install literate and cargo-watch
$ make build # produce a valid cargo project
$ cargo build
```

notes:

As ever, all Rust code you see in this video is part of a literate programming document that can be extracted and compiled with native Rust tooling.


---

# CONTENT HERE



---


![[rust-logo.png]]

# Subtitle 


notes:

# OUTTRO

If you would like to support my channel, get early ad-free and tracking-free videos and vip discord access head to patreon.com/noboilerplate.

If you're interested in transhumanism and hopepunk stories, please check out my sci-fi podcast, Lost Terminal.

Or if urban fantasy is more your bag, click the bottom video to listen to a strange and beautiful podcast I produce called Modem Prometheus.

Transcripts and compile-checked markdown sourcecode are available on github, links in the description, and corrections are in the pinned ERRATA comment.

Thank you so much for watching, talk to you on Discord.

```rust
  println!("That's all folks!");
} 
```