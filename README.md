# DEPRECATED
This repository has been incorporated into
[toradex/torizon-containers](https://github.com/toradex/torizon-containers).

# debian-cross-toolchains

Base images for cross-compiling toolchains.

For each architecture there is a base container named
torizon/debian-cross-toolchain-ARCHITECTURE and one that can be used via ssh
(it stars sshd on startup) named
torizon/debian-cross-toolchain-ssh-ARCHITECTURE

The SSH container has user/password build/build

## License
This project is licensed under the terms of MIT license - see `LICENSE`.
