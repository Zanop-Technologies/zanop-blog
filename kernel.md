# The Zanop Kernel

Every Zanop product sits on the **Zanop Kernel**, written from scratch in C++ targeting x86_64. It was never written for one device — the same kernel is meant to carry several operating systems.

- Repository: <https://github.com/Zanop-Technologies/zanop-kernel>
- Language: C++ (with the OS itself)
- License: AGPL-3.0

## What the kernel runs

| Variant             | What it is                                               |
| ------------------- | -------------------------------------------------------- |
| Zanop Desktop OS    | Desktop build; applications are packaged as `.sft` files |
| Zanop Mobile OS     | Build aimed at phones (planned)                          |
| Zanop Television OS | Build for televisions and set-top boxes (planned)        |
| Zanop Server OS     | Server build                                             |

## Features

- Open source (AGPL-3.0)
- Custom GUI
- Does not use UNIX commands — see [ECMXS](ecmxs.md)

## Getting involved

The kernel is the heart of the project. See [Contributing](contributing.md) to get started.
