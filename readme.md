# C3D Language

Welcome to **C3D**, a minimalist programming language designed specifically for 3D game engine development using OpenGL 3.3. C3D combines simple, readable syntax inspired by C++ and Python with the full power of native C++ interoperability, making it easier than ever to create complex 3D applications and engines.

## Features

- Modular system: Use `add moduleName;` to quickly include OpenGL, physics (Bullet), UI (ImGui), and more.
- High-level 3D APIs: Create and manipulate 3D objects with simple commands instead of verbose boilerplate.
- Event-driven structure: Write code in `on_init`, `on_update(dt)`, and `on_render` blocks.
- Raw C++ embedding: Drop down to native C++ whenever you need fine control.
- Focused on OpenGL 3.3 support for powerful and modern graphics.
- Designed to be both beginner-friendly and powerful enough for advanced developers.

## Getting Started

1. Clone this repository.
2. Follow the included documentation to set up your build environment.
3. Write your C3D programs using simple syntax and modules.
4. Use the transpiler to convert C3D code into C++.
5. Compile the generated C++ with your preferred toolchain.

## Roadmap

- Version 1.0: Core language, OpenGL 3.3 module, Bullet physics module.
- Version 2.0: Additional modules like ImGui, audio support, and improved scripting.
- Future: Multi-backend graphics, better tooling, and JIT compilation.

## License

C3D is distributed under a **custom license** that permits usage, modification, and redistribution of compiled outputs and programs created with C3D. The original source code of C3D and any modified versions of it **cannot be redistributed** without explicit permission.

Please see the LICENSE file for details.

## Contact

For questions or suggestions, open an issue or contact the maintainer directly.

---

Build your 3D worlds faster with C3D!
