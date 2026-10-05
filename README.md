# awesome-zig

A curated list of awesome Zig frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Package Management](#package-management)
	* [Linters and Formatters](#linters-and-formatters)
	* [Debugging and Profiling](#debugging-and-profiling)
	* [Editor and IDE Support](#editor-and-ide-support)
	* [Version Control](#version-control)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [Frontend and UI Components](#frontend-and-ui-components)
	* [Web Servers and Proxies](#web-servers-and-proxies)
* Data and Storage
	* [Databases](#databases)
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
	* [Caching and Queues](#caching-and-queues)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
	* [Machine Learning Frameworks](#machine-learning-frameworks)
* Networking and Distributed
	* [Networking](#networking)
	* [RPC and Messaging](#rpc-and-messaging)
	* [Distributed Systems](#distributed-systems)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
	* [Monitoring and Observability](#monitoring-and-observability)
* User Interface
	* [GUI Toolkits](#gui-toolkits)
	* [Terminal and Console UI](#terminal-and-console-ui)
	* [Mobile](#mobile)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Graphics and Rendering](#graphics-and-rendering)
	* [Game Development](#game-development)
	* [Audio](#audio)
	* [Image and Video](#image-and-video)
* Security
	* [Cryptography](#cryptography)
	* [Security Tools](#security-tools)
	* [Authentication and Authorization](#authentication-and-authorization)
	* [Reverse Engineering](#reverse-engineering)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
	* [Performance and Optimization](#performance-and-optimization)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Logging and Configuration](#logging-and-configuration)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* Systems and Hardware
	* [Operating Systems and Kernels](#operating-systems-and-kernels)
	* [Embedded and Firmware](#embedded-and-firmware)
* Science and Math
	* [Mathematics](#mathematics)
	* [Scientific Computing](#scientific-computing)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [pedropark99/zig-book](https://github.com/pedropark99/zig-book) - An open, technical and introductory book for the Zig programming language 📚📖
* [zigcc/zig-course](https://github.com/zigcc/zig-course) - Zig 语言圣经：简单、快速地学习 Zig, Zig Chinese tutorial, learn zig simply and quickly
* [ziglang/zig-spec](https://github.com/ziglang/zig-spec) - *(archived)*
* [cshenton/learnopengl](https://github.com/cshenton/learnopengl) - https://learnopengl.com tutorials ported to zig
* [tr1ckydev/zig_guides](https://github.com/tr1ckydev/zig_guides) - A collection of code samples and walkthroughs for performing common tasks in Zig ⚡.
* [lwjglgamedev/zvk](https://github.com/lwjglgamedev/zvk) - Vulkan tutorial using Zig language
* [dee0xeed/learning-zig-rus](https://github.com/dee0xeed/learning-zig-rus) - Karl Seguin's "Learning Zig" in Russian
* [ramonmeza/zig-c-tutorial](https://github.com/ramonmeza/zig-c-tutorial) - Learn to create Zig bindings for C libraries!
* [mikdusan/zig.internals](https://github.com/mikdusan/zig.internals) - An Unofficial Writeup on Zig Compiler Internals - THIS IS OUTDATED SINCE LATE '2022 WHEN ZIG WENT SELF-HOSTED
* [JonathanHallstrom/perf-ninja-zig](https://github.com/JonathanHallstrom/perf-ninja-zig) - Zig port of dendibakh/perf-ninja - an online course where you can learn and master the skill of low-level performance analysis and tuning.
* [PacktPublishing/Learning-Zig](https://github.com/PacktPublishing/Learning-Zig) - Learning Zig, published by Packt
* [zigcc/zig-idioms](https://github.com/zigcc/zig-idioms) - Common idioms used in Zig
* [hcsalmon1/Zig-Tutorial-Project](https://github.com/hcsalmon1/Zig-Tutorial-Project) - Tutorial files explaining how zig works and the code I used in my youtube series

### Examples and Exercises

* [zigcc/zig-cookbook](https://github.com/zigcc/zig-cookbook) - Simple Zig programs that demonstrate good practices to accomplish common programming tasks.
* [TheAlgorithms/Zig](https://github.com/TheAlgorithms/Zig) - Collection of Algorithms implemented in Zig.
* [CX330Blake/Black-Hat-Zig](https://github.com/CX330Blake/Black-Hat-Zig) - This project provides some code examples of Zig for malwares, hacking, and red teaming. ⚡
* [SuperAuguste/zig-patterns](https://github.com/SuperAuguste/zig-patterns) - Common Zig patterns for you and your friends :)
* [spanzeri/vkguide-zig](https://github.com/spanzeri/vkguide-zig) - An implementation of vkguide.dev in the zig programming language
* [andrewrk/zig-vulkan-triangle](https://github.com/andrewrk/zig-vulkan-triangle) - simple triangle displayed using vulkan, xcb, and zig
* [andrewrk/sdl-zig-demo](https://github.com/andrewrk/sdl-zig-demo) - SDL2 hello world in zig
* [craftlinks/zig_learn_opengl](https://github.com/craftlinks/zig_learn_opengl) - Follow the Learn-OpenGL book using Zig
* [staltz/zig-nodejs-example](https://github.com/staltz/zig-nodejs-example) - Node.js Native Module written in Zig
* [SpexGuy/Zig-AoC-Template](https://github.com/SpexGuy/Zig-AoC-Template) - A template for Advent of Code participants using Zig
* [daneelsan/minimal-zig-wasm-canvas](https://github.com/daneelsan/minimal-zig-wasm-canvas) - A minimal example showing how HTML5's canvas, wasm memory and zig can interact.
* [ste5e99/zigtoys](https://github.com/ste5e99/zigtoys) - All about Zig + WASM and seeing what we can do
* [Nelarius/weekend-raytracer-zig](https://github.com/Nelarius/weekend-raytracer-zig) - A Zig implementation of the "Ray Tracing in One Weekend" book
* [nrdmn/uefi-examples](https://github.com/nrdmn/uefi-examples) - UEFI examples in Zig
* [tralamazza/embedded_zig](https://github.com/tralamazza/embedded_zig) - minimal Zig embedded ARM example (STM32F103 blue pill)
* [coderonion/hello-algo-zig](https://github.com/coderonion/hello-algo-zig) - Zig codes for the famous public project 《Hello, Algorithm》|《 Hello，算法 》 about data structures and algorithms.
* [SimonLSchlee/zigraylib](https://github.com/SimonLSchlee/zigraylib) - a fairly minimal raylib zig example codebase using the zig package manager *(archived)*
* [floooh/sokol-zig-imgui-sample](https://github.com/floooh/sokol-zig-imgui-sample) - Sample to use sokol-zig bindings with Dear ImGui
* [exercism/zig](https://github.com/exercism/zig) - Exercism exercises in Zig.
* [Swoogan/ziggtk](https://github.com/Swoogan/ziggtk) - Sample GTK+ applications in the zig programming language
* [rbino/zig-stm32-blink](https://github.com/rbino/zig-stm32-blink) - Use Zig to blink some LEDs
* [dundalek/notcurses-zig-example](https://github.com/dundalek/notcurses-zig-example) - Demo showing how to use Notcurses library for building terminal UIs with Zig
* [Vulfox/vulkan-tutorial-zig](https://github.com/Vulfox/vulkan-tutorial-zig) - A Zig implementation of https://github.com/Overv/VulkanTutorial
* [ComputerBread/znippets](https://github.com/ComputerBread/znippets) - A collection of Zig code snippets tested across multiple Zig versions
* [skyfex/zig-nrf-demo](https://github.com/skyfex/zig-nrf-demo) - Demonstrate Zig code on the nRF51/nRF52 microcontrollers
* [andrewrk/zig-async-demo](https://github.com/andrewrk/zig-async-demo) - Comparing concurrent code example programs between other languages and Zig
* [meheleventyone/zig-wasm-test](https://github.com/meheleventyone/zig-wasm-test) - A minimal Web Assembly example using Zig's build system.
* [Durobot/raylib-zig-examples](https://github.com/Durobot/raylib-zig-examples) - Raylib examples ported to Zig
* [zserge/glob-grep](https://github.com/zserge/glob-grep) - A little experiment: compare the languages aimed to replace C
* [castholm/zig-examples](https://github.com/castholm/zig-examples) - Collection of small Zig example projects
* [ryupold/examples-raylib.zig](https://github.com/ryupold/examples-raylib.zig) - Example usage of raylib.zig bindings
* [ziglings-org/exercises](https://github.com/ziglings-org/exercises) - This WAS the mirror of Ziglings
* [spiraldb/ziggy-pydust-template](https://github.com/spiraldb/ziggy-pydust-template) - A template for building Python extensions in Zig using Pydust toolkit.
* [SpexGuy/Zig-Oculus-Quest](https://github.com/SpexGuy/Zig-Oculus-Quest) - An example application for the Oculus Quest, written in Zig
* [david-vanderson/dvui-demo](https://github.com/david-vanderson/dvui-demo) - examples for using dvui
* [DutchGhost/zigiffy](https://github.com/DutchGhost/zigiffy) - Rust FFI with Zig
* [lithdew/hello](https://github.com/lithdew/hello) - Multi-threaded cross-platform HTTP/1.1 web server example in Zig.
* [tiehuis/zig-rosetta](https://github.com/tiehuis/zig-rosetta) - Rosettacode examples in zig *(archived)*
* [Tomcat-42/aoc.zig-template](https://github.com/Tomcat-42/aoc.zig-template) - Advent of Code Zig Template

## Language and Tooling

### Compilers and Interpreters

* [ziglang/zig](https://github.com/ziglang/zig) - Moved to Codeberg
* [roc-lang/roc](https://github.com/roc-lang/roc) - A fast, friendly, functional language.
* [Vexu/arocc](https://github.com/Vexu/arocc) - A modern fully featured C compiler.
* [buzz-language/buzz](https://github.com/buzz-language/buzz) - 👨‍🚀 buzz, A small/lightweight statically typed scripting language
* [fubark/cyber](https://github.com/fubark/cyber) - Fast and concurrent scripting.
* [yuku-toolchain/yuku](https://github.com/yuku-toolchain/yuku) - High-performance JavaScript/TypeScript compiler toolchain in Zig.
* [ghuntley/cursed](https://github.com/ghuntley/cursed) - the 💀 cursed programming language: programming, but make it gen z
* [Vexu/toy-lang](https://github.com/Vexu/toy-lang) - Toy language for experimentation and fun.
* [zackradisic/tyvm](https://github.com/zackradisic/tyvm) - An experimental bytecode interpreter / type-checker for type-level Typescript
* [natecraddock/ziglua](https://github.com/natecraddock/ziglua) - Zig bindings for the Lua C API
* [if-not-nil/revo](https://github.com/if-not-nil/revo) - a dynamic language for the joy of programming
* [malcolmstill/zware](https://github.com/malcolmstill/zware) - Zig WebAssembly Runtime Engine
* [kubkon/bold](https://github.com/kubkon/bold) - bold: the bold linker *(archived)*
* [ziglang/translate-c](https://github.com/ziglang/translate-c) - A Zig package for translating C code into Zig code. *(archived)*
* [jamii/imp](https://github.com/jamii/imp) - Various experiments in relational programming *(archived)*
* [Validark/Accelerated-Zig-Parser](https://github.com/Validark/Accelerated-Zig-Parser) - A high-throughput parser for the Zig programming language.
* [jazzzooo/buz](https://github.com/jazzzooo/buz) - A fork of Bun based on modern Zig
* [lightpanda-io/zig-js-runtime](https://github.com/lightpanda-io/zig-js-runtime) - Add a JS runtime in your Zig project *(archived)*
* [ikskuh/LoLa](https://github.com/ikskuh/LoLa) - LoLa is a small programming language meant to be embedded into games.
* [sin-ack/zigself](https://github.com/sin-ack/zigself) - An implementation of the Self programming language in Zig
* [cryptocode/bio](https://github.com/cryptocode/bio) - A Lisp dialect written in Zig
* [squeek502/zua](https://github.com/squeek502/zua) - An implementation of Lua 5.1 in Zig, for learning purposes
* [clojurewasm/ClojureWasm](https://github.com/clojurewasm/ClojureWasm) - A JVM-free Clojure runtime in Zig — call WebAssembly from Clojure to use libraries written in any language.
* [ziglang/libc-abi-tools](https://github.com/ziglang/libc-abi-tools) - A repository that collects libc ABI files for multiple versions and a tool to combine them into one dataset. *(archived)*
* [zwasm/zwasm](https://github.com/zwasm/zwasm) - A fast, spec-compliant WebAssembly runtime written in Zig
* [fubark/zig-v8](https://github.com/fubark/zig-v8) - Simple V8 builds with C and Zig bindings.
* [Zag-Research/Zag-Smalltalk](https://github.com/Zag-Research/Zag-Smalltalk) - Smalltalk VM Written in Zig with methods stored as type-annotated ASTs
* [squeek502/resinator](https://github.com/squeek502/resinator) - Cross-platform Windows resource-definition script (.rc) to resource file (.res) compiler
* [psyclyx/fix](https://github.com/psyclyx/fix) - Fast nIX language evaluator
* [rdunnington/bytebox](https://github.com/rdunnington/bytebox) - Standalone WebAssembly VM.
* [srijan-paul/jam](https://github.com/srijan-paul/jam) - Fastest JS parser and semantic analyzer out there.
* [tree-sitter/zig-tree-sitter](https://github.com/tree-sitter/zig-tree-sitter) - Zig bindings to the Tree-sitter parsing library
* [fengb/wazm](https://github.com/fengb/wazm) - Web Assembly Zig Machine *(archived)*
* [mitchellh/zig-quickjs-ng](https://github.com/mitchellh/zig-quickjs-ng) - Zig build and bindings for quickjs-ng
* [Scythe-Technology/zune](https://github.com/Scythe-Technology/zune) - A Luau runtime
* [solenopsys/cruller](https://github.com/solenopsys/cruller) - fork of Bun
* [zig-java/jaz](https://github.com/zig-java/jaz) - A JVM implementation in Zig!
* [chrischtel/Ziglet](https://github.com/chrischtel/Ziglet) - A Minimalist, High-Performance Virtual Machine in Zig
* [andrewrk/zasm](https://github.com/andrewrk/zasm) - multi-target assembler and disassembler
* [mitchellh/zig-mquickjs](https://github.com/mitchellh/zig-mquickjs) - Zig build and bindings for Micro QuickJS
* [sackosoft/zig-luajit](https://github.com/sackosoft/zig-luajit) - Run Lua code in Zig apps! A package providing Zig language bindings to LuaJIT.
* [zigwasm/wasmtime-zig](https://github.com/zigwasm/wasmtime-zig) - Zig embedding of Wasmtime
* [Ray-D-Song/wasmz](https://github.com/Ray-D-Song/wasmz) - Fast WebAssembly interpreter
* [ikskuh/parser-toolkit](https://github.com/ikskuh/parser-toolkit) - A toolkit that makes it easier to write recursive-descent parsers in Zig.
* [atomfinger/brunost](https://github.com/atomfinger/brunost) - Brunost - Programmeringsspråket med smak av Noreg
* [AvitalTamir/sever](https://github.com/AvitalTamir/sever) - A Programming Language by AI, for AI
* [FarhanAliRaza/taipan](https://github.com/FarhanAliRaza/taipan) - Run Python anywhere. A single self-contained binary (Zig + embedded CPython) that runs PEP 723 scripts on machines with no Python installed.
* [kassane/llvm-zig](https://github.com/kassane/llvm-zig) - LLVM bindings written in Zig
* [srijan-paul/tinyjit](https://github.com/srijan-paul/tinyjit) - Educational JIT compiler for ARM64 in Zig.
* [Rexicon226/osmium](https://github.com/Rexicon226/osmium) - A Python Interpreter written in Zig
* [jwmerrill/zig-lox](https://github.com/jwmerrill/zig-lox) - Zig implementation of Crafting Interpreters bytecode lox interpreter
* [zigwasm/wasmer-zig](https://github.com/zigwasm/wasmer-zig) - Zig bindings for the Wasmer WebAssembly runtime
* [kiedtl/finwe](https://github.com/kiedtl/finwe) - A statically-typed, concatenative language for the Uxn VM with compiler-enforced stack safety.
* [chaploud/ClojureWasmBeta](https://github.com/chaploud/ClojureWasmBeta) - *(archived)*
* [alichay/zig-wasm3](https://github.com/alichay/zig-wasm3) - Zig bindings and build system for https://github.com/wasm3/wasm3
* [mattn/zig-lisp](https://github.com/mattn/zig-lisp)
* [Luukdegram/luf](https://github.com/Luukdegram/luf) - Statically typed, embeddable, scripting language written in Zig.
* [mxpv/luaz](https://github.com/mxpv/luaz) - Zero-cost Luau wrapper for Zig
* [igor84/wcc](https://github.com/igor84/wcc) - A compiler for subset of C as instructed by the "Writing a C compiler" book by Nora Sandler
* [dantecatalfamo/mruby-zig](https://github.com/dantecatalfamo/mruby-zig) - mruby bindings for zig
* [Lulzx/hvm](https://github.com/Lulzx/hvm) - A Zig implementation of HVM - the Higher-Order Virtual Machine based on Interaction Calculus.
* [zig-java/jui](https://github.com/zig-java/jui) - Ziggy bindings for the JNI
* [kristoff-it/scripty](https://github.com/kristoff-it/scripty) - The perfect scripting sidekick!
* [bfredl/forklift](https://github.com/bfredl/forklift) - x86-64 JIT backend for Zig
* [extism/zig-pdk](https://github.com/extism/zig-pdk) - Extism Plug-in Development Kit (PDK) for Zig
* [Rexicon226/zob](https://github.com/Rexicon226/zob) - Zig Optimizing Backend
* [chmod222/zuxn](https://github.com/chmod222/zuxn) - A Zig implementation of the Uxn and Varvara ecosystem (MIRROR)
* [extism/zig-sdk](https://github.com/extism/zig-sdk) - Extism Zig Host SDK - easily run WebAssembly modules / plugins from Zig applications
* [the-flint-lang/flint](https://github.com/the-flint-lang/flint) - A pipeline-oriented system language for robust CLI tools. Transpiles to C99. Built in Zig. *(archived)*
* [anoushk1234/zig-ebpf](https://github.com/anoushk1234/zig-ebpf) - Zig virtual machine for eBPF programs.
* [momumi/x86-zig](https://github.com/momumi/x86-zig) - library for assembling x86 in zig (WIP)

### Build Systems

* [theseyan/bkg](https://github.com/theseyan/bkg) - Package Bun apps into a single executable
* [Cloudef/zig2nix](https://github.com/Cloudef/zig2nix) - Flake for packaging, building and running Zig projects.
* [the-argus/zig-compile-commands](https://github.com/the-argus/zig-compile-commands) - A simple zig module to generate compile_commands.json from a slice of build targets.
* [mitchellh/zig-libxml2](https://github.com/mitchellh/zig-libxml2) - libxml2 built using Zig build system
* [chase-lambert/vigil](https://github.com/chase-lambert/vigil) - A clean, fast build watcher for Zig
* [allyourcodebase/zlib](https://github.com/allyourcodebase/zlib) - zlib ported to the zig build system
* [akarpovskii/build.crab](https://github.com/akarpovskii/build.crab) - Build and use Rust libraries from Zig
* [pwbh/SDL](https://github.com/pwbh/SDL) - SDL on Zig build system and in-sync with latest SDL versions
* [ziglang/fetch-them-macos-headers](https://github.com/ziglang/fetch-them-macos-headers) - A utility for fetching minimal macOS libc headers *(archived)*
* [andrewrk/autodoc](https://github.com/andrewrk/autodoc) - Zig Documentation Generator *(archived)*
* [hermeticbuild/actiond](https://github.com/hermeticbuild/actiond) - A fully hermetic local "remote executor"
* [Luukdegram/zwld](https://github.com/Luukdegram/zwld) - Experimental wasm linker *(archived)*
* [moosichu/zar](https://github.com/moosichu/zar) - An attempt to write an archiver using zig
* [zig-gamedev/zemscripten](https://github.com/zig-gamedev/zemscripten) - Build package and shims for Emscripten emsdk

### Package Management

* [Seafoam-Labs/Shelly-ALPM](https://github.com/Seafoam-Labs/Shelly-ALPM) - Pacman alternative for ArchLinux, designed with you in mind.
* [justrach/nanobrew](https://github.com/justrach/nanobrew) - The fastest macOS package manager. Written in Zig. 3ms warm installs.
* [marler8997/zigup](https://github.com/marler8997/zigup) - Download and manage zig compilers.
* [nektro/zigmod](https://github.com/nektro/zigmod) - 📦 A package manager for the Zig programming language.
* [marler8997/anyzig](https://github.com/marler8997/anyzig) - One zig to rule them all.
* [shilangyu/scoop-search](https://github.com/shilangyu/scoop-search) - Fast `scoop search` drop-in replacement 🚀
* [marler8997/msvcup](https://github.com/marler8997/msvcup) - Hermetic install of MSVC/SDK from the CLI
* [indaco/malt](https://github.com/indaco/malt) - Homebrew's whole ecosystem, none of its weight - a single Zig binary with native post-install and a themeable TUI & CLI.
* [nix-community/zon2nix](https://github.com/nix-community/zon2nix) - Convert the dependencies in `build.zig.zon` to a Nix expression [maintainer=@figsoda]
* [ziglibs/repository](https://github.com/ziglibs/repository) - A community-maintained repository of zig packages
* [ScoopInstaller/Shim](https://github.com/ScoopInstaller/Shim) - A Scoop helper program for shimming executables
* [hendriknielaender/zvm](https://github.com/hendriknielaender/zvm) - ⚡ POSIX-compliant fast and simple zig version manager (zvm)
* [Hejsil/dipm](https://github.com/Hejsil/dipm) - An alternative to `curl | sh`
* [marler8997/zig-unofficial-releases](https://github.com/marler8997/zig-unofficial-releases) - A list of unofficial zig releases
* [nektro/aquila](https://github.com/nektro/aquila) - 📫 A package index for Zig projects.
* [marler8997/zig-build-repos](https://github.com/marler8997/zig-build-repos) - [DEPRECATED] use build.zig.zon instead. Enables build.zig files to depend on git repositories. *(archived)*
* [mertishere/zeP](https://github.com/mertishere/zeP) - A new package- and version manager for zig.
* [moonstone-sh/moonstone](https://github.com/moonstone-sh/moonstone) - ʀᴇʟɪᴀʙʟᴇ ʟᴜᴀ ᴇɴᴠɪʀᴏɴᴍᴇɴᴛꜱ, ʀᴇᴀᴅʏ ᴀᴛ ᴀ ꜱɴᴀᴘ.
* [lispking/zvm](https://github.com/lispking/zvm) - A fast, dependency-free version manager for Zig written in Zig.
* [aklinker1/bunv](https://github.com/aklinker1/bunv) - Corepack for Bun. PoC for implementing a version manager inside bun itself.

### Linters and Formatters

* [kristoff-it/superhtml](https://github.com/kristoff-it/superhtml) - HTML Validator, Formatter, LSP, and Templating Language Library
* [DonIsaac/zlint](https://github.com/DonIsaac/zlint) - A linter for the Zig programming language
* [ityonemo/clr](https://github.com/ityonemo/clr) - Checker for Lifetimes and other Refinement types
* [fiberplane/drift](https://github.com/fiberplane/drift) - Bind specs to code and check for drift.
* [DutchGhost/zorrow](https://github.com/DutchGhost/zorrow) - Borrowchecker in Zig
* [nektro/ziglint](https://github.com/nektro/ziglint) - A linting suite for Zig
* [KurtWagner/zlinter](https://github.com/KurtWagner/zlinter) - An extendable and customisable Zig linter that is integrated from source into your build.zig.
* [rockorager/ziglint](https://github.com/rockorager/ziglint) - opinionated linting to keep your agent in check
* [tusharsadhwani/zigimports](https://github.com/tusharsadhwani/zigimports) - Automatically remove unused imports and globals from Zig files.

### Debugging and Profiling

* [jcalabro/uscope](https://github.com/jcalabro/uscope) - μscope 🔬
* [ANDRVV/zprof](https://github.com/ANDRVV/zprof) - A cross-allocator memory profiler for Zig. Tracks logical allocations, detects memory leaks, and logs memory changes with optional thread-safe mode.
* [nektro/zig-tracy](https://github.com/nektro/zig-tracy) - Zig bindings for the Tracy profiler.
* [ciathefed/fehler](https://github.com/ciathefed/fehler) - A comprehensive error reporting system for Zig
* [kubkon/zig-snapshots](https://github.com/kubkon/zig-snapshots) - Preview Zig's incremental linker state in interactive HTML
* [speed2exe/tree-fmt](https://github.com/speed2exe/tree-fmt) - Tree-like pretty formatter for Zig
* [cipharius/zig-tracy](https://github.com/cipharius/zig-tracy) - Easy to use bindings for the tracy client C API.
* [Games-by-Mason/tracy_zig](https://github.com/Games-by-Mason/tracy_zig) - Tracy bindings for Zig.

### Editor and IDE Support

* [zigtools/zls](https://github.com/zigtools/zls) - A language server for Zig supporting developers with features like autocomplete and goto definition
* [nolanderc/glsl_analyzer](https://github.com/nolanderc/glsl_analyzer) - Language server for GLSL (autocomplete, goto-definition, formatter, and more)
* [llogick/zigscient](https://github.com/llogick/zigscient) - A Zig Language Server
* [zigtools/lsp-kit](https://github.com/zigtools/lsp-kit) - The necessary building blocks to develop LSP implementations in Zig.
* [rwc9u/emacs-libgterm](https://github.com/rwc9u/emacs-libgterm) - Terminal emulator for Emacs using libghostty-vt (Ghostty's terminal engine)
* [ziglang/sublime-zig-language](https://github.com/ziglang/sublime-zig-language) - Zig language support for Sublime Text
* [ziglibs/zig-lsp](https://github.com/ziglibs/zig-lsp) - Microsoft's Language Server Protocol implemented in Zig for use in zls and beyond! <3 *(archived)*
* [nvim-neorg/neorg-lsp](https://github.com/nvim-neorg/neorg-lsp) - An LSP for the Neorg file format.

### Version Control

* [xit-vcs/xit](https://github.com/xit-vcs/xit) - a git alternative written in zig
* [xit-vcs/haxy](https://github.com/xit-vcs/haxy) - a git forge from the future-past
* [mattzcarey/zagi](https://github.com/mattzcarey/zagi) - better git cli for agents
* [simoarpe/ziggity](https://github.com/simoarpe/ziggity) - ⚡️ Ziggity an ultra fast, keyboard driven terminal UI for Git, written in Zig.
* [chrislloyd/git-remote-sqlite](https://github.com/chrislloyd/git-remote-sqlite) - Single-file Git repos that can replicate with Litestream
* [will/git-vain](https://github.com/will/git-vain) - vanity git
* [dantecatalfamo/zig-git](https://github.com/dantecatalfamo/zig-git) - Implementing git structures and functions in zig
* [leecannon/zig-libgit2](https://github.com/leecannon/zig-libgit2) - Zig bindings to libgit2 *(archived)*

## Web

### Web Frameworks

* [kristoff-it/zine](https://github.com/kristoff-it/zine) - Fast, Scalable, Flexible Static Site Generator (SSG)
* [jetzig-framework/jetzig](https://github.com/jetzig-framework/jetzig) - Jetzig is a web framework written in Zig
* [justrach/turboAPI](https://github.com/justrach/turboAPI) - FastAPI-compatible Python framework with Zig HTTP core; 7x faster, free-threading native
* [cztomsik/tokamak](https://github.com/cztomsik/tokamak) - Web framework for Zig that leverages dependency injection for clean, modular application development.
* [ziex-dev/ziex](https://github.com/ziex-dev/ziex) - Full-stack web framework for Zig. HTML syntax within Zig code, just like JSX but for Zig!
* [justrach/merjs](https://github.com/justrach/merjs) - A Zig-native web framework. File-based routing, SSR, type-safe APIs, WASM client interactivity. No Node. No npm. Just zig build serve.
* [zon-dev/zinc](https://github.com/zon-dev/zinc) - Zinc is a web framework written in pure Zig with a focus on high performance, usability, security, and extensibility.
* [floscodes/zerve](https://github.com/floscodes/zerve) - zerve is a minimalistic approach to a lightweight, zero-dependency web framework for Zig – designed to be simple, fast, and easy to use.
* [Cloudef/zig-router](https://github.com/Cloudef/zig-router) - Straightforward HTTP-like request routing.

### HTTP and Networking Clients

* [jiacai2050/zig-curl](https://github.com/jiacai2050/zig-curl) - Libcurl bindings for Zig
* [ducdetronquito/requestz](https://github.com/ducdetronquito/requestz) - HTTP client for Zig 🦎 *(archived)*
* [ducdetronquito/h11](https://github.com/ducdetronquito/h11) - I/O agnostic HTTP/1.1 implementation for Zig 🦎 *(archived)*
* [ducdetronquito/http](https://github.com/ducdetronquito/http) - HTTP core types for Zig 🦴 *(archived)*
* [muhammad-fiaz/httpx.zig](https://github.com/muhammad-fiaz/httpx.zig) - httpx.zig is a production-ready, high-performance HTTP client and server library for Zig, designed for building modern, robust, and scalable networked applications.
* [truemedian/hzzp](https://github.com/truemedian/hzzp) - *(archived)*
* [haze/zelda](https://github.com/haze/zelda) - A simple HTTP client library for Zig *(archived)*
* [marler8997/ziget](https://github.com/marler8997/ziget) - Zig library/tool to request network assets
* [fengb/zCord](https://github.com/fengb/zCord) - Zig ⚡ Discord API with zero allocations in the critical path *(archived)*
* [truemedian/zfetch](https://github.com/truemedian/zfetch) - *(archived)*
* [Kludex/zttp](https://github.com/Kludex/zttp) - Sans-IO HTTP parser for Python with a Zig core! :zap:
* [nikneym/hparse](https://github.com/nikneym/hparse) - Fastest HTTP parser in the west. Utilizes SIMD vectorization, supports streaming and never allocates. Powered by Zig ⚡
* [mattn/zig-curl](https://github.com/mattn/zig-curl) - cURL binding for Zig
* [definitepotato/espocrmz](https://github.com/definitepotato/espocrmz) - An API client for EspoCRM in Zig.

### Frontend and UI Components

* [cztomsik/graffiti](https://github.com/cztomsik/graffiti) - HTML/CSS engine for node.js and deno.
* [mitchellh/zig-js](https://github.com/mitchellh/zig-js) - Access the JS host environment from Zig compiled to WebAssembly.
* [shritesh/zig-wasm-dom](https://github.com/shritesh/zig-wasm-dom) - Zig + WebAssembly + JS + DOM
* [chadwain/rem](https://github.com/chadwain/rem) - An HTML parsing library, written in Zig.
* [scottredig/zig-javascript-bridge](https://github.com/scottredig/zig-javascript-bridge) - Easily call Javascript from Zig wasm
* [chadwain/zss](https://github.com/chadwain/zss) - zss is a CSS parser, layout engine, and renderer, written in Zig.

### Web Servers and Proxies

* [karlseguin/http.zig](https://github.com/karlseguin/http.zig) - An HTTP/1.1 server for zig
* [tardy-org/zzz](https://github.com/tardy-org/zzz) - A framework for writing performant and reliable networked services.
* [frmdstryr/zhp](https://github.com/frmdstryr/zhp) - A Http server written in Zig *(archived)*
* [Vexu/routez](https://github.com/Vexu/routez) - Http server for Zig *(archived)*
* [Luukdegram/apple_pie](https://github.com/Luukdegram/apple_pie) - Basic HTTP server implementation in Zig
* [Aryvyo/Zagros](https://github.com/Aryvyo/Zagros) - A simple, fast server built in Zig!
* [andrewrk/StaticHttpFileServer](https://github.com/andrewrk/StaticHttpFileServer) - Zig module for serving a directory of files from memory via HTTP
* [amirrezaask/khadem](https://github.com/amirrezaask/khadem) - Async webserver implemented in both Zig and Rust
* [hendriknielaender/http2.zig](https://github.com/hendriknielaender/http2.zig) - 🌐 HTTP/2 server for zig
* [ikskuh/zig-serve](https://github.com/ikskuh/zig-serve) - Server implementations for several protocols in Zig. Includes http(s), gemini and gopher
* [vrischmann/zig-io_uring-http-server](https://github.com/vrischmann/zig-io_uring-http-server)
* [AndrewGossage/Zoi](https://github.com/AndrewGossage/Zoi) - Ultra simple zig server

## Data and Storage

### Databases

* [tigerbeetle/tigerbeetle](https://github.com/tigerbeetle/tigerbeetle) - The financial transactions database designed for mission critical safety and performance.
* [jeffhajewski/latticedb](https://github.com/jeffhajewski/latticedb) - Embedded single-file knowledge graph database with vector search and full-text search for AI/RAG apps
* [xataio/pgzx](https://github.com/xataio/pgzx) - Create PostgreSQL extensions using Zig.
* [Lulzx/zs3](https://github.com/Lulzx/zs3) - S3-compatible storage in Zig. Zero dependencies.
* [rajivharlalka/filedb](https://github.com/rajivharlalka/filedb) - Disk Based Key-Value Store Inspired by Bitcask
* [eatonphil/zigrocks](https://github.com/eatonphil/zigrocks) - Writing a SQL database, take two: Zig and RocksDB
* [ekzhang/redis-rope](https://github.com/ekzhang/redis-rope) - 🪢 A fast native data type for manipulating large strings in Redis
* [xit-vcs/xitdb](https://github.com/xit-vcs/xitdb) - an immutable database for zig
* [canvasxyz/okra](https://github.com/canvasxyz/okra) - A pseudo-random deterministic merkle tree built on LMDB
* [tursodatabase/pg_turso](https://github.com/tursodatabase/pg_turso) - Postgres output plugin for replicating data to Turso. *(archived)*
* [jeremytregunna/foldb](https://github.com/jeremytregunna/foldb) - The database that is a log, and all operations are `fold(log)`.
* [nickmonad/kv](https://github.com/nickmonad/kv) - small and fast key/value store
* [ochi-team/ochi](https://github.com/ochi-team/ochi) - Ochi is a fast, cost-effective, Loki compatible database for logs.
* [mailmug/zentropy](https://github.com/mailmug/zentropy) - A high-performance, lightweight key-value store server written in Zig
* [ekzhang/graphon](https://github.com/ekzhang/graphon) - 🌌 A very small graph database in Zig

### Database Clients and ORMs

* [karlseguin/pg.zig](https://github.com/karlseguin/pg.zig) - Native PostgreSQL driver / client for Zig
* [kristoff-it/zig-okredis](https://github.com/kristoff-it/zig-okredis) - Zero-allocation Client for all the various Redis forks
* [cztomsik/fridge](https://github.com/cztomsik/fridge) - A small, batteries-included database library for Zig.
* [lithdew/lmdb-zig](https://github.com/lithdew/lmdb-zig) - Lightweight, fully-featured, idiomatic cross-platform Zig bindings to Lightning Memory-Mapped Database (LMDB).
* [speed2exe/myzql](https://github.com/speed2exe/myzql) - MySQL and MariaDB driver in native Zig
* [jetzig-framework/jetquery](https://github.com/jetzig-framework/jetquery) - Database query library for the Jetzig web framework
* [nDimensional/zig-sqlite](https://github.com/nDimensional/zig-sqlite) - Simple, low-level, explicitly-typed SQLite bindings for Zig.
* [Tony-ArtZ/zorm](https://github.com/Tony-ArtZ/zorm) - A Zig ORM with custom schema support
* [nDimensional/zig-lmdb](https://github.com/nDimensional/zig-lmdb) - Zig bindings for LMDB
* [star-tek-mb/pgz](https://github.com/star-tek-mb/pgz) - Postgres driver written in pure Zig

### Serialization and Formats

* [kristoff-it/ziggy](https://github.com/kristoff-it/ziggy) - A data serialization language for expressing clear API messages, config files, etc.
* [Arwalk/zig-protobuf](https://github.com/Arwalk/zig-protobuf) - a protobuf 3 implementation for zig.
* [kubkon/zig-yaml](https://github.com/kubkon/zig-yaml) - YAML parser for Zig *(archived)*
* [norma-core/gremlin.zig](https://github.com/norma-core/gremlin.zig) - A zero-dependency Google Protocol Buffers implementation in pure Zig. Single allocation encode and lazy decode
* [getty-zig/getty](https://github.com/getty-zig/getty) - A (de)serialization framework for Zig *(archived)*
* [EzequielRamis/zimdjson](https://github.com/EzequielRamis/zimdjson) - Parsing gigabytes of JSON per second. Zig port of simdjson with fundamental features.
* [ziglibs/s2s](https://github.com/ziglibs/s2s) - A zig binary serialization format.
* [mitchellh/libflightplan](https://github.com/mitchellh/libflightplan) - A library for reading and writing flight plans in various formats. Available as both a C and Zig library.
* [archaistvolts/simdjson-z](https://github.com/archaistvolts/simdjson-z) - simdjson ported to zig
* [sam701/zig-toml](https://github.com/sam701/zig-toml) - Zig TOML (v1.0.0) parser
* [adamserafini/zaml](https://github.com/adamserafini/zaml) - 🚀 Fast YAML 1.2 parsing library for Python 3
* [aeronavery/zig-toml](https://github.com/aeronavery/zig-toml) - A TOML parser written in Zig
* [nektro/zig-xml](https://github.com/nektro/zig-xml) - A pure-Zig fully spec-compliant XML parser.
* [gruebite/zzz](https://github.com/gruebite/zzz) - Simple and boring human readable data format for Zig.
* [OrlovEvgeny/serde.zig](https://github.com/OrlovEvgeny/serde.zig) - Universal serialization for Zig: JSON, Yaml, XML, MessagePack, TOML, CSV and more from a single API. msgpack.org[Zig]
* [getty-zig/json](https://github.com/getty-zig/json) - A (de)serialization library for JSON *(archived)*
* [theseyan/bufzilla](https://github.com/theseyan/bufzilla) - Fast, compact, zero-copy serialization format in Zig.
* [ianprime0509/zig-xml](https://github.com/ianprime0509/zig-xml) - XML parser for Zig
* [clickingbuttons/arrow-zig](https://github.com/clickingbuttons/arrow-zig) - Apache Arrow implementation
* [zigcc/zig-msgpack](https://github.com/zigcc/zig-msgpack) - zig messagpack implementation / msgpack.org[zig]
* [pwbh/ymlz](https://github.com/pwbh/ymlz) - Small and convenient YAML parser for Zig
* [r4gus/zbor](https://github.com/r4gus/zbor) - This is a mirror. Work is continued on codeberg: https://codeberg.org/r4gus/zbor
* [archaistvolts/flatbufferz](https://github.com/archaistvolts/flatbufferz) - a flatbuffers codegen library in zig
* [archaistvolts/protobuf-zig](https://github.com/archaistvolts/protobuf-zig) - A protocol buffers implementation in zig *(archived)*
* [knadh/csv2json](https://github.com/knadh/csv2json) - csv2json is a fast utility that converts CSV files into JSON line files. An experiment in Zig lang.
* [kubkon/protozig](https://github.com/kubkon/protozig) - The protozig(uana), or protocol buffers implementation in Zig
* [mattyhall/tomlz](https://github.com/mattyhall/tomlz) - A well-tested TOML parsing library for Zig
* [xyaman/zjson](https://github.com/xyaman/zjson) - Minimal json library with zero allocations
* [leostera/zerde](https://github.com/leostera/zerde) - comptime-fused serialization library for zig
* [ziglibs/tres](https://github.com/ziglibs/tres) - ValueTree-based JSON parser *(archived)*
* [zigtools/protobruh](https://github.com/zigtools/protobruh) - Protobuf for Zig
* [berdon/zig-json](https://github.com/berdon/zig-json) - Simple zig JSON parsing library with a focus on friendly API.
* [ziglibs/ini](https://github.com/ziglibs/ini) - A teeny tiny ini parser
* [mattn/zig-json](https://github.com/mattn/zig-json)
* [blockblaz/ssz.zig](https://github.com/blockblaz/ssz.zig) - A ziglang implementation of the SSZ serialization protocol
* [matthewtolman/zig_csv](https://github.com/matthewtolman/zig_csv) - CSV tools (writing, parsing) for Zig
* [mlugg/zigpb](https://github.com/mlugg/zigpb) - Simple Protobuf encoder and decoder in Zig

### Caching and Queues

* [barddoo/zedis](https://github.com/barddoo/zedis) - Redis in Zig
* [kristoff-it/redis-cuckoofilter](https://github.com/kristoff-it/redis-cuckoofilter) - Hashing-function agnostic Cuckoo filters for Redis
* [jeremytregunna/wild](https://github.com/jeremytregunna/wild) - A highly performant cache for very small data
* [karlseguin/cache.zig](https://github.com/karlseguin/cache.zig) - A thread-safe, expiration-aware, LRU cache for Zig
* [taskforcesh/bullmq-redis](https://github.com/taskforcesh/bullmq-redis) - BullMQ - Redis Module for handling queues of jobs and messages.
* [sectasy0/zcached](https://github.com/sectasy0/zcached) - Lightweight and efficient in-memory caching system akin to databases like Redis.

## Machine Learning and AI

### LLM and Inference

* [nullclaw/nullclaw](https://github.com/nullclaw/nullclaw) - Fastest, smallest, and fully autonomous AI assistant infrastructure written in Zig
* [zml/zml](https://github.com/zml/zml) - Any model. Any hardware. Zero compromise. Built with @ziglang / @openxla / MLIR / @bazelbuild
* [vercel-labs/fx](https://github.com/vercel-labs/fx) - Unix like coding agent
* [nullclaw/nullhub](https://github.com/nullclaw/nullhub) - Management console for the Null ecosystem — install, configure, and monitor AI agents, orchestration workflows, task pipelines, and system health
* [ddalcu/mlx-serve](https://github.com/ddalcu/mlx-serve) - Native LLM inference server for Apple Silicon. OpenAI + Anthropic API compatible. No Python. Zig backend, Swift frontend macOS app with chat, music, voice, video generation.
* [justrach/codedb](https://github.com/justrach/codedb) - Zig code intelligence server and MCP toolset for AI agents. Fast tree, outline, symbol, search, read, edit, deps, snapshot, and remote GitHub repo queries.
* [zolotukhin/zinc](https://github.com/zolotukhin/zinc) - Zig INferenCe Engine — Local LLM inference on AMD GPUs and Apple Silicon
* [smithersai/claude-p](https://github.com/smithersai/claude-p) - Drop-in replacement for `claude -p` that drives the interactive Claude Code TUI inside an in-process zmux PTY session.
* [justrach/codegraff](https://github.com/justrach/codegraff) - graff — a fast agentic coding harness in Zig: multi-provider, MCP, workflows, DGM evolution loop, TS/Python SDKs
* [cgbur/llama2.zig](https://github.com/cgbur/llama2.zig) - Inference Llama 2 in one file of pure Zig
* [gary23w/nl-veil](https://github.com/gary23w/nl-veil) - Open-source AI coding desktop app with parallel agents and persistent project memory. Local models, Ollama or cloud AI. Windows, macOS and Linux.
* [codejunkie99/ztk](https://github.com/codejunkie99/ztk) - CLI proxy that reduces LLM token consumption by 78%+. Single Zig binary under 260KB. Zero dependencies.
* [krillclaw/KrillClaw](https://github.com/krillclaw/KrillClaw) - The world's smallest AI agent runtime. 49KB. Written in Zig. Zero dependencies.
* [nullclaw/nullboiler](https://github.com/nullclaw/nullboiler) - Orchestrates multi-step AI agent workflows — defines execution graphs, manages shared state, dispatches work to agents, and tracks progress with checkpoints and streaming
* [kxzk/snapbench](https://github.com/kxzk/snapbench) - 📸 gotta find 'em all; spatial reasoning benchmark for LLMs
* [qskousen/ggufy](https://github.com/qskousen/ggufy) - CLI/GUI tool for efficient and easy safetensors and gguf model conversion
* [joelreymont/pz](https://github.com/joelreymont/pz) - Minimal pi coding-agent re-implementation in Zig
* [snowclipsed/moondream-zig](https://github.com/snowclipsed/moondream-zig) - moondream in zig.
* [Deins/llama.cpp.zig](https://github.com/Deins/llama.cpp.zig) - llama.cpp bindings and utilities for zig
* [colus001/pls](https://github.com/colus001/pls) - CLI tool that turns natural language into shell commands via LLM
* [justrach/devswarm](https://github.com/justrach/devswarm) - High-performance MCP server, code graph engine & evolutionary algorithm platform in Zig. 33 tools: GitHub project management, agent swarm orchestration, iterative review-fix loops, blast radius analysis, and code navigation via Model Context Protocol.
* [zouyee/dmlx](https://github.com/zouyee/dmlx) - Big models. Small Macs. Zero excuses.
* [Saimirbaci/llm.zig](https://github.com/Saimirbaci/llm.zig)
* [FOLLGAD/zig-ai](https://github.com/FOLLGAD/zig-ai) - OpenAI SDK with streaming support
* [CogitatorTech/zigformer](https://github.com/CogitatorTech/zigformer) - An educational transformer-based LLM in pure Zig
* [clebert/llama2.zig](https://github.com/clebert/llama2.zig) - Inference Llama 2 in pure Zig *(archived)*
* [LilithSemi/chock](https://github.com/LilithSemi/chock) - Sandbox first AI coding harness
* [lupin4/wintermolt](https://github.com/lupin4/wintermolt) - Open-source AI agent CLI built in Zig. A pure Zig rewrite of OpenClaw — one ~5MB binary, zero Node.js. Agentic loop, SSE streaming, tool dispatch, SQLite history, and multi-backend support (Claude, Ollama, OpenAI-compatible). Cross-compiles Mac, Linux, and Windows in one command.
* [joelreymont/banjo](https://github.com/joelreymont/banjo) - Zig implementation of Claude Code ACP adapter for Zed
* [EugenHotaj/zig_gpt2](https://github.com/EugenHotaj/zig_gpt2) - GPT-2 inference engine written in Zig
* [muhammad-fiaz/mcp.zig](https://github.com/muhammad-fiaz/mcp.zig) - A Model Context Protocol (MCP) library for the Zig ecosystem.
* [dravenk/ollama-zig](https://github.com/dravenk/ollama-zig) - Ollama Zig library
* [nullclaw/nulltickets](https://github.com/nullclaw/nulltickets) - Manages tasks and persistent storage for AI agents — assigns work, tracks completion, and provides a shared key-value store with full-text search across agent sessions
* [jaco-bro/MLX.zig](https://github.com/jaco-bro/MLX.zig) - MLX.zig: Phi-4, Llama 3.2, and Whisper in Zig

### Machine Learning Frameworks

* [ZantFoundation/Z-Ant](https://github.com/ZantFoundation/Z-Ant) - Zant simplifies the deployment and optimization of neural networks on microprocessors
* [Marco-Christiani/Zigrad](https://github.com/Marco-Christiani/Zigrad) - A deep learning framework built on an autograd engine with high level abstractions and low level control.
* [AuleTechnologies/Aule-Attention](https://github.com/AuleTechnologies/Aule-Attention) - High-performance FlashAttention-2 for AMD, Intel, and Apple GPUs. Drop-in replacement for PyTorch SDPA. Triton backend for ROCm (MI300X, RDNA3), Vulkan backend for consumer GPUs. No CUDA required.
* [SilasMarvin/dnns-from-scratch-in-zig](https://github.com/SilasMarvin/dnns-from-scratch-in-zig)
* [snowclipsed/katana](https://github.com/snowclipsed/katana) - A light tensor library in zig.
* [botirkhaltaev/turboquant](https://github.com/botirkhaltaev/turboquant) - Library for Google's Turboquant Algorithm
* [andrewCodeDev/ZEIN](https://github.com/andrewCodeDev/ZEIN) - Zig-based implementation of tensors
* [mattn/zig-tflite](https://github.com/mattn/zig-tflite) - Zig binding for TensorFlow Lite
* [recursiveGecko/onnxruntime.zig](https://github.com/recursiveGecko/onnxruntime.zig) - Incomplete experimental Zig wrapper for ONNX Runtime with examples (Silero VAD, NSNet2)

## Networking and Distributed

### Networking

* [sleep3r/mtproto.zig](https://github.com/sleep3r/mtproto.zig) - Keep the people you love connected — a tiny self-hosted Telegram proxy that hides in plain HTTPS
* [zfl9/chinadns-ng](https://github.com/zfl9/chinadns-ng) - chinadns 重构增强版，支持域名分流、ipset/nftset、UDP/TCP/DoT
* [ikskuh/zig-network](https://github.com/ikskuh/zig-network) - A smallest-common-subset of socket functions for crossplatform networking, TCP & UDP
* [karlseguin/websocket.zig](https://github.com/karlseguin/websocket.zig) - A websocket implementation for zig
* [partout-io/partout](https://github.com/partout-io/partout) - The easiest way to build cross-platform tunnel apps.
* [nikneym/ws](https://github.com/nikneym/ws) - WebSocket library for Zig ⚡
* [dantecatalfamo/zig-dns](https://github.com/dantecatalfamo/zig-dns) - Experimental DNS library implemented in zig
* [MarcoPolo/zig-libp2p](https://github.com/MarcoPolo/zig-libp2p)
* [YUX/floo](https://github.com/YUX/floo) - High-throughput, token-authenticated tunneling built in Zig.
* [endel/quic-zig](https://github.com/endel/quic-zig) - QUIC implementation in pure Zig ⚡
* [Anidetrix/sing-box-vless-mikrotik](https://github.com/Anidetrix/sing-box-vless-mikrotik) - VLESS for RouterOS using sing-box
* [lun-4/zigdig](https://github.com/lun-4/zigdig) - naive dns client library in zig
* [shiguredo/quic-client-zig](https://github.com/shiguredo/quic-client-zig) - *(archived)*
* [Corendos/ztun](https://github.com/Corendos/ztun) - An implementation of the STUN Protocol in Zig
* [ion232/reticulum-zig](https://github.com/ion232/reticulum-zig) - An implementation of Reticulum for operating systems and embedded devices
* [Quaint-Studios/Sustenet](https://github.com/Quaint-Studios/Sustenet) - Sustenet is a networking solution built with Rust and Zig, formerly C#, for game engines like Unity3D, Godot, and Unreal Engine. The primary focus is on scaling by allowing multiple servers to work together.
* [karlseguin/smtp_client.zig](https://github.com/karlseguin/smtp_client.zig) - SMTP client for Zig
* [GhostKellz/zquic](https://github.com/GhostKellz/zquic) - zquic is a lightweight, high-performance QUIC (HTTP/3 transport layer) implementation written in pure Zig.
* [lithdew/snow](https://github.com/lithdew/snow) - A small, fast, cross-platform, async Zig networking framework built on top of lithdew/pike.
* [danielpgross/friendly_neighbor](https://github.com/danielpgross/friendly_neighbor) - Server that responds to ARP (IPv4) and NDP (IPv6) requests on behalf of neighboring machines. Useful for keeping sleeping machines accessible on the network.
* [truemedian/wz](https://github.com/truemedian/wz) - *(archived)*
* [vincenzopalazzo/carl](https://github.com/vincenzopalazzo/carl) - Carl is a BitTorrent light client that preserves the privacy of the common user without requiring be Mr. Robot! ofc it is compliant with https://www.bittorrent.org/beps/bep_0000.html
* [shiguredo/quic-server-zig](https://github.com/shiguredo/quic-server-zig) - *(archived)*
* [ringtailsoftware/misshod](https://github.com/ringtailsoftware/misshod) - MiSSHod is a minimal, experimental SSH client and server implemented as a library

### RPC and Messaging

* [nats-io/nats.zig](https://github.com/nats-io/nats.zig) - Zig Client for NATS
* [ziglana/gRPC-zig](https://github.com/ziglana/gRPC-zig) - blazigly fast gRPC/MCP client & server implementation in zig
* [karlseguin/mqttz](https://github.com/karlseguin/mqttz) - MQTT client for Zig
* [lalinsky/nats.zig](https://github.com/lalinsky/nats.zig) - A Zig client library for NATS
* [dont-rely-on-nulls/zerl](https://github.com/dont-rely-on-nulls/zerl) - A Zig library to idiomatically communicate with other BEAM nodes
* [williamw520/zigjr](https://github.com/williamw520/zigjr) - A Lightweight Zig Library for JSON-RPC 2.0
* [luxluth/goose](https://github.com/luxluth/goose) - A pure Zig D-Bus implementation
* [ziglibs/antiphony](https://github.com/ziglibs/antiphony) - A zig remote procedure call solution
* [nine-lives-later/zzmq](https://github.com/nine-lives-later/zzmq) - Zig Binding for ZeroMQ
* [g41797/nats](https://github.com/g41797/nats) - Zig client for NATS Core and JetStream
* [uyha/zimq](https://github.com/uyha/zimq) - Zig binding for ZeroMQ
* [electricalgorithm/protomq](https://github.com/electricalgorithm/protomq) - ProtoMQ: Type-safe, bandwidth-efficient MQTT for the rest of us. Stop sending bloated JSON over the wire.
* [g41797/tofu](https://github.com/g41797/tofu) - Tofu - Async messaging for enterprise systems

### Distributed Systems

* [Syndica/sig](https://github.com/Syndica/sig) - a Solana validator client implementation written in Zig
* [lithdew/rheia](https://github.com/lithdew/rheia) - A blockchain written in Zig.
* [tigerbeetle/viewstamped-replication-made-famous](https://github.com/tigerbeetle/viewstamped-replication-made-famous) - A $20k consensus challenge based on TigerBeetle's implementation of the pioneering Viewstamped Replication protocol.
* [evmts/guillotine](https://github.com/evmts/guillotine) - An ultra-high performance and flexible EVM. Written in zig
* [Raiden1411/zabi](https://github.com/Raiden1411/zabi) - Interact with ethereum and EVM based chains via Zig!
* [espra/espra](https://github.com/espra/espra) - Espra: A platform to enable a decentralized economic protocol
* [blockblaz/zeam](https://github.com/blockblaz/zeam) - Ethereum Lean client in Zig (wip)
* [rauljordan/zevm](https://github.com/rauljordan/zevm) - Zig implementation of the Ethereum Virtual Machine
* [keep-starknet-strange/ziggy-starkdust](https://github.com/keep-starknet-strange/ziggy-starkdust) - ⚡ Cairo VM in Zig ⚡
* [zig-bitcoin/btczee](https://github.com/zig-bitcoin/btczee) - Bitcoin protocol implementation in Zig.
* [leishman/yam](https://github.com/leishman/yam) - Lightweight Bitcoin node connection and analysis CLI tool
* [zen-eth/eth-p2p-z](https://github.com/zen-eth/eth-p2p-z) - Ethereum p2p implementation in Zig
* [DaniPopes/zevm](https://github.com/DaniPopes/zevm) - Zig EVM
* [stateless-consensus/phant](https://github.com/stateless-consensus/phant) - A stateless Ethereum execution client
* [mtlynch/zenith](https://github.com/mtlynch/zenith) - An implementation of the Ethereum virtual machine in pure Zig.
* [lithdew/solana-zig](https://github.com/lithdew/solana-zig) - Write Solana programs in Zig.
* [starkware-bitcoin/coconut](https://github.com/starkware-bitcoin/coconut) - 🥥 Cashu wallet and mint implementation in Zig

### Cloud and Infrastructure

* [NilsIrl/dockerc](https://github.com/NilsIrl/dockerc) - container image to single executable compiler
* [jedisct1/zigly](https://github.com/jedisct1/zigly) - The easiest way to write services for Fastly's Compute@Edge in Zig.
* [nilslice/workers-zig](https://github.com/nilslice/workers-zig) - Write Cloudflare Workers in 100% Zig via WebAssembly
* [elerch/aws-sdk-for-zig](https://github.com/elerch/aws-sdk-for-zig) - AWS SDK for Zig. This is a readonly mirror of https://git.lerch.org/lobo/aws-sdk-for-zig, although Issues/PRs are welcome!
* [CraigglesO/workers-zig](https://github.com/CraigglesO/workers-zig) - Write Cloudflare Workers in Zig via WebAssembly
* [algoflows/zig-s3](https://github.com/algoflows/zig-s3) - A simple and efficient Zig native S3 client library, supporting AWS S3 and S3-compatible services like MINIO.
* [softprops/zig-lambda-runtime](https://github.com/softprops/zig-lambda-runtime) - an aws lambda runtime for zig

### Monitoring and Observability

* [open-telemetry/opentelemetry-injector](https://github.com/open-telemetry/opentelemetry-injector)
* [karlseguin/metrics.zig](https://github.com/karlseguin/metrics.zig) - Prometheus metrics for library and application developers
* [zig-o11y/opentelemetry-sdk](https://github.com/zig-o11y/opentelemetry-sdk) - An implementation of @open-telemetry SDK in @ziglang *(archived)*
* [luodaoyi/komari-zig-agent](https://github.com/luodaoyi/komari-zig-agent) - komari 的zig版本的agent, 超低资源占用，100%测试覆盖，支持所有linux的架构和发行版
* [vrischmann/zig-prometheus](https://github.com/vrischmann/zig-prometheus) - Prometheus/VictoriaMetrics client library for Zig
* [nullclaw/nullwatch](https://github.com/nullclaw/nullwatch) - Observability, tracing, evals, and experiments for nullclaw

## User Interface

### GUI Toolkits

* [vercel-labs/native](https://github.com/vercel-labs/native) - Toolkit for building native desktop apps
* [capy-ui/capy](https://github.com/capy-ui/capy) - 💻Build one codebase and get native UI on Windows, Linux and Web
* [david-vanderson/dvui](https://github.com/david-vanderson/dvui) - Immediate Zig GUI for Apps and Games
* [webui-dev/zig-webui](https://github.com/webui-dev/zig-webui) - Use any web browser or WebView as GUI, with Zig in the backend and modern web technologies in the frontend, all in a lightweight portable library.
* [duanebester/gooey](https://github.com/duanebester/gooey) - Gooey is a hybrid immediate/retained mode UI framework designed for building fast, GPU-rendered applications on macOS/Metal, WebAssembly/WebGPU, and Wayland/Vulkan
* [rcalixte/libqt6zig](https://github.com/rcalixte/libqt6zig) - Qt 6 for Zig
* [johan0A/clay-zig-bindings](https://github.com/johan0A/clay-zig-bindings) - Zig bindings for the library clay: A high performance UI layout library in C.
* [thechampagne/webview-zig](https://github.com/thechampagne/webview-zig) - ⚡ Zig binding & wrapper for a tiny cross-platform webview library to build modern cross-platform GUIs.
* [ypsvlq/wio](https://github.com/ypsvlq/wio) - windowed i/o
* [ianprime0509/zig-gobject](https://github.com/ianprime0509/zig-gobject) - GObject bindings for Zig using GObject introspection
* [ifreund/zig-wayland](https://github.com/ifreund/zig-wayland) - [mirror] Zig Wayland scanner and libwayland bindings
* [batiati/IUPforZig](https://github.com/batiati/IUPforZig) - IUP (Portable User Interface Toolkit) bindings for the Zig language. *(archived)*
* [kassane/qml_zig](https://github.com/kassane/qml_zig) - QML bindings for the Zig programming language
* [JonSnowbd/ZT](https://github.com/JonSnowbd/ZT) - A zig based Imgui Application framework *(archived)*
* [Aransentin/ZWL](https://github.com/Aransentin/ZWL) - Zig Windowing Library
* [swaywm/zig-wlroots](https://github.com/swaywm/zig-wlroots) - [mirror] Zig bindings for wlroots
* [theseyan/bunview](https://github.com/theseyan/bunview) - Feature-complete webview library for Bun
* [MoAlyousef/zfltk](https://github.com/MoAlyousef/zfltk) - Zig bindings for the FLTK gui library
* [ryupold/raygui.zig](https://github.com/ryupold/raygui.zig) - Zig bindings for raylibs raygui.h
* [DerryAlex/zig-gir-ffi](https://github.com/DerryAlex/zig-gir-ffi) - GObject Introspection for zig
* [capy-ui/zig-template](https://github.com/capy-ui/zig-template) - Simple template for creating a Capy app in Zig
* [zenolith-ui/zenolith](https://github.com/zenolith-ui/zenolith) - The GUI engine to end them all! Mirror of https://git.mzte.de/zenolith/zenolith
* [gabrielmfern/forbear](https://github.com/gabrielmfern/forbear) - GUI framework: as beautiful as the web, bare metal fast, as nice to write as React.
* [evanwashere/webview](https://github.com/evanwashere/webview) - 🕸️ webview bindings for bun runtime *(archived)*
* [gabydd/wraith](https://github.com/gabydd/wraith) - Unofficial Wayland Only Ghostty App Runtime
* [desttinghim/zig-libui-ng](https://github.com/desttinghim/zig-libui-ng) - Zig bindings for libui-ng
* [PhantomUIx/core](https://github.com/PhantomUIx/core) - A truly cross-platform GUI toolkit for Zig.

### Terminal and Console UI

* [rockorager/libvaxis](https://github.com/rockorager/libvaxis) - a modern tui library written in zig
* [meszmate/zigzag](https://github.com/meszmate/zigzag) - A Terminal UI framework for Zig
* [const-void/DOOM-fire-zig](https://github.com/const-void/DOOM-fire-zig) - DOOM's fire algo, in zig, for 256 color terminals w/no dependencies
* [akarpovskii/tuile](https://github.com/akarpovskii/tuile) - A cross-platform Text UI (TUI) library in Zig *(archived)*
* [xyaman/mibu](https://github.com/xyaman/mibu) - Zero-allocation Zig library for ANSI terminal control: colors, styling, cursor, screen, and input events.
* [tr1ckydev/chameleon](https://github.com/tr1ckydev/chameleon) - 🦎 Terminal string styling for zig.
* [adxdits/zigtui](https://github.com/adxdits/zigtui) - Build beautiful, interactive terminal applications with a simple, composable API.
* [ziglibs/ansi_term](https://github.com/ziglibs/ansi_term) - Zig library for dealing with ANSI terminals
* [M64GitHub/movy](https://github.com/M64GitHub/movy) - A terminal graphics engine for rendering, effects, and animation. Built for games, engines, and visual frameworks.
* [joachimschmidt557/linenoize](https://github.com/joachimschmidt557/linenoize) - A port of linenoise to zig
* [muhammad-fiaz/tui.zig](https://github.com/muhammad-fiaz/tui.zig) - TUI.zig is a Modern and easy-to-use Terminal User Interface (TUI) library for the Zig programming language. It provides a rich set of features to create modern, responsive, and visually appealing terminal applications with minimal effort.
* [smithersai/zmux](https://github.com/smithersai/zmux) - tmux-style PTY session multiplexer as a Zig package. Long-lived daemon owns sessions and PTY child processes; clients attach over UNIX-domain JSON-RPC.
* [Adictya/mold](https://github.com/Adictya/mold) - A high-performance TUI library with a Zig core, SolidJS frontend, and blazingly fast flexbox-like layouting.
* [ziglibs/zinput](https://github.com/ziglibs/zinput) - A Zig command-line input library!
* [dying-will-bullet/prettytable-zig](https://github.com/dying-will-bullet/prettytable-zig) - :butter: Display tabular data in a visually appealing ASCII table format.
* [xit-vcs/xitui](https://github.com/xit-vcs/xitui) - a TUI library for zig

### Mobile

* [ikskuh/ZigAndroidTemplate](https://github.com/ikskuh/ZigAndroidTemplate) - This repository contains a example on how to create a minimal Android app in Zig.
* [kubkon/zig-ios-example](https://github.com/kubkon/zig-ios-example) - Minimal build.zig for targeting iOS
* [silbinarywolf/zig-android-sdk](https://github.com/silbinarywolf/zig-android-sdk) - This library allows you to setup and build an APK for your Android devices
* [geooot/zig-sokol-crossplatform-starter](https://github.com/geooot/zig-sokol-crossplatform-starter) - A template for an app that runs on iOS, Android, PC, and Mac. Built with Sokol, and using Zig
* [kubkon/zig-deploy](https://github.com/kubkon/zig-deploy) - Deploy your iOS apps written with Zig!

### Applications and End User Tools

* [ghostty-org/ghostty](https://github.com/ghostty-org/ghostty) - 👻 Ghostty is a fast, feature-rich, and cross-platform terminal emulator that uses platform-native UI and GPU acceleration.
* [fairyglade/ly](https://github.com/fairyglade/ly) - A lightweight TUI (ncurses-like) display manager for Linux and BSD (mirror of https://codeberg.org/fairyglade/ly).
* [riverwm/river](https://github.com/riverwm/river) - [mirror] A non-monolithic Wayland compositor
* [neurocyte/flow](https://github.com/neurocyte/flow) - Flow Control: a programmer's text editor
* [neurosnap/zmx](https://github.com/neurosnap/zmx) - Session attach/detach for the terminal
* [fizzyedit/fizzy](https://github.com/fizzyedit/fizzy) - Pixel art editor made with Zig
* [coder/boo](https://github.com/coder/boo) - A GNU screen style terminal multiplexer built on libghostty.
* [Illusionna/LocalTransfer](https://github.com/Illusionna/LocalTransfer) - A fast cross-platform HTTP file server (轻量小巧快速上手的跨平台 HTTP 文件服务器互传文件)
* [freref/fancy-cat](https://github.com/freref/fancy-cat) - PDF reader for terminal emulators using the Kitty image protocol
* [ifreund/waylock](https://github.com/ifreund/waylock) - [mirror] A small, secure Wayland screenlocker
* [xuzhougeng/wispterm](https://github.com/xuzhougeng/wispterm) - A cross-platform terminal workspace for remote development and AI agent workflows, powered by libghostty-vt
* [kristoff-it/bork](https://github.com/kristoff-it/bork) - A TUI chat client tailored for livecoding on Twitch.
* [jamii/focus](https://github.com/jamii/focus) - Minimalist text editor
* [rockorager/prise](https://github.com/rockorager/prise) - a terminal multiplexer for modern terminals *(archived)*
* [paulilaaso/hys](https://github.com/paulilaaso/hys) - Terminal RSS Reader for Digital Minimalists — Tool for Escaping the Doomscroll
* [kewuaa/kwm](https://github.com/kewuaa/kwm) - A window manager based on River Wayland compositor.
* [semos-labs/attyx](https://github.com/semos-labs/attyx) - GPU accelerated terminal for agentic workflows
* [EsportToys/LibreScroll](https://github.com/EsportToys/LibreScroll) - Smooth inertial scrolling with any regular mouse.
* [fabioarnold/MiniPixel](https://github.com/fabioarnold/MiniPixel) - A tiny pixel art editor
* [rockorager/monstar](https://github.com/rockorager/monstar) - wayland terminal based on libghostty. cpu rendered, like foot
* [18alantom/fex](https://github.com/18alantom/fex) - A command-line file explorer prioritizing quick navigation.
* [akiyosi/zonvie](https://github.com/akiyosi/zonvie) - 🧟 Zonvie is a Fast, feature-rich Neovim GUI built with Zig, native on macOS and Windows.
* [no1msd/seance](https://github.com/no1msd/seance) - A scrolling terminal multiplexer that tracks your AI coding agents.
* [fifty-six/zig.SteamManifestPatcher](https://github.com/fifty-six/zig.SteamManifestPatcher) - Patches steam at runtime to re-allow the use of download_depot to downpatch games. *(archived)*
* [waycrate/NextWM](https://github.com/waycrate/NextWM) - Manual tiling wayland compositor. ( Work In Progress )
* [joelreymont/dots](https://github.com/joelreymont/dots) - Connect the dots - minimal task tracker in Zig
* [dancinlab/void](https://github.com/dancinlab/void) - 🕳️ VOID — Terminal emulator written in hexa-lang.
* [M64GitHub/movycat](https://github.com/M64GitHub/movycat) - A terminal movie player written in Zig. Like catimg, but for videos.
* [sin-ack/papertoy](https://github.com/sin-ack/papertoy) - Run a Shadertoy-compatible shader as an animated wallpaper on Wayland
* [BrookJeynes/jido](https://github.com/BrookJeynes/jido) - 地圖 (Jido) is a lightweight Unix TUI file explorer designed for speed and simplicity.
* [debpalash/Opal](https://github.com/debpalash/Opal) - Opal — The open-source everything media player & browser. Jellyfin/Stremio/Kodi alternative for macOS, Linux & Windows.
* [greenfork/kisa](https://github.com/greenfork/kisa) - Text editor of the new world
* [spiral-ladder/gram](https://github.com/spiral-ladder/gram) - A Zig port of the kilo editor, in less than 1000 LOC.
* [nmeum/creek](https://github.com/nmeum/creek) - A malleable and minimalist status bar for the River compositor
* [midasdf/zt](https://github.com/midasdf/zt) - ⚡zt — the fastest terminal emulator. 88 MB/s throughput. 5.5ms startup. 2MB memory. Pure Zig.
* [Luukdegram/juicebox](https://github.com/Luukdegram/juicebox) - Tiled Window Manager written in Zig
* [Sarv/SarvTerminal](https://github.com/Sarv/SarvTerminal) - Fast, open-source macOS terminal + SSH connection manager — saved-host vault, SFTP/SCP, SSH keys, tunnels, Docker/K8s attach, AI command assist, and zero-knowledge settings sync.
* [TheFox/cmus-control](https://github.com/TheFox/cmus-control) - Control cmus with Media Keys :rewind: :arrow_forward: :fast_forward: under OS X.
* [rockorager/comlink](https://github.com/rockorager/comlink) - An experimental IRC client
* [DynamiByte/Endfield-Uncensored](https://github.com/DynamiByte/Endfield-Uncensored) - A tool that removes the transparency filter of Endfield in Vulkan
* [ringtailsoftware/commy](https://github.com/ringtailsoftware/commy) - A serial monitor for Mac, Linux and Windows
* [forketyfork/architect](https://github.com/forketyfork/architect) - A flexible terminal grid for multi-agent AI workflows
* [donpdonp/zootdeck](https://github.com/donpdonp/zootdeck) - A Linux Fediverse Desktop Reader (alpha)
* [lun-4/awtfdb](https://github.com/lun-4/awtfdb) - the Anime Woman's Tagged File Data Base.
* [parkers0405/ghostty-pixel-scroll](https://github.com/parkers0405/ghostty-pixel-scroll) - Ghostty fork with Neovide-style pixel-perfect scrolling and smooth cursor animations
* [AFreeChameleon/multask](https://github.com/AFreeChameleon/multask) - A process manager for linux, mac & windows to simplify your developer environment.
* [lun-4/obsidian2web](https://github.com/lun-4/obsidian2web) - my obsidian publish knockoff that generates (largely static) websites
* [theMackabu/ink](https://github.com/theMackabu/ink) - multipurpose markdown viewer
* [malcolmstill/foxwhale](https://github.com/malcolmstill/foxwhale) - A Wayland compositor written in Zig
* [slastra/hyprglaze](https://github.com/slastra/hyprglaze) - Wayland shader wallpaper daemon for Hyprland with modular effects, color schemes, and AI desktop buddy
* [schmee/habu](https://github.com/schmee/habu) - A TUI habit tracker
* [TristanJet/muzi](https://github.com/TristanJet/muzi) - A snappy, slick terminal client for MPD with vim-keybindings and fuzzy-finding written in Zig.
* [Mario-SO/zigitor](https://github.com/Mario-SO/zigitor) - Video editor written in Zig ⚡ using raylib
* [atasoya/carbonara](https://github.com/atasoya/carbonara) - Tech feeds in your terminal cooked al dente with Zig
* [flouthoc/ztick](https://github.com/flouthoc/ztick) - tiny desktop utility to keep notes ( with no features ). Written in zig and gtk4
* [Foundation42/CASSANDRA](https://github.com/Foundation42/CASSANDRA) - OSINT: Live map of the world's signals — news, ships, planes, and whatever comes next.
* [isaac-westaway/Zenith](https://github.com/isaac-westaway/Zenith) - Tiling Zig Window Manager
* [kdchambers/reel](https://github.com/kdchambers/reel) - Screen capture software for Linux / Wayland
* [MakotoArai-CN/Velora](https://github.com/MakotoArai-CN/Velora) - Velora是一个使用Zig编写的多站点API Key管理器，用于统一管理并快速切换Codex、Claude Code、OpenCode等工具的API Key配置。
* [ivanjermakov/hat](https://github.com/ivanjermakov/hat) - Hackable modal text editor for modern terminals
* [getSilver/Ringwin](https://github.com/getSilver/Ringwin) - This is a trading system written in the Zig language.

## Graphics and Media

### Graphics and Rendering

* [letoram/arcan](https://github.com/letoram/arcan) - The owls are not what they seem.
* [Snektron/vulkan-zig](https://github.com/Snektron/vulkan-zig) - Vulkan binding generator for Zig
* [ziglibs/zgl](https://github.com/ziglibs/zgl) - Zig OpenGL Wrapper
* [fubark/cosmic](https://github.com/fubark/cosmic) - A platform for computing and creating applications.
* [vancluever/z2d](https://github.com/vancluever/z2d) - Pure Zig 2D graphics library
* [TinyVG/sdk](https://github.com/TinyVG/sdk) - TinyVG software development kit
* [mkeeter/futureproof](https://github.com/mkeeter/futureproof) - A live editor for fragment shaders, powered by Neovim, WebGPU, and Zig!
* [hexops-graveyard/mach-gpu](https://github.com/hexops-graveyard/mach-gpu) - mach/gpu: truly cross-platform WebGPU graphics for Zig
* [hexops-graveyard/mach-core](https://github.com/hexops-graveyard/mach-core) - window+input+GPU, truly cross-platform
* [ikskuh/zero-graphics](https://github.com/ikskuh/zero-graphics) - Application framework based on OpenGL ES 2.0. Runs on desktop machines, Android phones and the web
* [castholm/zigglgen](https://github.com/castholm/zigglgen) - Zig OpenGL binding generator
* [mkeeter/rayray](https://github.com/mkeeter/rayray) - A tiny GPU raytracer, using Zig and WebGPU
* [IridescenceTech/zglfw](https://github.com/IridescenceTech/zglfw) - A thin, idiomatic wrapper for GLFW. Written in Zig, for Zig!
* [hexops-graveyard/mach-gpu-dawn](https://github.com/hexops-graveyard/mach-gpu-dawn) - Google's Dawn WebGPU implementation, cross-compiled with Zig into a single static library
* [ashpil/moonshine](https://github.com/ashpil/moonshine) - A spectral path tracer built with Zig + Vulkan
* [bronter/wgpu_native_zig](https://github.com/bronter/wgpu_native_zig) - Zig bindings for wgpu-native
* [hexops-graveyard/mach-sysgpu](https://github.com/hexops-graveyard/mach-sysgpu) - Highly experimental, blazingly fast, lean & mean descendant of WebGPU written in Zig
* [kooparse/zgltf](https://github.com/kooparse/zgltf) - A glTF parser for Zig codebase.
* [PavelDoGreat/Fluid-Simulation](https://github.com/PavelDoGreat/Fluid-Simulation) - This project will be a complete rewrite of my mobile app Fluid Simulation. It will be done in an open-source way and hopefully will inspire many people around the world.
* [prime31/zig-renderkit](https://github.com/prime31/zig-renderkit)
* [hexops-graveyard/mach-freetype](https://github.com/hexops-graveyard/mach-freetype) - Ziggified Freetype 2 bindings with zero-fuss installation, cross compilation, and more.
* [floooh/sokol-tools-bin](https://github.com/floooh/sokol-tools-bin) - Binaries and fips integration for https://github.com/floooh/sokol-tools
* [Games-by-Mason/shader_compiler](https://github.com/Games-by-Mason/shader_compiler) - Glslang ported to be usable via Zig's build system.
* [Avokadoen/zig_vulkan](https://github.com/Avokadoen/zig_vulkan) - Toying with vulkan and zig
* [Games-by-Mason/Zex](https://github.com/Games-by-Mason/Zex) - A texture utility for Zig.
* [JosefAlbers/zigon](https://github.com/JosefAlbers/zigon) - Zigon: A procedural 3D terrain generator and visualizer written in Zig using Raylib
* [kdchambers/vkwayland](https://github.com/kdchambers/vkwayland) - Reference application for Vulkan / Wayland
* [quag/zig-generative-template](https://github.com/quag/zig-generative-template) - Zig framework for generating png images (single or multiple frames.)
* [Thomvanoorschot/zignite](https://github.com/Thomvanoorschot/zignite) - Zignite is a Cross-platform graphics engine built with Zig, featuring WebGPU rendering using GLFW for window management. It has WebAssembly and native support
* [nDimensional/andromeda](https://github.com/nDimensional/andromeda) - High-performance graph layout engine
* [ziglibs/fontaine](https://github.com/ziglibs/fontaine) - A library to support text rendering in arbitrary contexts
* [pdoane/metal-zig](https://github.com/pdoane/metal-zig) - Low-overhead Zig interface for Metal

### Game Development

* [hexops/mach](https://github.com/hexops/mach) - zig game engine & graphics toolkit - mirror of https://code.hexops.com/hexops/mach
* [PixelGuys/Cubyz](https://github.com/PixelGuys/Cubyz) - Voxel sandbox game with a large render distance, procedurally generated content and some cool graphical effects.
* [zig-gamedev/zig-gamedev](https://github.com/zig-gamedev/zig-gamedev) - Dev repo for @zig-gamedev libs and sample applications
* [raylib-zig/raylib-zig](https://github.com/raylib-zig/raylib-zig) - Manually tweaked, auto-generated raylib bindings for zig. https://github.com/raysan5/raylib
* [andrewrk/tetris](https://github.com/andrewrk/tetris) - A simple tetris clone written in zig programming language.
* [prime31/zig-ecs](https://github.com/prime31/zig-ecs)
* [wendigojaeger/ZigGBA](https://github.com/wendigojaeger/ZigGBA) - Work in progress SDK for creating Game Boy Advance games using Zig programming language.
* [Jack-Ji/jok](https://github.com/Jack-Ji/jok) - A minimal 2d/3d game framework for @ziglang. *(archived)*
* [pkmn/engine](https://github.com/pkmn/engine) - A minimal, complete, Pokémon battle simulation engine optimized for performance
* [Interrupt/delve-framework](https://github.com/Interrupt/delve-framework) - Delve is a framework for writing Games in Zig and Lua. For those who value being cross platform and keeping things simple.
* [foxnne/aftersun](https://github.com/foxnne/aftersun) - Top-down 2D RPG
* [godot-zig/godot-zig](https://github.com/godot-zig/godot-zig) - Zig bindings for Godot 4
* [floooh/pacman.zig](https://github.com/floooh/pacman.zig) - Simple Pacman clone written in Zig.
* [Gota7/zig-sdl3](https://github.com/Gota7/zig-sdl3) - Zig wrapper for SDL3. *(archived)*
* [ryupold/raylib.zig](https://github.com/ryupold/raylib.zig) - Idiomatic Zig bindings for raylib utilizing raylib_parser
* [Senryoku/Deecy](https://github.com/Senryoku/Deecy) - Dreamcast emulator written in Zig
* [gdzig/gdzig](https://github.com/gdzig/gdzig) - Zig bindings for Godot 4
* [fengb/fundude](https://github.com/fengb/fundude) - Gameboy emulator: Zig -> wasm *(archived)*
* [Games-by-Mason/ZCS](https://github.com/Games-by-Mason/ZCS) - A Zig ECS.
* [kiedtl/roguelike](https://github.com/kiedtl/roguelike) - A stealth roguelike in development phase.
* [floooh/chipz](https://github.com/floooh/chipz) - 8-bit emulator experiments in Zig
* [prime31/zig-upaya](https://github.com/prime31/zig-upaya) - Zig-based framework for creating game tools and helper apps *(archived)*
* [prime31/zig-gamekit](https://github.com/prime31/zig-gamekit) - Companion repo for zig-renderkit for making 2D games
* [thimenesup/GodotZigBindings](https://github.com/thimenesup/GodotZigBindings) - Zig lang bindings for Godot Engine GDNative and GDExtension
* [maxpoletaev/nupsx](https://github.com/maxpoletaev/nupsx) - PlayStation 1 emulator
* [DanB91/Zig-Playdate-Template](https://github.com/DanB91/Zig-Playdate-Template) - Starter code for a Playdate program written in Zig
* [SnowballSH/Avalanche](https://github.com/SnowballSH/Avalanche) - UCI Chess Engine written in Zig.
* [thejoshwolfe/legend-of-swarkland](https://github.com/thejoshwolfe/legend-of-swarkland) - Turn-based action fantasy puzzle game inspired by NetHack and Crypt of the Necrodancer
* [CrossCraft/CrossCraft](https://github.com/CrossCraft/CrossCraft) - CrossCraft is an open-source Minecraft reimplementation: 🎮 Faithful, Version by Version 🌍 Native on PSP, 3DS, Switch & PC ⚡ Powered by Zig and Aether
* [fabioarnold/zeroman](https://github.com/fabioarnold/zeroman)
* [zenith391/didot](https://github.com/zenith391/didot) - Zig 3D game engine. *(archived)*
* [JonathanHallstrom/pawnocchio](https://github.com/JonathanHallstrom/pawnocchio) - chess engine, goal is to make it strong. currently plays good chess
* [jdah/zigsteroids](https://github.com/jdah/zigsteroids) - asteroids in zig
* [lukewilliamboswell/roc-wasm4](https://github.com/lukewilliamboswell/roc-wasm4) - Build wasm4 games using Roc
* [srijan-paul/nez](https://github.com/srijan-paul/nez) - An emulator for the NES. For fun and profit and all that.
* [tsoding/zigout](https://github.com/tsoding/zigout) - An attempt to implement breakout in Zig
* [allyourcodebase/SDL](https://github.com/allyourcodebase/SDL) - SDL ported to the Zig build system.
* [Guigui220D/zig-sfml-wrapper](https://github.com/Guigui220D/zig-sfml-wrapper) - A zig wrapper for csfml
* [nmalthouse/rathammer](https://github.com/nmalthouse/rathammer) - An editor for Valve's VMF maps. MOVED to https://sr.ht/~niklasm/rathammer/ *(archived)*
* [michal-z/zig-d3d12-starter](https://github.com/michal-z/zig-d3d12-starter) - Simple game written from scratch in Zig
* [Games-by-Mason/Tween](https://github.com/Games-by-Mason/Tween) - Common easing and interpolation functions for game development.
* [floooh/kc85.zig](https://github.com/floooh/kc85.zig) - A KC85 emulator written in Zig *(archived)*
* [TM35-Metronome/metronome](https://github.com/TM35-Metronome/metronome) - A set of tools for modifying and randomizing Pokémon games
* [ikskuh/Ziguana-Game-System](https://github.com/ikskuh/Ziguana-Game-System) - A retro-style gaming console running on bare x86 metal written in Zig
* [natecraddock/open-reckless-drivin](https://github.com/natecraddock/open-reckless-drivin) - A work-in-progress open source reimplementation of the classic Macintosh shareware game Reckless Drivin'
* [zig-community/Zig-Showdown](https://github.com/zig-community/Zig-Showdown) - A community effort to create a small multiplayer 3D shooter game in pure zig
* [lizard-demon/fps](https://github.com/lizard-demon/fps) - Simplest possible voxel engine in sokol.
* [Mar7thLover/Himeko-Nova-SR](https://github.com/Mar7thLover/Himeko-Nova-SR) - A re-implementation of a game server with opensrc.
* [thexeondev/remielle](https://github.com/thexeondev/remielle) - Zenless Zone Zero server emulator focused on efficiency, stability and correctness.
* [M64GitHub/1st-shot](https://github.com/M64GitHub/1st-shot) - A terminal bullet hell dream
* [paoda/zba](https://github.com/paoda/zba) - Game Boy Advance Emulator. Yes, I'm awful with project names.
* [Lommix/knoedel](https://github.com/Lommix/knoedel) - Data oriented application framework written in Zig (ECS). Very similar API to Bevy
* [zenith391/Stella-Dei](https://github.com/zenith391/Stella-Dei) - SimEarth-like sandbox game where you can make and develop your very own planet
* [CrossCraft/CrossCraft-Classic-Server](https://github.com/CrossCraft/CrossCraft-Classic-Server) - A Minecraft Classic Server compatible with all Minecraft Classic Clients *(archived)*
* [GasInfinity/zitrus](https://github.com/GasInfinity/zitrus) - Mirror of https://codeberg.org/GasInfinity/zitrus
* [Ryp/gb-emu-zig](https://github.com/Ryp/gb-emu-zig) - Gameboy emulator written in Zig
* [NunoDasNeves/Dungeon-Wizard](https://github.com/NunoDasNeves/Dungeon-Wizard) - Action roguelike deckbuilder game in Zig
* [jakehffn/zig-nes](https://github.com/jakehffn/zig-nes) - NES emulator written in Zig⚡
* [linuxy/coyote-ecs](https://github.com/linuxy/coyote-ecs) - A fast and simple zig native ECS.
* [SmileYik/GTNH-OC-AE-Controller](https://github.com/SmileYik/GTNH-OC-AE-Controller) - Order the items in AE on the web. https://blog.smileyik.eu.org/oc-ae/
* [felixuxx/zsdl3](https://github.com/felixuxx/zsdl3) - high quality zig bindings for low-level access to sdl3's multimedia capabilities for game and application development.
* [rcmagic/ZigFightingGame](https://github.com/rcmagic/ZigFightingGame) - A fighting game implemented in the Zig programming language.
* [Avokadoen/ecez](https://github.com/Avokadoen/ecez) - An ECS API for Zig! *(archived)*
* [fengb/zig-wii](https://github.com/fengb/zig-wii)
* [peterino2/NeonWood](https://github.com/peterino2/NeonWood) - A game engine written in zig (development is concluded)
* [silversquirl/phyz](https://github.com/silversquirl/phyz) - 2D game physics for Zig
* [allyourcodebase/VVVVVV](https://github.com/allyourcodebase/VVVVVV) - The game VVVVVV ported to the Zig build system.
* [alvarorichard/RISC8Emulator](https://github.com/alvarorichard/RISC8Emulator) - RISC8Emulator is a software recreation of the CHIP-8 system, a simple computer from the mid-1970s primarily used for playing video games.
* [TheWaWaR/bobby-carrot](https://github.com/TheWaWaR/bobby-carrot) - Game Bobby Carrot in Rust/Haxe/Zig
* [trevorswan11/water](https://github.com/trevorswan11/water) - A zig chess library and engine.
* [ringtailsoftware/zigtris](https://github.com/ringtailsoftware/zigtris) - A minimal terminal Tetris written in Zig

### Audio

* [orhun/linuxwave](https://github.com/orhun/linuxwave) - Generate music from the entropy of Linux 🐧🎵
* [robbielyman/seamstress-v1](https://github.com/robbielyman/seamstress-v1) - seamstress is an art engine
* [boomlinde/pocketacid](https://github.com/boomlinde/pocketacid) - Music sequencer for cheap gaming handhelds
* [sinshu/ziggysynth](https://github.com/sinshu/ziggysynth) - A SoundFont MIDI synthesizer written in pure Zig
* [ArborealAudio/arbor](https://github.com/ArborealAudio/arbor) - Easy-to-use audio plugin framework
* [schroffl/zig-vst](https://github.com/schroffl/zig-vst) - Aims to provide high- and low-level utilites for building VST 2.4 plugins with Zig
* [squeek502/audiometa](https://github.com/squeek502/audiometa) - An audio metadata/tag reading library written in Zig
* [Hejsil/zig-midi](https://github.com/Hejsil/zig-midi) - *(archived)*
* [allyourcodebase/pipewire](https://github.com/allyourcodebase/pipewire) - pipewire ported to the zig build system
* [prime31/zig-miniaudio](https://github.com/prime31/zig-miniaudio)
* [ziglibs/zig-lv2](https://github.com/ziglibs/zig-lv2) - Zig-intuitive bindings for LV2.
* [hexops-graveyard/mach-sysaudio](https://github.com/hexops-graveyard/mach-sysaudio) - cross-platform low-level audio IO in Zig

### Image and Video

* [dmtrKovalenko/odiff](https://github.com/dmtrKovalenko/odiff) - A very fast SIMD-first image comparison library (with nodejs API)
* [zigimg/zigimg](https://github.com/zigimg/zigimg) - Zig library for reading and writing different image formats
* [seatedro/glyph](https://github.com/seatedro/glyph) - convert images, video to ascii!
* [arrufat/zignal](https://github.com/arrufat/zignal) - zero-dependency image processing library
* [ikskuh/zig-qoi](https://github.com/ikskuh/zig-qoi) - Quite OK Image format encoder/decoder written in Zig
* [sphaerophoria/video-editor](https://github.com/sphaerophoria/video-editor)
* [gianni-rosato/oavif](https://github.com/gianni-rosato/oavif) - Target quality AVIF encoding
* [dnjulek/vapoursynth-zip](https://github.com/dnjulek/vapoursynth-zip) - VapourSynth Zig Image Process ⚡🎞️
* [gianni-rosato/fssimu2](https://github.com/gianni-rosato/fssimu2) - Fast SSIMULACRA2 derivative implementation in Zig.
* [ikskuh/TinyVG](https://github.com/ikskuh/TinyVG) - A new format for vector graphics: Tiny vector graphics *(archived)*
* [adworacz/zsmooth](https://github.com/adworacz/zsmooth) - Cross-platform, cross-architecture video smoothing functions for Vapoursynth, written in Zig

## Security

### Cryptography

* [ianic/tls.zig](https://github.com/ianic/tls.zig) - TLS 1.3/1.2 client and TLS 1.3 server in Zig
* [jedisct1/zig-minisign](https://github.com/jedisct1/zig-minisign) - Minisign reimplemented in Zig.
* [shiguredo/tls13-zig](https://github.com/shiguredo/tls13-zig) - The first TLS1.3 implementation in Zig(master/HEAD) only with std. *(archived)*
* [jedisct1/turbocrypt](https://github.com/jedisct1/turbocrypt) - A fast, easy-to-use, and secure command-line tool for encrypting and decrypting files , git repositories and directory trees.
* [ubavic/srb-id-pkcs11](https://github.com/ubavic/srb-id-pkcs11) - Open source PKCS#11 module for Serbian ID cards
* [alexnask/iguanaTLS](https://github.com/alexnask/iguanaTLS) - Minimal, experimental TLS 1.2 implementation in Zig
* [jedisct1/zig-charm](https://github.com/jedisct1/zig-charm) - A Zig version of the Charm crypto library.
* [jedisct1/boringssl-wasm](https://github.com/jedisct1/boringssl-wasm) - BoringSSL for WebAssembly/WASI
* [jsign/verkle-crypto](https://github.com/jsign/verkle-crypto) - Cryptography for Ethereum Verkle Trees
* [thedonutfactory/zig-tfhe](https://github.com/thedonutfactory/zig-tfhe) - 🐊 A pure zig implementation of TFHE Fully Homomorphic Encryption Scheme
* [jedisct1/aegis-X](https://github.com/jedisct1/aegis-X) - The AEGIS-128X and AEGIS-256X high performance ciphers.
* [ikskuh/zig-bearssl](https://github.com/ikskuh/zig-bearssl) - A BearSSL binding for Zig
* [jsign/zig-stealth-addresses](https://github.com/jsign/zig-stealth-addresses) - A Zig implementation of Ethereum stealth addresses (ERC-5564)
* [kubkon/zignature](https://github.com/kubkon/zignature) - codesign your Apple apps with Zig!

### Security Tools

* [0xsp-SRD/ZigStrike](https://github.com/0xsp-SRD/ZigStrike) - ZigStrike, a powerful Payload Delivery Pipeline developed in Zig, offering a variety of injection techniques and anti-sandbox features.
* [The-Z-Labs/bof-launcher](https://github.com/The-Z-Labs/bof-launcher) - [ BOF-LAUNCHER ] -> an API for loading, executing and in-memory masking BOFs on Windows and Linux for use in C/Zig/Go/Rust agents/implants. [ Z-BEAC0N ] -> a custom-written stage-1 (aka pre-C2) solution engineered with a small footprint, stealth and modularity in mind.
* [darkr4y/OffensiveZig](https://github.com/darkr4y/OffensiveZig) - Some attempts at using Zig(https://ziglang.org/) in penetration testing.
* [TheFox/keylogger](https://github.com/TheFox/keylogger) - Keylogger for Windows.
* [CX330Blake/ZYRA](https://github.com/CX330Blake/ZYRA) - ZYRA: Your Runtime Armor. ZYRA is an Zig-written obfuscator/packer for executable binaries.
* [The-Z-Labs/cli4bofs](https://github.com/The-Z-Labs/cli4bofs) - A swiss army knife tool for running, injecting and organizing your BOFs collection *(archived)*
* [0xsp-SRD/aether](https://github.com/0xsp-SRD/aether) - Aether is a Windows memory-forensics and threat hunting tool that scans live process memory for malicious pattern, detect injection techniques, implant signatures, reflectively loaded .NET assemblies. it works with a multi-layer confidence model that dramatically reduce the false positive rate and hunt for malicious behaviour.
* [Thoxy67/zig-pe](https://github.com/Thoxy67/zig-pe) - Reflective PE loader written in Zig. Loads and executes native and .NET PE files directly from memory.
* [mgord9518/aisap](https://github.com/mgord9518/aisap) - Tool to make sandboxing AppImages easy
* [kristoff-it/zig-afl-kit](https://github.com/kristoff-it/zig-afl-kit) - Convenience functions for easy integration with AFL++ for both Zig and C/C++ programmers!
* [squeek502/zig-std-lib-fuzzing](https://github.com/squeek502/zig-std-lib-fuzzing) - A set of fuzzers for fuzzing various parts of the Zig standard library
* [christopherkarani/ryk](https://github.com/christopherkarani/ryk) - Local guardrails for coding agents. Policy, approvals, 86 safety packs, OS sandbox, audit trail — no Docker.
* [TheFox/synflood](https://github.com/TheFox/synflood) - Start a SYN flood attack to an ip address.

### Authentication and Authorization

* [linyows/octopass](https://github.com/linyows/octopass) - Octopass brings GitHub's team management to your Linux servers. No more manually managing /etc/passwd or distributing SSH keys — just add users to your GitHub team, and they're ready to SSH into your servers.
* [Zig-Sec/PassKeeZ](https://github.com/Zig-Sec/PassKeeZ) - This is a mirror. Work is continued on Codeberg: https://codeberg.org/r4gus/PassKeeZ
* [Zig-Sec/keylib](https://github.com/Zig-Sec/keylib) - work is continued on codberg: https://codeberg.org/r4gus/keylib
* [leroycep/zig-jwt](https://github.com/leroycep/zig-jwt) - JSON Web Tokens for Zig
* [uzyn/passcay](https://github.com/uzyn/passcay) - 🦎🔑 Secure & fast Passkey (WebAuthn) library for Zig

### Reverse Engineering

* [duty1g/x64dbg-mcp-server](https://github.com/duty1g/x64dbg-mcp-server) - x64dbg-MCP Server is a native MCP (Model Context Protocol) plugin for x64dbg that exposes the debugger's full functionality over HTTP. Connect any MCP-compatible AI assistant and control x64dbg programmatically: set breakpoints, step through code, read memory, dump registers, and more. Built with Zig — zero dependencies, single-binary output, cros
* [Ronsor/riscv-zig](https://github.com/Ronsor/riscv-zig) - A RISC-V emulator written in Zig
* [kubkon/zacho](https://github.com/kubkon/zacho) - Like otool but written from scratch in Zig *(archived)*
* [kubkon/zig-dis-x86_64](https://github.com/kubkon/zig-dis-x86_64) - x86_64 disassembler library written in Zig
* [ringtailsoftware/zig-minirv32](https://github.com/ringtailsoftware/zig-minirv32) - Zig RISC-V32 emulator with Linux and baremetal examples
* [kubkon/zcoff](https://github.com/kubkon/zcoff) - Like dumpbin.exe but cross-platform

## Concurrency and Performance

### Concurrency and Parallelism

* [mitchellh/libxev](https://github.com/mitchellh/libxev) - libxev is a cross-platform, high-performance event loop that provides abstractions for non-blocking IO, timers, events, and more and works on Linux (io_uring or epoll), macOS (kqueue), and Wasm + WASI. Available as both a Zig and C API.
* [judofyr/spice](https://github.com/judofyr/spice) - Fine-grained parallelism with sub-nanosecond overhead in Zig
* [lalinsky/zio](https://github.com/lalinsky/zio) - Async I/O framework for Zig
* [kprotty/zap](https://github.com/kprotty/zap) - An asynchronous runtime with a focus on performance and resource efficiency.
* [Cloudef/zig-aio](https://github.com/Cloudef/zig-aio) - io_uring like asynchronous API and coroutine powered IO tasks for zig
* [tardy-org/tardy](https://github.com/tardy-org/tardy) - An asynchronous runtime for writing applications and services. Supports io_uring, epoll, kqueue, and poll for I/O.
* [rsepassi/zigcoro](https://github.com/rsepassi/zigcoro) - A Zig coroutine library
* [kython28/leviathan](https://github.com/kython28/leviathan) - A lightning-fast Zig-powered event loop for Python's asyncio.
* [boonzy00/ringmpsc](https://github.com/boonzy00/ringmpsc) - Lock-free MPSC channel in Zig achieving 180+ billion messages/second via ring-decomposed architecture
* [lithdew/pike](https://github.com/lithdew/pike) - Async I/O for Zig
* [rockorager/ourio](https://github.com/rockorager/ourio) - An asynchronous IO runtime
* [YoSTEALTH/Liburing](https://github.com/YoSTEALTH/Liburing) - Liburing is Python + Zig wrapper around C Liburing, which is a helper to setup and tear-down io_uring instances.
* [saltzm/async_io_uring](https://github.com/saltzm/async_io_uring) - An event loop in Zig using io_uring and coroutines
* [g41797/mailbox](https://github.com/g41797/mailbox) - Zig Mailbox is convenient inter-thread communication mechanism.
* [Thomvanoorschot/backstage](https://github.com/Thomvanoorschot/backstage) - This repository contains an experimental actor framework built using the Zig programming language. The framework implements actor-based concurrent programming patterns, including message passing between actors, actor lifecycle management, and state isolation. It leverages the libxev library for its event loop and concurrency.
* [sbancuz/OpenMP-zig](https://github.com/sbancuz/OpenMP-zig) - An implementation of the OpenMP directives for Zig
* [kprotty/zefi](https://github.com/kprotty/zefi) - Zig Fiber Library (experiments; wip)
* [yrashk/zig-generator](https://github.com/yrashk/zig-generator) - Async generator type for Zig
* [Jack-Ji/zig-async](https://github.com/Jack-Ji/zig-async) - A simple and easy to use async task library for zig.
* [erik-dunteman/chanz](https://github.com/erik-dunteman/chanz) - Go channels implemented in zig
* [kprotty/zig-adaptive-lock](https://github.com/kprotty/zig-adaptive-lock) - Benchmarking a faster std.Mutex implementation for Zig

### Performance and Optimization

* [andrewrk/poop](https://github.com/andrewrk/poop) - Performance Optimizer Observation Platform
* [teamchong/turboquant-wasm](https://github.com/teamchong/turboquant-wasm) - TurboQuant WASM SIMD vector compression — 3 bits/dim with fast dot product. Requires relaxed SIMD (Chrome 114+, Firefox 128+, Safari 18+, Node 20+)
* [ziglang/gotta-go-fast](https://github.com/ziglang/gotta-go-fast) - Performance Tracking for Zig *(archived)*
* [hendriknielaender/zBench](https://github.com/hendriknielaender/zBench) - 📊 zig benchmark
* [mitchellh/zig-libgc](https://github.com/mitchellh/zig-libgc) - Zig-friendly library for interfacing with libgc (bdwgc) -- the Boehm-Demers-Weiser conservative garbage collector
* [akhildevelops/cudaz](https://github.com/akhildevelops/cudaz) - Cuda library for Zig
* [fengb/zee_alloc](https://github.com/fengb/zee_alloc) - tiny Zig allocator primarily targeting WebAssembly *(archived)*
* [Hejsil/zig-bench](https://github.com/Hejsil/zig-bench) - Simple benchmarking library
* [suirad/adma](https://github.com/suirad/adma) - A general purpose, multithreaded capable slab allocator for Zig
* [orhun/zig-http-benchmarks](https://github.com/orhun/zig-http-benchmarks) - Benchmarking Zig HTTP client against Rust, Go, Python, C++ and curl
* [Senryoku/smol-string](https://github.com/Senryoku/smol-string) - Compression for browsers' localStorage. Alternative to lz-string written in Zig.
* [andrewrk/CarmensPlayground](https://github.com/andrewrk/CarmensPlayground) - zig allocator playground
* [joadnacer/jdz_allocator](https://github.com/joadnacer/jdz_allocator) - Zig General Purpose Memory Allocator
* [judofyr/minz](https://github.com/judofyr/minz) - Minimal string compression
* [andrewrk/zig-general-purpose-allocator](https://github.com/andrewrk/zig-general-purpose-allocator) - work-in-progress general purpose allocator intended to be eventually merged into Zig standard library. live streamed development
* [ianic/flate](https://github.com/ianic/flate) - deflate compression algorithm in Zig *(archived)*
* [dweiller/zimalloc](https://github.com/dweiller/zimalloc) - General purpose allocator for Zig
* [Hejsil/zig-gc](https://github.com/Hejsil/zig-gc) - A super simple mark-and-sweep garbage collector written in Zig. *(archived)*
* [Justus2308/zuballoc](https://github.com/Justus2308/zuballoc) - A hard realtime O(1) allocator for sub-allocating memory regions with minimal fragmentation.
* [aqrit/sse2zig](https://github.com/aqrit/sse2zig) - SSE intrinsics for ziglang
* [gsquire/zig-snappy](https://github.com/gsquire/zig-snappy) - Snappy compression for Zig
* [romance-dev/speedboost](https://github.com/romance-dev/speedboost) - Call C functions from Go without CGO. +Zig example included.
* [tr1ckydev/zoop](https://github.com/tr1ckydev/zoop) - A benchmarking library for zig.
* [verte-zerg/lauka](https://github.com/verte-zerg/lauka) - Apple Silicon PMU counter benchmark

## Testing and Quality

### Testing

* [sb2bg/marionette](https://github.com/sb2bg/marionette) - Marionette is a deterministic simulation testing (DST) library for Zig.
* [kristoff-it/zig-doctest](https://github.com/kristoff-it/zig-doctest) - A tool for testing snippets of code, useful for websites and books that talk about Zig.
* [mnemnion/ohsnap](https://github.com/mnemnion/ohsnap) - Oh Snap! Easy Snapshot Testing for Zig
* [cryptocode/marble](https://github.com/cryptocode/marble) - A metamorphic testing library for Zig
* [CogitatorTech/minish](https://github.com/CogitatorTech/minish) - A property-based testing framework for Zig ⚡

## Utilities

### Command Line Tools

* [Loongphy/codex-auth](https://github.com/Loongphy/codex-auth) - A CLI tool to switch and manage Codex accounts
* [Hejsil/zig-clap](https://github.com/Hejsil/zig-clap) - Command line argument parsing library
* [so-dang-cool/dt](https://github.com/so-dang-cool/dt) - dt - duct tape for your unix pipes
* [sam701/zig-cli](https://github.com/sam701/zig-cli) - A simple package for building command line apps in Zig
* [xcaeser/zli](https://github.com/xcaeser/zli) - 📟 Build ergonomic, high-performance command-line tools (CLI) with zig.
* [ikskuh/zig-args](https://github.com/ikskuh/zig-args) - Simple-to-use argument parser with struct-based config
* [Arnau478/hevi](https://github.com/Arnau478/hevi) - ⚠️ MIGRATED TO CODEBERG ⚠️ *(archived)*
* [prajwalch/yazap](https://github.com/prajwalch/yazap) - 🔧 The ultimate Zig library for seamless command line argument parsing.
* [00JCIV00/cova](https://github.com/00JCIV00/cova) - Commands, Options, Values, Arguments. A simple yet robust cross-platform command line argument parsing library for Zig.
* [mattrobenolt/appify](https://github.com/mattrobenolt/appify) - Turn TUI apps into real macOS applications
* [rockorager/zigdoc](https://github.com/rockorager/zigdoc) - A command-line tool to view documentation for Zig standard library symbols
* [BarutSRB/GhosttyFetch](https://github.com/BarutSRB/GhosttyFetch) - Animated system info tool for Ghostty terminal
* [jiacai2050/zigcli](https://github.com/jiacai2050/zigcli) - A toolkit for building command lines programs in Zig.
* [pbui-project/pbui-main](https://github.com/pbui-project/pbui-main) - The main repository for the PBUI project
* [neurocyte/zat](https://github.com/neurocyte/zat) - zat is a syntax highlighting cat like utility using tree-sitter and with support for vscode themes
* [mikkelam/fast-cli](https://github.com/mikkelam/fast-cli) - Command line version of fast.com in ~1.2 MB
* [joegm/flags](https://github.com/joegm/flags) - An effortless command-line argument parser for Zig.
* [ratfactor/zigish](https://github.com/ratfactor/zigish) - A toy Unix shell written in Zig *(archived)*
* [leecannon/zig-coreutils](https://github.com/leecannon/zig-coreutils) - A single executable implementation of various coreutils.
* [here-Leslie-Lau/zlist](https://github.com/here-Leslie-Lau/zlist) - A modern ls alternative written in Zig.
* [CogitatorTech/chilli](https://github.com/CogitatorTech/chilli) - A microframework for creating command-line applications in Zig
* [jiacai2050/simargs](https://github.com/jiacai2050/simargs) - A simple, opinionated, struct-based argument parser in Zig. *(archived)*
* [rockorager/lsr](https://github.com/rockorager/lsr) - ls but with io_uring
* [judofyr/parg](https://github.com/judofyr/parg) - Lightweight argument parser for Zig
* [utox39/zigfetch](https://github.com/utox39/zigfetch) - Zigfetch is a minimal neofetch/fastfetch like system information tool
* [yamafaktory/whetuu](https://github.com/yamafaktory/whetuu) - An opinionated, zero-config status line and history picker for fish, bash and zsh, written in Zig
* [BanchouBoo/accord](https://github.com/BanchouBoo/accord) - A simple argument parser for Zig
* [deevus/neutils](https://github.com/deevus/neutils) - Modern CLI utilities for everyday developer tasks, written in Zig
* [rito1998/zwol](https://github.com/rito1998/zwol) - Wake-on-LAN CLI written in Zig.
* [kioz-wang/zargs](https://github.com/kioz-wang/zargs) - Comptime Argparse for Zig! Let's start to build your command line!
* [tensorush/liza](https://github.com/tensorush/liza) - Zig codebase initializer.

### Logging and Configuration

* [karlseguin/log.zig](https://github.com/karlseguin/log.zig) - A structured logger for Zig
* [chrischtel/nexlog](https://github.com/chrischtel/nexlog) - A modern, feature-rich logging library for Zig with thread-safety, file rotation, and colorized output. High-performance logging made easy.
* [muhammad-fiaz/logly.zig](https://github.com/muhammad-fiaz/logly.zig) - A production-ready, high-performance structured logging library for Zig with a clean, simplified API.
* [candrewlee14/zlog](https://github.com/candrewlee14/zlog) - A zero-allocation log library for Zig *(archived)*
* [dying-will-bullet/dotenv](https://github.com/dying-will-bullet/dotenv) - Loads environment variables from .env for Zig projects.

### Text Processing

* [Lulzx/zpdf](https://github.com/Lulzx/zpdf) - Zero-copy PDF text extraction library written in Zig. High-performance, memory-mapped parsing with SIMD acceleration.
* [Hejsil/mecha](https://github.com/Hejsil/mecha) - A parser combinator library for Zig
* [JakubSzark/zig-string](https://github.com/JakubSzark/zig-string) - A String Library made for Zig
* [unjs/md4x](https://github.com/unjs/md4x) - 📄 Fast and small markdown parser and renderer
* [tiehuis/zig-regex](https://github.com/tiehuis/zig-regex) - A regex implementation for the zig programming language
* [jetzig-framework/zmpl](https://github.com/jetzig-framework/zmpl) - Zmpl is a templating language written in Zig
* [batiati/mustache-zig](https://github.com/batiati/mustache-zig) - Logic-less templates for Zig *(archived)*
* [kivikakk/koino](https://github.com/kivikakk/koino) - CommonMark + GFM compatible Markdown parser and renderer
* [alexnask/ctregex.zig](https://github.com/alexnask/ctregex.zig) - Compile time regular expressions in zig
* [ije/md4w](https://github.com/ije/md4w) - A Markdown renderer written in Zig & C, compiled to WebAssymbly.
* [mnemnion/mvzr](https://github.com/mnemnion/mvzr) - Minimum Viable Zig Regex
* [JacobCrabill/zigdown](https://github.com/JacobCrabill/zigdown) - Markdown toolset in Zig ⚡
* [jacobsandlund/uucode](https://github.com/jacobsandlund/uucode) - uucode - fast unicode library in zig
* [timfayz/pretty](https://github.com/timfayz/pretty) - Pretty printer for arbitrary data structures in Zig.
* [zigster64/zts](https://github.com/zigster64/zts) - Zig Templates made Simple
* [hexops-graveyard/zorex](https://github.com/hexops-graveyard/zorex) - Zorex: the omnipotent regex engine
* [gremlin-labs/vibe-jinja](https://github.com/gremlin-labs/vibe-jinja) - Pure Zig implementation of Jinja2 templating. Bytecode compilation, 40+ filters, template inheritance, macros, autoescaping, and sandboxing. Built for HuggingFace ML pipelines and high-performance applications.
* [imggion/html2realpdf](https://github.com/imggion/html2realpdf) - Generate a real PDF, not a screenshot.
* [nektro/zig-pek](https://github.com/nektro/zig-pek) - A comptime HTML preprocessor with a builtin template engine for Zig.
* [judofyr/lil-scan](https://github.com/judofyr/lil-scan) - Lil Scan helps you hand-write parsers in Zig
* [kristoff-it/supermd](https://github.com/kristoff-it/supermd) - SuperMD is an extension of Markdown used by https://zine-ssg.io
* [ikskuh/TextEditor](https://github.com/ikskuh/TextEditor) - A backbone for text editors. No rendering, no input, but everything else.
* [jetzig-framework/zmd](https://github.com/jetzig-framework/zmd) - Zmd is a Markdown library written in Zig
* [Vexu/zuri](https://github.com/Vexu/zuri) - URI parser for Zig *(archived)*
* [karlseguin/ztl](https://github.com/karlseguin/ztl) - Templating Language for Zig
* [ziglibs/treez](https://github.com/ziglibs/treez) - tree-sitter bindings for Zig
* [dokwork/parcom](https://github.com/dokwork/parcom) - Parser combinators for Zig, ready to parse on-the-fly. Consume input, not memory.
* [kivikakk/libpcre.zig](https://github.com/kivikakk/libpcre.zig) - Zig bindings to libpcre
* [rockorager/zzdoc](https://github.com/rockorager/zzdoc) - an scdoc compatible manpage compiler for build.zig
* [ikskuh/ZTT](https://github.com/ikskuh/ZTT) - Precompiled Zig text template engine
* [karlseguin/buffer.zig](https://github.com/karlseguin/buffer.zig) - A poolable string builder (aka string buffer) for Zig
* [ziglibs/diffz](https://github.com/ziglibs/diffz) - Implementation of go-diff's diffmatchpatch in Zig
* [quangdn42/regex.zig](https://github.com/quangdn42/regex.zig) - Zig regular expression engine, with guaranteed linear time matching.
* [zig-utils/zig-regex](https://github.com/zig-utils/zig-regex) - A modern, performant regular expression library for Zig.

### Files and Operating System

* [marlersoft/zigwin32](https://github.com/marlersoft/zigwin32) - Zig bindings for Win32 generated by https://github.com/marlersoft/zigwin32gen
* [mitchellh/zig-objc](https://github.com/mitchellh/zig-objc) - Objective-C runtime bindings for Zig (Zig calling ObjC).
* [ziglibs/known-folders](https://github.com/ziglibs/known-folders) - Provides access to well-known folders across several operating systems
* [dmtrKovalenko/zlob](https://github.com/dmtrKovalenko/zlob) - *Very* fast recursive file walking and globbing library for Zig, C, and Rust. With gitignore support. 100% POSIX compatible
* [marlersoft/zigwin32gen](https://github.com/marlersoft/zigwin32gen) - Generates Complete Zig bindings for Win32. See https://github.com/marlersoft/zigwin32 for the bindings themselves.
* [Jarred-Sumner/poof](https://github.com/Jarred-Sumner/poof) - Ephemeral filesystem isolation via Linux overlayfs (experimental)
* [kubkon/ZigKit](https://github.com/kubkon/ZigKit) - Zig bindings for low-level macOS frameworks
* [txthinking/z](https://github.com/txthinking/z) - z - process manager
* [TibboddiT/dyn-loader](https://github.com/TibboddiT/dyn-loader) - dlopen for zig, from static executables and without libc
* [marlersoft/win32jsongen](https://github.com/marlersoft/win32jsongen) - Generates the JSON Win32 metadata files for: https://github.com/marlersoft/win32json
* [GoNZooo/zig-win32](https://github.com/GoNZooo/zig-win32) - Bindings for win32, with and without WIN32_LEAN_AND_MEAN *(archived)*

### Automation and Scripting

* [jstrieb/github-stats](https://github.com/jstrieb/github-stats) - Better GitHub statistics images for your profile, with stats from private repos too
* [jackielii/skhd.zig](https://github.com/jackielii/skhd.zig) - Simple Hotkey Daemon for macOS, ported from skhd by asmvik
* [Parth/dotfiles](https://github.com/Parth/dotfiles)
* [remorses/usecomputer](https://github.com/remorses/usecomputer) - Fast computer automation CLI for AI agents. Control any desktop with screenshots, clicks, typing, scrolling, and more.
* [alleneubank/claude-code](https://github.com/alleneubank/claude-code) - Comprehensive configuration system for Claude Code *(archived)*
* [BanchouBoo/lucky](https://github.com/BanchouBoo/lucky) - Lua-configured input daemon for X
* [discord-zig/discord.zig](https://github.com/discord-zig/discord.zig) - Mirror of Discord.zig, submit PRs and issues at https://git.yuzucchii.xyz/yuzucchii/discord.zig *(archived)*
* [Sobeston/zigcord](https://github.com/Sobeston/zigcord) - A discord library in zig. *(archived)*
* [whuanle/EasyTouch](https://github.com/whuanle/EasyTouch) - 一个跨平台的系统自动化操作工具，支持鼠标、键盘、屏幕、窗口、系统资源等多种操作。支持 CLI 和 MCP 两种使用方式。
* [Nyarum/zigtgshka](https://github.com/Nyarum/zigtgshka) - 🤖 Memory-safe, high-performance Telegram Bot API library for Zig with zero-cost abstractions and comprehensive examples

### General Purpose Libraries

* [karlseguin/zul](https://github.com/karlseguin/zul) - zig utility library
* [getz3/polystate](https://github.com/getz3/polystate) - Build type-safe finite state machines with higher-order states.
* [marler8997/ziglibc](https://github.com/marler8997/ziglibc)
* [Super-ZIG/io](https://github.com/Super-ZIG/io) - Easy input/output in ZIG. *(archived)*
* [cryptocode/zigfsm](https://github.com/cryptocode/zigfsm) - A finite state machine library for Zig
* [nilslice/zig-interface](https://github.com/nilslice/zig-interface) - Comptime interface generation modeled after vtable design found in the stdlib.
* [alexnask/interface.zig](https://github.com/alexnask/interface.zig) - Dynamic dispatch for zig made easy
* [yamafaktory/hypergraphz](https://github.com/yamafaktory/hypergraphz) - HypergraphZ – directed hypergraph library in Zig with Python bindings
* [mitchellh/zig-graph](https://github.com/mitchellh/zig-graph) - Directed graph data structure for Zig
* [andrewCodeDev/Fluent](https://github.com/andrewCodeDev/Fluent) - Fluent interface for REGEX, iteration, and algorithm chaining.
* [deckarep/ziglang-set](https://github.com/deckarep/ziglang-set) - A generic and general purpose Set implementation for the Zig language
* [williamw520/toposort](https://github.com/williamw520/toposort) - Topological sort library in Zig
* [cryptocode/bithacks](https://github.com/cryptocode/bithacks) - Zig bithacks
* [Aandreba/zigrc](https://github.com/Aandreba/zigrc) - Zig reference-counted pointers inspired by Rust's Rc and Arc
* [axiomhq/zig-hyperloglog](https://github.com/axiomhq/zig-hyperloglog) - Zig library for HyperLogLog estimation
* [Hejsil/ziter](https://github.com/Hejsil/ziter) - The missing iterators for Zig
* [kristoff-it/zig-cuckoofilter](https://github.com/kristoff-it/zig-cuckoofilter) - Production-ready Cuckoo Filters for any C ABI compatible target.
* [Srekel/zig-sparse-set](https://github.com/Srekel/zig-sparse-set) - Sparse sets for zig, supporting both SOA and AOS style
* [alichraghi/zort](https://github.com/alichraghi/zort) - Sorting algorithms in zig
* [flyfish30/zig-cats](https://github.com/flyfish30/zig-cats) - A category theory and functional programing library for Zig language
* [judofyr/zini](https://github.com/judofyr/zini) - Succinct data structures for Zig
* [nektro/zig-extras](https://github.com/nektro/zig-extras) - An assortment of random utility functions that aren't in std and don't need to be their own pacakge.
* [mov-rax/zig-validate](https://github.com/mov-rax/zig-validate) - A type validation library for writing a zero-cost, declarative, understandable, generic code in zig.
* [HolyGrailSortProject/Rewritten-Grailsort](https://github.com/HolyGrailSortProject/Rewritten-Grailsort) - A diverse array of heavily refactored versions of Andrey Astrelin's GrailSort.h, aiming to be as readable and intuitive as possible
* [permutationlock/zimpl](https://github.com/permutationlock/zimpl) - Simple comptime generic interfaces for Zig
* [asheshvidyut/zds](https://github.com/asheshvidyut/zds) - A collection of high-performance data structures for Zig.
* [archaistvolts/art.zig](https://github.com/archaistvolts/art.zig) - An Adaptive Radix Tree ported from c *(archived)*
* [chung-leong/zigft](https://github.com/chung-leong/zigft) - Zig function transform library
* [BraedonWooding/Lazy-Zig](https://github.com/BraedonWooding/Lazy-Zig) - Linq in Zig
* [thi-ng/zig-thing](https://github.com/thi-ng/zig-thing) - Small collection of data types/structures, utilities & open-learning with Zig
* [r4gus/uuid-zig](https://github.com/r4gus/uuid-zig) - This is a Codeberg Mirror. Work is continued on codeberg: https://codeberg.org/r4gus/uuid-zig
* [ikskuh/any-pointer](https://github.com/ikskuh/any-pointer) - A type erasure library for Zig that is meant to be eventually upstreamed to std
* [CogitatorTech/ordered](https://github.com/CogitatorTech/ordered) - A sorted collection library (sorted sets and sorted maps) for Zig
* [MahdiGMK/zaman](https://github.com/MahdiGMK/zaman) - Comptime lifetime annotations for Zig!
* [sphaerophoria/sphtud](https://github.com/sphaerophoria/sphtud) - My zig standard library
* [OrlovEvgeny/lo.zig](https://github.com/OrlovEvgeny/lo.zig) - A Lodash-style Zig library
* [karlseguin/validate.zig](https://github.com/karlseguin/validate.zig) - A validation framework for Zig
* [zhuyadong/zoop](https://github.com/zhuyadong/zoop) - A Zig OOP solution
* [ziglibs/funzig](https://github.com/ziglibs/funzig) - Fun functional functionality for Zig!
* [andrewrk/mime](https://github.com/andrewrk/mime) - zig package for mapping extensions to mime types
* [SasLuca/zig-nanoid](https://github.com/SasLuca/zig-nanoid) - A tiny, secure, URL-friendly, unique string ID generator. Now available in pure Zig.
* [Vexu/comptime_hash_map](https://github.com/Vexu/comptime_hash_map) - A statically initiated HashMap
* [tristanpemble/resizable-struct](https://github.com/tristanpemble/resizable-struct) - Runtime resizable struct types in Zig
* [yrashk/zig-rcsp](https://github.com/yrashk/zig-rcsp) - Reference-counted Shared Pointer for Zig
* [rdunnington/zig-stable-array](https://github.com/rdunnington/zig-stable-array) - Address-stable array with a max size that allocates directly from virtual memory.

## Systems and Hardware

### Operating Systems and Kernels

* [ZystemOS/pluto](https://github.com/ZystemOS/pluto) - An x86 kernel written in Zig
* [mewz-project/mewz](https://github.com/mewz-project/mewz) - A unikernel designed specifically for running Wasm applications and compatible with WASI
* [AndreaOrru/zen](https://github.com/AndreaOrru/zen) - Experimental operating system written in Zig
* [jzck/kernel-zig](https://github.com/jzck/kernel-zig) - :floppy_disk: hobby x86 kernel zig
* [andrewrk/HellOS](https://github.com/andrewrk/HellOS) - "hello world" x86 kernel example
* [tw4452852/zbpf](https://github.com/tw4452852/zbpf) - Writing eBPF in Zig
* [andrewrk/clashos](https://github.com/andrewrk/clashos) - multiplayer arcade game for bare metal Raspberry Pi 3 B+
* [lopespm/zig-minimal-kernel-x86](https://github.com/lopespm/zig-minimal-kernel-x86) - Minimal x86 Kernel - built in Zig
* [butter-dot-dev/bVisor](https://github.com/butter-dot-dev/bVisor) - Embedded application kernel, inspired by gVisor
* [popovicu/zig-time-sharing-kernel](https://github.com/popovicu/zig-time-sharing-kernel) - Minimal implementation of a time-sharing kernel on RISC-V, implemented in Zig, on top of OpenSBI
* [kristoff-it/kristos](https://github.com/kristoff-it/kristos) - A minimal OS implemented following "Operating system in 1000 lines of code"
* [diodesign/diosix](https://github.com/diodesign/diosix) - A lightweight, robust, multiprocessor bare-metal hypervisor written in Zig for RISC-V
* [botirkhaltaev/pico-os](https://github.com/botirkhaltaev/pico-os) - A minimal RISC-V 32-bit OS written in Zig.
* [FlorenceOS/Florence](https://github.com/FlorenceOS/Florence) - The Renaissance of Operating Systems
* [TalonFloof/zorroOS](https://github.com/TalonFloof/zorroOS) - A hobby operating system written in Zig & C, a modification of some UNIX ideas.
* [b0bleet/zvisor](https://github.com/b0bleet/zvisor) - Minimalistic hypervisor built on KVM, coded with Zig.
* [Ashet-Technologies/Ashet-OS](https://github.com/Ashet-Technologies/Ashet-OS) - Retro-inspired operating system designed to be learnable and hackable by its users
* [CascadeOS/CascadeOS](https://github.com/CascadeOS/CascadeOS) - General purpose operating system targeting standard desktops and laptops.
* [bagggage/bamos](https://github.com/bagggage/bamos) - An open-source operating system with its own kernel
* [lupyuen/pinephone-nuttx](https://github.com/lupyuen/pinephone-nuttx) - Apache NuttX RTOS for PinePhone
* [jayschwa/dos.zig](https://github.com/jayschwa/dos.zig) - Create DOS programs with Zig
* [MinecAnton209/NovumOS](https://github.com/MinecAnton209/NovumOS)
* [smallkirby/ymir](https://github.com/smallkirby/ymir) - Ymir: The Type-1 Hypervisor.
* [davidgmbb/birth](https://github.com/davidgmbb/birth) - A better operating system *(archived)*
* [zig-osdev/riscv-barebones](https://github.com/zig-osdev/riscv-barebones) - Barebones RISC-V kernel template for Zig
* [rafaelbreno/zig-os](https://github.com/rafaelbreno/zig-os) - A simple OS written in Zig following Philipp Oppermann's posts "Writing an OS in Rust"
* [sjdh02/trOS](https://github.com/sjdh02/trOS) - tiny aarch64 baremetal OS thingy
* [iguessthislldo/georgios](https://github.com/iguessthislldo/georgios) - Hobby Operating System
* [F4LCn/falcon-os](https://github.com/F4LCn/falcon-os) - toy operating system kernel written from scratch as a learning tool
* [jmbaur/mixos](https://github.com/jmbaur/mixos) - MixOS, a Minimal Nix OS
* [epizzella/Echo-OS](https://github.com/epizzella/Echo-OS) - A Real Time Operating System written in Zig
* [nrdmn/uefi-paint](https://github.com/nrdmn/uefi-paint) - UEFI-bootable touch paint app
* [FlorenceOS/Sabaton](https://github.com/FlorenceOS/Sabaton) - aarch64 stivale2 bootloader
* [stakach/uefi-bootstrap](https://github.com/stakach/uefi-bootstrap) - experiments with bootstrapping a kernel with UEFI
* [matgla/yasos.zig](https://github.com/matgla/yasos.zig) - This repository contains my new OS implementation written in zig language
* [48cf/zigux](https://github.com/48cf/zigux) - Zigux is an attempt to write a UNIX-like kernel in Zig
* [48cf/limine-zig](https://github.com/48cf/limine-zig) - A Zig library for handling Limine boot protocol structures.
* [kora-org/ydin](https://github.com/kora-org/ydin) - A very extendable and versatile hybrid kernel.
* [michaelkremenetsky/linuxemu](https://github.com/michaelkremenetsky/linuxemu) - Linux compatible kernel written in Zig for running linux binaries in the browser
* [DanB91/Hello-UEFI-Zig](https://github.com/DanB91/Hello-UEFI-Zig) - Super bare-minimum code needed to get started writing an OS or UEFI bare metal application

### Embedded and Firmware

* [ZigEmbeddedGroup/microzig](https://github.com/ZigEmbeddedGroup/microzig) - MicroZig is a toolbox for building embedded applications in Zig.
* [kassane/zig-esp-idf-sample](https://github.com/kassane/zig-esp-idf-sample) - Run Zig on esp-idf (Xtensa/RISC-V)
* [semickolon/kirei](https://github.com/semickolon/kirei) - 🌸 The prettiest keyboard software
* [FireFox317/avr-arduino-zig](https://github.com/FireFox317/avr-arduino-zig) - Arduino using Zig!
* [zPSP-Dev/Zig-PSP](https://github.com/zPSP-Dev/Zig-PSP) - A project to bring the Zig Programming Language to the Sony PlayStation Portable!
* [markfirmware/zig-bare-metal-raspberry-pi](https://github.com/markfirmware/zig-bare-metal-raspberry-pi) - Bare metal raspberry pi program written in zig
* [ZigEmbeddedGroup/serial](https://github.com/ZigEmbeddedGroup/serial) - Serial port configuration library for Zig
* [BANANASJIM/padctl](https://github.com/BANANASJIM/padctl) - HID gamepad daemon with declarative TOML device config
* [ZigEmbeddedGroup/raspberrypi-rp2040](https://github.com/ZigEmbeddedGroup/raspberrypi-rp2040) - MicroZig Hardware Support Package for Raspberry Pi RP2040 *(archived)*
* [ZigEmbeddedGroup/regz](https://github.com/ZigEmbeddedGroup/regz) - Generate zig code from ATDF or SVD files for microcontrollers. *(archived)*
* [leath-dub/droidux](https://github.com/leath-dub/droidux) - Create user space drivers for your android devices (digitizer, buttons, etc)
* [gpanders/esp32-zig-starter](https://github.com/gpanders/esp32-zig-starter) - Starter project for using Zig with ESP IDF
* [jeffective/gatorcat](https://github.com/jeffective/gatorcat) - An EtherCAT MainDevice for Zig *(archived)*
* [ZigEmbeddedGroup/foundation-libc](https://github.com/ZigEmbeddedGroup/foundation-libc) - A libc implementation written in Zig that is designed to be used with freestanding targets. *(archived)*
* [lupyuen/zig-bl602-nuttx](https://github.com/lupyuen/zig-bl602-nuttx) - Zig on RISC-V BL602 with Apache NuttX RTOS and LoRaWAN
* [nodecum/zig-zephyr](https://github.com/nodecum/zig-zephyr) - Case study of interweaving zephyr and zig
* [lynaghk/svd2zig](https://github.com/lynaghk/svd2zig) - Generate Zig API from SVD register definitions.
* [markfirmware/zig-bare-metal-microbit](https://github.com/markfirmware/zig-bare-metal-microbit) - Bare metal microbit program written in zig
* [ZigEmbeddedGroup/espressif-esp](https://github.com/ZigEmbeddedGroup/espressif-esp) - [WIP] ESP32 microzig package *(archived)*
* [nmeum/zig-riscv-embedded](https://github.com/nmeum/zig-riscv-embedded) - Experimental Zig-based CoAP node for the HiFive1 RISC-V board
* [justinbalexander/svd2zig](https://github.com/justinbalexander/svd2zig) - Convert System View Description (svd) files to Zig headers for baremetal development
* [puppy-rtos/stm32-zboot](https://github.com/puppy-rtos/stm32-zboot) - Universal stm32 boot written using zig

## Science and Math

### Mathematics

* [kooparse/zalgebra](https://github.com/kooparse/zalgebra) - Linear algebra library for games and real-time graphics.
* [ziglibs/zlm](https://github.com/ziglibs/zlm) - Zig linear mathemathics
* [zig-gamedev/zmath](https://github.com/zig-gamedev/zmath) - SIMD math library for Zig game developers
* [griush/zm](https://github.com/griush/zm) - MOVED TO Codeberg. NOT mirrored. zm - Zig math library
* [ymndoseijin/zilliam](https://github.com/ymndoseijin/zilliam) - A Geometric Algebra library for Zig
* [ziglibs/zigfp](https://github.com/ziglibs/zigfp) - Basic fixed point implementation in Zig.
* [srmadrid/zsl](https://github.com/srmadrid/zsl) - Zig scientific library
* [Laremere/alg](https://github.com/Laremere/alg) - Algebra for Zig

### Scientific Computing

* [ATTron/astroz](https://github.com/ATTron/astroz) - Astrodynamics and Spacecraft Toolkit. Features fast orbit prop, celestial precession, CCSDS parsing, RF parsing, fits image parsing, and more!
* [zerotech-studio/zack](https://github.com/zerotech-studio/zack) - Backtesting engine in Zig
* [zig-robotics/zigros](https://github.com/zig-robotics/zigros) - Zig build for the entirel rcl and rclcpp stack
* [vsergeev/zigradio](https://github.com/vsergeev/zigradio) - A lightweight software-defined radio framework built with Zig
* [ckrowland/markets](https://github.com/ckrowland/markets) - Visually simulate basic markets.

## Other

* [lightpanda-io/browser](https://github.com/lightpanda-io/browser) - Lightpanda: the headless browser designed for AI and automation
* [tonybanters/oxwm](https://github.com/tonybanters/oxwm)
* [spiraldb/ziggy-pydust](https://github.com/spiraldb/ziggy-pydust) - A toolkit for building Python extensions in Zig.
* [w1nt3r-eth/evm-from-scratch](https://github.com/w1nt3r-eth/evm-from-scratch) - Super secret 100% practical EVM course. Please do not share
* [natecraddock/zf](https://github.com/natecraddock/zf) - a commandline fuzzy finder and zig module designed for filtering filepaths
* [jamii/dida](https://github.com/jamii/dida) - Differential dataflow for mere mortals *(archived)*
* [antflydb/antfly](https://github.com/antflydb/antfly)
* [chung-leong/zigar](https://github.com/chung-leong/zigar) - Toolkit enabling the use of Zig code in JavaScript and PHP projects
* [justrach/kuri](https://github.com/justrach/kuri) - Browser automation, web crawling, and iOS + Android device control for AI agents. Zig-native, token-efficient CDP snapshots, HAR recording, native adb wire-protocol client, and a standalone fetcher.
* [Jarred-Sumner/hop](https://github.com/Jarred-Sumner/hop)
* [paralogical/rarest-move-in-chess](https://github.com/paralogical/rarest-move-in-chess) - Analyze compressed chess pgn files to determine the rarest move
* [hdresearch/ziggit](https://github.com/hdresearch/ziggit)
* [rockorager/zeit](https://github.com/rockorager/zeit) - a date and time library written in zig. Timezone, DST, and leap second aware
* [Srekel/tides-of-revival](https://github.com/Srekel/tides-of-revival)
* [jamii/jams](https://github.com/jamii/jams)
* [ohah/hwpjs](https://github.com/ohah/hwpjs) - hwpjs
* [ryoppippi/zigcv](https://github.com/ryoppippi/zigcv) - zig bindings for OpenCV4
* [jamii/zest](https://github.com/jamii/zest)
* [boldsoftware/exe.dev](https://github.com/boldsoftware/exe.dev) - just use ssh
* [marler8997/zigx](https://github.com/marler8997/zigx)
* [external-mirrors/phoenix](https://github.com/external-mirrors/phoenix)
* [pig-dot-dev/piglet](https://github.com/pig-dot-dev/piglet)
* [NishantJoshi00/flipper-template](https://github.com/NishantJoshi00/flipper-template)
* [beamivalice/sushi](https://github.com/beamivalice/sushi) - Sushi engine runs very high quality quant model in Apple Silicon, using hybrid affine/exl3 with special expert tuning techniques.
* [Noisemux/zeptun](https://github.com/Noisemux/zeptun) - High-performance tun2socks engine in Zig with TCP, UDP, ICMP, SOCKS5, io_uring, and C API.
* [frmdstryr/zig-datetime](https://github.com/frmdstryr/zig-datetime) - A date and time module for Zig
* [patrickgwsmith/qip](https://github.com/patrickgwsmith/qip) - Quickly render anything, everywhere
* [sphaerophoria/sphmap](https://github.com/sphaerophoria/sphmap) - It's a sphmap
* [pyozig/PyOZ](https://github.com/pyozig/PyOZ) - PyOZ - Zig's power meets Python's simplicity. Build blazing-fast extensions with zero boilerplate and zero Python C API headaches.
* [yukmakoto/zed2api](https://github.com/yukmakoto/zed2api)
* [acoustid/acoustid-index](https://github.com/acoustid/acoustid-index) - Minimalistic search engine searching in audio fingerprints from Chromaprint
* [Thomvanoorschot/zigma](https://github.com/Thomvanoorschot/zigma) - Zigma is an algorithmic trading framework built with the Zig programming language, leveraging an actor-based concurrency model. It aims to provide an efficient, low-latency system for algorithmic trading through components handling market data, strategy execution, order management, risk, and data persistence.
* [drcode/zek](https://github.com/drcode/zek)
* [furunkel/zig.rb](https://github.com/furunkel/zig.rb) - Write Ruby extensions in Zig!
* [suirad/zig-header-gen](https://github.com/suirad/zig-header-gen) - Automatically generate headers/bindings for other languages from Zig code
* [comrade-T/handmade-studio](https://github.com/comrade-T/handmade-studio)
* [katafrakt/zig-ruby](https://github.com/katafrakt/zig-ruby)
* [nektro/zig-time](https://github.com/nektro/zig-time) - A date and time parsing and formatting library for Zig.
* [and-rs/nvim](https://github.com/and-rs/nvim) - im fast
* [ThePrimeagen/BunSpreader](https://github.com/ThePrimeagen/BunSpreader) - We spread the buns
* [cztomsik/napigen](https://github.com/cztomsik/napigen) - Automatic N-API (server-side javascript) bindings for your Zig project.
* [kotsutsumi/zylix](https://github.com/kotsutsumi/zylix)
* [lukewilliamboswell/roc-ray](https://github.com/lukewilliamboswell/roc-ray) - Roc graphics and simple games platform
* [NicoElbers/nixPatch-nvim](https://github.com/NicoElbers/nixPatch-nvim) - This repository has been moved to codeberg *(archived)*
* [rauchg/rst](https://github.com/rauchg/rst)
* [xop01/project-progress-mcp](https://github.com/xop01/project-progress-mcp) - make your ai track the progress of your project without drifting off
* [The-Memory-Managers/cpu-vs-ai](https://github.com/The-Memory-Managers/cpu-vs-ai) - Boot.dev hackathon 2025
* [rarnu/ExGhostty](https://github.com/rarnu/ExGhostty)
* [kunkka19xx/lgtm](https://github.com/kunkka19xx/lgtm) - Read what your agent wrote before you say LGTM. A fast TUI in Zig for reviewing code with vim motions.
* [Remy2701/zigplotlib](https://github.com/Remy2701/zigplotlib) - A simple library for plotting graphs in Zig
* [kristoff-it/awebo](https://github.com/kristoff-it/awebo) - Mirror of https://codeberg.org/kristoff/awebo
* [DockYard/zap](https://github.com/DockYard/zap)
* [iStark/PS5PCEM](https://github.com/iStark/PS5PCEM) - PS5 PC Emulator
* [okcontract/oksolc](https://github.com/okcontract/oksolc) - A Solidity compiler written in Zig
* [BUNotesAI/ghostty-dev](https://github.com/BUNotesAI/ghostty-dev)
* [aikoschurmann/zog](https://github.com/aikoschurmann/zog) - ⚡ A blisteringly fast, zero-allocation JSONL search engine in Zig. Query and aggregate massive datasets at 4.0 GB/s using SIMD-accelerated "Blind Scanning." Up to 50x faster than jq.
* [coolbho3k/emibios](https://github.com/coolbho3k/emibios) - accuracy-focused GBA BIOS replacement
* [PikaOS-Linux/falcond](https://github.com/PikaOS-Linux/falcond)
* [lithdew/hyperia](https://github.com/lithdew/hyperia)
* [immanuwell/ringzero](https://github.com/immanuwell/ringzero) - 9M+ packets/sec L4 load balancer, XDP learning project
* [Yueqing-Chen/complexweeper-A-minesweeper-game](https://github.com/Yueqing-Chen/complexweeper-A-minesweeper-game) - 复扫雷，顾名思义
* [redwoodjs/machinen](https://github.com/redwoodjs/machinen) - Machinen
* [ringtailsoftware/obfusgator](https://github.com/ringtailsoftware/obfusgator) - obfusgator.zig
* [xirf/macula](https://github.com/xirf/macula) - Lightweight OCR error detection and correction engine built in Zig *(archived)*
* [Yupcha/memXT](https://github.com/Yupcha/memXT) - MemXT is a Local long-term memory for Claude Code & coding agents. 100% local
* [knots-ui/knots](https://github.com/knots-ui/knots) - High performance cross-platform immediate-mode GUI rendering library.
* [Fusion-Engine-Labs/fusion-runtime](https://github.com/Fusion-Engine-Labs/fusion-runtime)
* [RohanVashisht1234/donut](https://github.com/RohanVashisht1234/donut)
* [and-rs/flash.tmux](https://github.com/and-rs/flash.tmux) - Navigate terminal panes by jumping
* [tsoding/pogfish](https://github.com/tsoding/pogfish) - pogfish
* [im-ng/zero](https://github.com/im-ng/zero) - Simple and opinionated web framework written in zig
* [raptodb/rapto](https://github.com/raptodb/rapto) - For engineers seeking an in-memory key-value database, Rapto provides predictable performance, cache-aware design, and low memory usage through an event-driven runtime.
* [ivanleomk/gil](https://github.com/ivanleomk/gil)
* [mactsouk/zigSP](https://github.com/mactsouk/zigSP) - Systems Programming with Zig
* [Seafoam-Labs/Aqueous](https://github.com/Seafoam-Labs/Aqueous) - A dynamic tiling Wayland compositor and window manager with compositor-side motion and Vulkan effects, in one Zig process.
* [sphaerophoria/ball-machine](https://github.com/sphaerophoria/ball-machine)
* [anomalyco/haunt](https://github.com/anomalyco/haunt)
* [pixel-clover/sandopolis](https://github.com/pixel-clover/sandopolis) - A portable multi-system Sega emulator for Genesis, Sega CD, Master System, Game Gear, and SG-1000 🎮
* [rockorager/rush](https://github.com/rockorager/rush) - rockorager's user-friendly shell
* [zoeesilcock/flint](https://github.com/zoeesilcock/flint) - Building blocks for the game engine your game actually needs.
* [bobrwm/bobrwm](https://github.com/bobrwm/bobrwm) - Tiling WM for macOS
* [cwt/fts5-icu-tokenizer](https://github.com/cwt/fts5-icu-tokenizer) - FTS5 ICU Tokenizer for SQLite
* [justinGrosvenor/swerver](https://github.com/justinGrosvenor/swerver) - A zero-copy, zero-allocation HTTP server written in pure Zig.
* [mrusme/zpoweralertd](https://github.com/mrusme/zpoweralertd) - Zig rewrite and drop-in replacement of poweralertd (https://tty.fail/mrus/zpoweralertd)
* [c-shinkle/anyline](https://github.com/c-shinkle/anyline) - *(archived)*
