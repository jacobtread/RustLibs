# RustLibs

This is a collection of different things and what libraries I've found work best for each of those things



## Email 

Creating and sending emails

**Lettre**
[Docs.rs](https://docs.rs/lettre/latest/lettre/)
[Crates.io](https://crates.io/crates/lettre)
[GitHub](https://github.com/lettre/lettre)

Lettre works well and provides an easy to use async API for creating and sending emails.

## .env files

**dotenvy**
[Docs.rs](https://docs.rs/dotenvy/latest/dotenvy/)
[Crates.io](https://crates.io/crates/dotenvy)
[GitHub](https://github.com/allan2/dotenvy)


Well maintained fork of the dotenv crate


## Authentication

Working with authentication

Stateless authentication with Json Web Token


**jsonwebtoken**
[Docs.rs](https://docs.rs/jsonwebtoken/latest/jsonwebtoken/)
[Crates.io](https://crates.io/crates/jsonwebtoken)
[GitHub](https://github.com/Keats/jsonwebtoken)

jsonwebtoken good well rounded library with supports for many forms of JWT
along with validation

## Password Hashing

**Argon2**
[Docs.rs](https://docs.rs/argon2/latest/argon2/)
[Crates.io](https://crates.io/crates/argon2)
[GitHub](https://github.com/RustCrypto/password-hashes/tree/master/argon2)

Powerful and easy to use password hashing


## Form Validation

**validator**
[Docs.rs](https://docs.rs/validator/latest/validator/)
[Crates.io](https://crates.io/crates/validator)
[GitHub](https://github.com/Keats/validator)

Easy to use derive macro based struct validation


## Templating

File based templating for creating things like html pages
with data filled in at runtime

**sailfish**
[Docs.rs](https://docs.rs/sailfish/latest/sailfish/)
[Crates.io](https://crates.io/crates/sailfish)
[GitHub](https://github.com/rust-sailfish/sailfish)
[Website](https://rust-sailfish.github.io/sailfish/)

Super fast compile time templating using derive macros

**handlebars**
[Docs.rs](https://docs.rs/handlebars/latest/handlebars/)
[Crates.io](https://crates.io/crates/handlebars)
[GitHub](https://github.com/sunng87/handlebars-rust)

Runtime templating which can load many handlebars files from a directory


## Embedding files

**rust-embed**

[Docs.rs](https://docs.rs/rust-embed/latest/rust_embed/)
[Crates.io](https://crates.io/crates/rust-embed)
[GitHub](https://github.com/pyros2097/rust-embed)

Useful for embedding entire directories into your binary
