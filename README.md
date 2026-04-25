Currently studying at **42 Berlin**.
Building game engines and systems-level software in C/C++. Focused on real-time rendering, ECS architecture, networking, and embedded systems.

## Game Engine & Combat Systems · C / C++ / Rust

- [**Hit 'em Good — Multiplayer Arena Fighter**](https://github.com/AntonSplavnik/transcendence)
  A 3D multiplayer arena fighting game with a **C++ ECS game engine** (entt) compiled as a static library and integrated into a Rust backend via CXX FFI. Server-authoritative 60Hz game loop on a dedicated thread. Combat system with attack chains, abilities, stamina, knockback, and two character classes (Knight & Rogue). 2–8 players over **WebTransport (HTTP/3)**. 3D rendering in Babylon.js with isometric camera, bone-attached equipment, and animation state machines.
  *My role: Product Owner & Game Developer — designed and built the game engine, combat systems, character mechanics, 3D scene, and in-game HUD.*

- [**PocketGate Engine**](https://github.com/AntonSplavnik/pocketgate-engine) *(work in progress)*
  Custom game engine for a **handheld console prototype**. Hardware assembly + embedded C/C++ software. Double-buffered rendering engine handling lines, tiles, sprites, and movement on resource-constrained hardware.

## Graphics & Rendering · C / C++

- [**Ray Tracer**](https://github.com/AntonSplavnik/miniRT)
  A raytracer written in pure C. Spheres, planes, cylinders, triangles, cones, meshes, shadows, reflections, and Phong lighting.

- [**Vulkan Ray Tracer**](https://github.com/AntonSplavnik/ray_tracer_vulkan) *(work in progress)*
  Ray tracer built with Vulkan and C++.

- [**Shader Testbed**](https://github.com/AntonSplavnik/shader_test)
  OpenGL/GLSL shader playground — custom vertex and fragment shaders with real-time mouse and time uniforms.

## Systems Programming · C / C++

- [**WebServ**](https://github.com/AntonSplavnik/WebServ)
  HTTP web server written from scratch in C++. Handles concurrent connections, request parsing, CGI, and static file serving.

- [**Mini Shell**](https://github.com/AntonSplavnik/minishell)
  Unix shell clone. Piping, redirection, signals, and process management.

- [**Philosophers**](https://github.com/AntonSplavnik/philosophers)
  POSIX-threaded dining philosophers. Mutexes, timing, and deadlock prevention.

<details>
<summary>Other Projects</summary>

- [**Cube D**](https://github.com/AntonSplavnik/How-to-make-a-videogame) — 3D runner built in Unity (C#)
- [**Kebab Maker**](https://github.com/AntonSplavnik/KebabMaker) — Mobile cooking game prototype in Unity (C#)
- `fractol` — Fractal viewer using MLX
- `push_swap` — Sorting algorithm with operation constraints
- `get_next_line` / `ft_printf` — Low-level IO utilities in C
- `libft` — Custom C standard library
</details>

## Focus Areas

- Game engine development in **C/C++**
- Real-time rendering & graphics (OpenGL, Vulkan, GLSL)
- ECS architecture & server-authoritative game loops
- Embedded systems & hardware prototyping
- Systems programming, concurrency, networking
