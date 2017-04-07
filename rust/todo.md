# To-do list for Rust implemenation
- [DONE] Wrapper around existing C API.
- [DONE] Integrated bindgen so we can test against C API in the unit tests.
- [DONE] Serialize all packet + token(challenge & connection) in a form that's compatible with C API.
- [DONE] Add connect() support to mio.
- [DONE] Socking mocking scaffold to swap zero-cost implemenations.
- [DONE] Build on *nix platforms(should be drop-in but need to verify).
- [TODO] Use better mechanism to find libsodium on linux.
- [TODO] Working server implemenation.
- [TODO] In-place libsodium decode.
- [TODO] Appveyor/travis.ci auto-build.
- [TODO] Socket mocking layer to introduce latency/dropped packets for testing.