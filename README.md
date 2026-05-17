# Hi, I'm Hurayrah 👋

Computer Engineering student at the University of Waterloo. I build projects to solidify what I'm learning, currently working in C++, Python, and systems programming. Always looking to pick up new tools and contribute to things that matter.

---

## Featured Projects

### [Ray Tracer in C++](https://github.com/HurayrahB/c-ray-tracing)
CPU ray tracer built from scratch in C++17, with no external dependencies. Implements Lambertian, metal, and dielectric materials with Snell's law refraction and Schlick-approximated reflectance, a thin-lens camera with depth of field, stochastic anti-aliasing, recursive path tracing, motion blur, and a texture system covering image maps and procedural noise. Scene traversal is accelerated by a bounding volume hierarchy (BVH) over axis-aligned bounding boxes, cutting per-ray intersection cost from O(n) to O(log n). Built with CMake; outputs gamma-corrected PPM. Key takeaways include designing spatial acceleration structures (BVH, ray–AABB slab traversal), managing numerical precision in ray–surface intersection, procedural texturing via hashed permutation tables, and navigating subtle C++ pitfalls around `auto`-induced variable shadowing.

### [Dockerized Todo App](https://github.com/HurayrahB/docker-todo-app)
Node.js + Express + SQLite to-do app containerized following Docker's Getting Started Workshop. Covers layer caching and Dockerfile optimization, named volumes vs. bind mounts, multi-container networking with MySQL over a user-defined bridge network, and multi-stage builds. Orchestrated with Docker Compose. Built with Node.js, Docker, Docker Compose.

---

## Currently Exploring

- Low-level graphics and rendering pipelines (extending the ray tracer with BVH acceleration and texture maps)
- Containerization and DevOps fundamentals
- Getting hands-on with machine learning fundamentals using scikit-learn

---

## Let's Connect

I'm always open to talking about engineering, co-op experiences, or opportunities.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hurayrah-butt-282660394/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:hurayrahab@gmail.com)
