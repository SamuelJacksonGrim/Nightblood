# Nightblood

[![License: AGPL-3.0-only](https://img.shields.io/badge/license-AGPL--3.0--only-blue)](LICENSE)
[![dual-license](https://img.shields.io/badge/dual--license-AGPL--3.0--only%20or%20commercial-blueviolet)](LICENSING.md)
[![C++](https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=white)](https://isocpp.org)

## License

This project is dual-licensed under **AGPL-3.0-only** OR a commercial license.

- [LICENSE](LICENSE) — GNU AGPL-3.0-only (the free track)
- [LICENSING.md](LICENSING.md) — how the two tracks work
- [COMMERCIAL-LICENSE.md](COMMERCIAL-LICENSE.md) — the commercial agreement
- [NOTICE](NOTICE) — copyright, SPDX identifier, and provenance

```text
Nightblood/
│
├── CMakeLists.txt                # (If you choose to use CMake later)
│
├── build/                        # Compiled binaries + build artifacts
│   └── (placeholder)
│
├── include/                      # Public headers
│   ├── engine.h
│   ├── core/
│   │   ├── logger.h
│   │   ├── time.h
│   │   └── config.h
│   ├── math/
│   │   ├── vector2.h
│   │   ├── vector3.h
│   │   └── matrix4.h
│   ├── ecs/
│   │   ├── entity.h
│   │   ├── component.h
│   │   └── system.h
│   └── rendering/
│       ├── renderer.h
│       └── window.h
│
├── src/                          # Source files
│   ├── main.cpp
│   ├── engine.cpp
│   ├── core/
│   │   ├── logger.cpp
│   │   ├── time.cpp
│   │   └── config.cpp
│   ├── math/
│   │   ├── vector2.cpp
│   │   ├── vector3.cpp
│   │   └── matrix4.cpp
│   ├── ecs/
│   │   ├── entity.cpp
│   │   ├── component.cpp
│   │   └── system.cpp
│   └── rendering/
│       ├── renderer.cpp
│       └── window.cpp
│
├── assets/                       # Images, audio, shaders, etc.
│   └── (placeholder)
│
├── docs/                         # Documentation, design notes
│   └── architecture.md
│
└── tests/                        # Unit tests (if you add them later)
    └── (placeholder)
```
