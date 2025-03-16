# hands-on-rust

Accompany my book Hands-on-Rust

## Requirements

Following packages are needed:
- sudo dnf install ncurses ncurses-devel (optional, use when no OpenGL)
- sudo dnf install fontconfig-devel

## Compiling

With Fedora and Wayland followings works:

$ WINIT_UNIX_BACKEND=x11 RUST_BACKTRACE=1 cargo run
