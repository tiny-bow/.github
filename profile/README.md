[Tiny Bow](https://tinybow.org) is the nonprofit organization responsible for Ribbon.

Ribbon is comprised of two sibling projects, inspired by a history in game development, as well as a deep love for high performance systems, modding, formal systems, and analysis.

* A [programming language](https://ribbon-lang.com) striking a new balance between high level programmer experience and low level
systems access, by adapting influences from the latest in academia and industry

* A [realtime software engine](https://ribbon-engine.com), utilizing the insights of the Ribbon language to enable new approaches to extensibility and performance, particularly in game development


Focal points of both designs include:
+ High performance
    * Zero GC
    * Composable allocation strategies
    * Tracked thread affinity
    * Expressive effect system *without* allocating continuations
+ Embedding into other applications in the style of [Lua](https://lua.org) and [C#](https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/)/[MonoGame](https://monogame.net/)
    * Bindings for compiling at runtime
    * Simple glue to host applications
+ Toolkit presentation
    * Deep extensibility in the style of
    [Lisp](https://en.wikipedia.org/wiki/Lisp_(programming_language)) and
    [Terra](https://terralang.org/)
    * Establish strong conventions for core architecture, then get out of the way
    * Modular design, all modules exposed
    * Domain-specific support
    * Easy extension
+ Strong types with full inference
    * Big static analysis benefits
    * Retain the flexibility and joy-of-programming from dynamic languages
    * Row polymorphism for structural data and procedures
    * Rich API encodings through the use of new kinds of phantom types and effect handlers


