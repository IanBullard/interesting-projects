# Ian's Interesting Github Projects

This is a collections of projects I find interesting.  That's literally the only requirement to get on this list, don't read anything into it other than that. Kinda a public bookmark list.

[//]: # (This may be the most platform independent comment)

## Other GitHub Lists

* [Awesome Modern C++](https://github.com/rigtorp/awesome-modern-cpp/blob/master/README.md) - A collection of resources on modern C++.
* [C++ Links](https://github.com/MattPD/cpplinks) : A categorized list of C++ resources.
* [r-lyeh](https://github.com/r-lyeh) : Has cool game-oriented repositories

## Documentation

* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Changelog](https://keepachangelog.com/en/1.0.0/)

## C++ Libraries

* Hash functions
  * [murmur3](https://github.com/PeterScott/murmur3) : Murmur3 is a non-cryptographic hash, designed to be fast and excellent-quality for making things like hash tables or bloom filters.
  * [xxHash](https://github.com/Cyan4973/xxHash) : xxHash is an Extremely fast Hash algorithm, running at RAM speed limits.
  * [FNV](https://en.wikipedia.org/wiki/Fowler%E2%80%93Noll%E2%80%93Vo_hash_function) : Fowler–Noll–Vo Hash
  * [SplitMix](https://xorshift.di.unimi.it/splitmix64.c) : fast hash
  * Use CRC intrinsics
* Data encoding
  * [base64](https://github.com/ReneNyffenegger/cpp-base64) : Base64 encoding
  * [JSON](https://github.com/nlohmann/json) : JSON for Modern C++
  * [TOML](https://github.com/toml-lang/toml) : Tom's Obvious, Minimal Language.
  * [TOML11](https://github.com/ToruNiina/toml11) : C++11 TOML
  * [pugixml](https://github.com/zeux/pugixml) : Light-weight, simple and fast XML parser for C++ with XPath support
  * [FlatBuffers](https://github.com/google/flatbuffers) : FlatBuffers is a cross platform serialization library architected for maximum memory efficiency.
* Compression
  * [LZ4](https://github.com/lz4/lz4) : LZ4 is lossless compression algorithm, providing compression speed > 500 MB/s per core, scalable with multi-cores CPU.
  * [zStd](https://github.com/facebook/zstd) : Compression for small data
  * [Brotli](https://github.com/google/brotli) : generic-purpose lossless compression algorithm 
  * [crunch](https://github.com/BinomialLLC/crunch) : Advanced DXTc texture compression and transcoding library
  * [FasTC](https://github.com/GammaUNC/FasTC) : A fast texture compressor for various formats
  * [etcpack](https://github.com/wolfpld/etcpak) : The fastest ETC compressor on the planet
  * [zpaq](https://github.com/zpaq/zpaq) : Zpaq compression
  * [7zip](https://github.com/getnamo/7zip-cpp) : 7zip compression
  * [assimp](https://github.com/assimp/assimp) : Official Open Asset Import Library Repository. Loads 40+ 3D file formats into one unified and clean data structure.
* IO
  * [MIO](https://github.com/mandreyel/mio) : memory mapped I/O
  * [ASIO](https://github.com/chriskohlhoff/asio) : Asyncronous I/O
  * [libuv](https://github.com/libuv/libuv) : Asyncronous I/O
  * [physfs](https://github.com/icculus/physfs) : library to provide abstract access to various archives.
* Task systems
  * [Taskflow](https://taskflow.github.io/) : tasking system
  * [Scheduler](https://github.com/Bosma/Scheduler) : Modern C++ Header-Only Scheduling Library. Tasks run in thread pool.
  * [cpptask](https://github.com/Kolkir/cpptask) : Lightweight approach to expressing task stealing and balanced parallelism in a C++ programs.
* Text
  * [ztd.text](https://ztdtext.readthedocs.io/en/latest/index.html) : Text encoding
  * [utfcpp](https://github.com/nemtrif/utfcpp) : UTF-8 encoding
  * [miniutf](https://github.com/dropbox/miniutf) : C++ implementation of several basic Unicode manipulation functions
  * [dragonbox](https://github.com/jk-jeon/dragonbox) : Float to string
  * [fmt](https://github.com/fmtlib/fmt) : string formatting
  * [URL parsing](https://github.com/cpp-netlib/url) : URL
  * [Sole](https://github.com/r-lyeh-archived/sole) : Lightweight C++11 library to generate universally unique identificators (UUID).
  * [rang](https://github.com/agauniyal/rang) : Console color coding
  * [rlutil](https://github.com/tapio/rlutil) : C and C++ utilities for cross-platform console roguelike game creation.
  * [big list of naughty strings](https://github.com/minimaxir/big-list-of-naughty-strings) : The Big List of Naughty Strings is a list of strings which have a high probability of causing issues when used as user-input data.
  * [Unicorn Library](https://github.com/CaptainCrowbar/unicorn-lib) : Unicode library for C++
  * [hunspell](https://github.com/hunspell/hunspell) - The most popular spellchecking library
* Data structures
  * [Colony](https://plflib.org/colony.htm) : High performance data containers
  * [libcds](https://github.com/khizmax/libcds) : Concurrent data structures
  * [bipbuffer](https://github.com/willemt/bipbuffer) : A circular buffer alternative written in C under a BSD license.
  * [C++ B-Tree](https://github.com/diegocaro/cpp-btree) : C++ B-tree is a template library that implements ordered in-memory containers based on a B-tree data structure.
  * [EASTL](https://github.com/electronicarts/EASTL) : EASTL stands for Electronic Arts Standard Template Library. It is a C++ template library of containers, algorithms, and iterators useful for runtime and tool development across multiple platforms.
  * [THST](https://github.com/tuxalin/THST) : Templated hierarchical spatial trees designed for high-peformance.
  * [lru-cache](https://github.com/goldsborough/lru-cache) : A feature complete LRU cache implementation in C++.
* Algorithms
  * [RE2](https://github.com/google/re2) : RE2 is a fast, safe, thread-friendly alternative to backtracking regular expression engines like those used in PCRE, Perl, and Python. It is a C++ library.
  * [Tweeny](https://github.com/mobius3/tweeny) : Tweeny is an inbetweening library designed for the creation of complex animations for games and other beautiful interactive software.
  * [Poisson Disk Generator](https://github.com/corporateshark/poisson-disk-generator) : Poisson disk points generator in C++ in a single file
* Mathematics
  * [SafeInt](https://github.com/IanBullard/SafeInt) : Integer type that checks for overflow
  * [CNL](https://github.com/johnmcfarlane/cnl) : A Compositional Numeric Library for C++, includes fixed point
  * [OpenGL Mathematics](https://github.com/g-truc/glm) : OpenGL Mathematics (GLM) is a header only C++ mathematics library for graphics software based on the OpenGL Shading Language (GLSL) specifications.
* C++ std library stand-ins
  * [range](https://github.com/ericniebler/range-v3) : range
  * [filesystem](https://github.com/gulrak/filesystem) : filesystem
  * [string-view-lite](https://github.com/martinmoene/string-view-lite) : string view
  * [any](https://github.com/thelink2012/any) : any
  * [optional](https://github.com/TartanLlama/optional) : optional
  * [variant](https://github.com/mpark/variant) : variant
  * [abseil](https://github.com/abseil/abseil-cpp) : augments C++ libarary
  * [strong_type](https://github.com/rollbear/strong_type) : string typing
  * [Bitset2](https://github.com/ClaasBontus/bitset2) : std::bitset with constexpr implementations plus additional features.
* Rendering
  * [Vulkan](https://github.com/vinjn/awesome-vulkan) : Vulkan resources
  * [CopperSpice](https://www.copperspice.com/) : LGPL renderer
  * [Skia](https://skia.org/) : 2D renderer
  * [Sharp Filter](https://github.com/IanBullard/Sharp-Bilinear-Shaders) : Sharp filtering for 8-bit type games
  * [ShaderConductor](https://github.com/microsoft/ShaderConductor) :  tool designed for cross-compiling HLSL to other shading languages
  * [Magnum](https://github.com/mosra/magnum) : Lightweight and modular C++11/C++14 graphics middleware for games and data visualization
  * [msdfgen](https://github.com/Chlumsky/msdfgen) : This is a utility for generating signed distance fields from vector shapes and font glyphs, which serve as a texture representation that can be used in real-time graphics to efficiently reproduce said shapes.
  * [ozz](https://github.com/guillaumeblanc/ozz-animation/) : Open source c++ skeletal animation library and toolset
  * [NanoGUI](https://github.com/wjakob/nanogui) : Minimalistic GUI library for OpenGL
  * [Tiny Renderer](https://github.com/ssloy/tinyrenderer/wiki) : Tiny renderer or how OpenGL works: software rendering in 500 lines of code
* Build system
  * [xmake](https://github.com/xmake-io/xmake)
* Encryption
  * [Botan](https://github.com/randombit/botan)
  * [Crypto++](https://github.com/weidai11/cryptopp) : free C++ class library of cryptographic schemes.
* Lua
  * [Sol2](https://github.com/ThePhD/sol2) : Sol is a C++ library binding to Lua. It currently supports all Lua versions 5.1+ (LuaJIT 2.x included).
  * [LuaJIT](https://github.com/LuaJIT/LuaJIT) : Lua JIT compiler
  * [ZeroBrane Studio](https://studio.zerobrane.com/) : Lightweight IDE for your Lua needs
* Python
  * [pybind11](https://github.com/pybind/pybind11) : Seamless operability between C++11 and Python
* Optimization
  * [microprofile](https://github.com/jonasmr/microprofile) : Microprofile is a embeddable profiler in a few files
  * [easy profiler](https://github.com/yse/easy_profiler)
  * [memory tuner](https://github.com/milostosic/MTuner)
  * [rpmalloc](https://github.com/rampantpixels/rpmalloc) : Public domain cross platform lock free thread caching 32-byte aligned memory allocator implemented in C.
  * [Memory Allocators](https://github.com/mtrebi/memory-allocators) : Custom memory allocators in C++ to improve the performance of dynamic memory allocation
  * [libsimdpp](https://github.com/p12tic/libsimdpp) : Portable header-only zero-overhead C++ low level SIMD library.
  * [Buddy Allocator](https://github.com/dbrobins/buddy-allocator) : This is a buddy allocator written in C++ (C++11) for use in an embedded environment.
* Networking
  * [REST client for C++](https://github.com/mrtazz/restclient-cpp) : This is a simple REST client for C++. It wraps libcurl for HTTP requests.
  * [CURL](https://github.com/curl/curl) : CURL
  * [wdt](https://github.com/facebook/wdt) : Warp speed Data Transfer
  * [enet](https://github.com/lsalzman/enet) : ENet reliable UDP networking library
  * [CivitWeb](https://github.com/civetweb/civetweb) : Embedded C/C++ web server
  * [Caddy](https://github.com/mholt/caddy) : Fast, cross-platform HTTP/2 web server with automatic HTTPS
  * [SLikeNet](https://github.com/SLikeSoft/SLikeNet) : Cross-platform network engine written in C++ and specifially designed for games.
* Logging
  * [EasyLogging++](https://github.com/zuhd-org/easyloggingpp) : Single header C++ logging library.
  * [spdlog](https://github.com/gabime/spdlog) : Logging
* Databases
  * [SQlite](https://github.com/mackyle/sqlite) : SQLite
  * [SQLite ORM](https://github.com/fnc12/sqlite_orm) : SQLite ORM light header only library for modern C++.
  * [SQLite](https://github.com/sqlcipher/sqlcipher) : SQLite encryption
* Automated testing
  * [DocTest](https://github.com/onqtam/doctest) : The fastest feature-rich C++11/14/17/20 single-header testing framework for unit tests and TDD
* Pathfinding
  * [Recast & Detour](https://github.com/recastnavigation/recastnavigation) : Navigation-mesh Toolset for Games
* Physics
  * [Bullet](https://github.com/bulletphysics/bullet3) : Real-time collision detection and multi-physics simulation for VR, games, visual effects, robotics, machine learning etc.
* Debugging
  * [debugbreak](https://github.com/scottt/debugbreak) : allows you to put breakpoints in your C/C++ code with a call to debug_break()
  * [debug_assert](https://github.com/foonathan/debug_assert) : Simple, flexible and modular assertion macro.  Over engineered with unneeded features but the most thought out assert system I've seen.
* Misc.
  * [POSH](https://github.com/PhilipLudington/poshlib) : Platform identification library
  * [stb](https://github.com/nothings/stb) : stb single-file public domain libraries for C/C++.
  * [EntityX](https://github.com/alecthomas/entityx) : A fast, type-safe C++ Entity Component System
  * [Argument Aggregator](https://github.com/vietjtnguyen/argagg) :  simple C++11 command line argument parser
  * [FiraCode](https://github.com/tonsky/FiraCode) : Monospaced font with programming ligatures.
  * [Pre-commit Hooks](https://github.com/pocc/pre-commit-hooks) : This is a pre-commit hooks repo that integrates C/C++ linters clang-format, clang-tidy, and oclint.
  * [TinyScheme](http://tinyscheme.sourceforge.net/home.html) : a lightweight Scheme interpreter that implements as large a subset of R5RS as was possible without getting very large and complicated.
