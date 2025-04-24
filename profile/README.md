The main focus of Tiny Bow is Ribbon.

Ribbon is comprised of two sibling projects, inspired by a history in game development, and a deep love for high performance systems and modding.

* A programming language striking a new balance between high level programmer experience and low level
systems access, by adapting influences from the latest in academia and industry

* A real time software engine, utilizing the insights of the Ribbon language to enable new approaches to extensibility and performance, particularly in game development


Focal points of the design include:
+ High performance
    * Zero GC
    * Composable allocation strategies
    * Tracked thread affinity
    * Expressive effect system *without* allocating continuations
+ Embedding into other applications in the style of [Lua](https://lua.org) and [C#](https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/)/[MonoGame](https://monogame.net/)
    * Bindings for compiling at runtime
    * Simple glue to host applications
+ Toolkit presentation:
    * Deep extensibility in the style of
    [Lisp](https://en.wikipedia.org/wiki/Lisp_(programming_language)) and
    [Terra](https://terralang.org/)
    * Establish strong conventions for core architecture, then get out of the way
    * Module design, all modules exposed
    * Domain-specific syntax support
    * Easy compiler extension
+ Strong types with full inference:
    * Big static analysis benefits
    * Retain the flexibility and joy-of-programming from dynamic languages
    * Row polymorphism for structural data and procedures
    * Rich API encodings through the use of new kinds of phantom types and effect handlers


