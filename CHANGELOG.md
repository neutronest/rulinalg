# Change Log

This document will be used to keep track of changes made between release versions. I'll do my best to note any breaking changes!

## 0.2.0

### Breaking Changes

- Upper Hessenberg decomposition now consumes the input `Matrix` (instead of cloning at the start).

### Features

- Added Bidiagonal decomposition.
- Added Singular Value Decomposition.

### Minor Changes

- Fixed a bug where `get_unchecked_mut` returned `&T` instead of `&mut T`.

## 0.1.0

This release marks the separation of rulinalg from [rusty-machine](https://github.com/AtheMathmo/rusty-machine).

Rulinalg is now its own crate!