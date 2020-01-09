# tar
Rust Gamification Bot (Studying Only)

## How to

To run this project, use the `cargo run` command

### Errors

If the following error occurs while executing the command

```bash
error[E0432]: unresolved import `std::boxed::FnBox`
 --> /home/[username]/.cargo/registry/src/github.com-1ecc6299db9ec823/rocket-0.4.1/src/fairing/ad_hoc.rs:2:5
  |
2 | use std::boxed::FnBox;
  |     ^^^^^^^^^^^^^^^^^ no `FnBox` in `boxed`
```

Just update the Rocket framework by running the `cargo update` command (Reference)
