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
