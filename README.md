Hello :wave:

My name is Colin Ihrig, and I am a software engineer based out of Pittsburgh, PA in the United States. I have worked for small startups with a handful of employees as well as large enterprises such as Samsung, Walmart, and Amazon.

## Past open source projects

I have been developing open source software since 2013. I have created or contributed to many [projects](https://github.com/cjihrig?tab=repositories) since then. Here are some of the highlights:

### Node.js

[Node.js](https://nodejs.org/) is a popular cross-platform JavaScript runtime. I began contributing to [Node.js](https://github.com/nodejs/node) in 2014, and joined its [Technical Steering Committee](https://github.com/nodejs/tsc) in early 2015. Some of my past contributions include:

- Initial author of Node's [test runner](https://nodejs.org/api/test.html). This includes the `node:test` core module, the CLI runner, mocking, snapshot testing, and code coverage.
- Initial author of Node's [SQLite](https://nodejs.org/api/sqlite.html) integration.
- Initial author of Node's [WebAssembly System Interface](https://nodejs.org/api/wasi.html) (WASI) integration.
- Significant contributions to the [`child_process`](https://nodejs.org/api/child_process.html), [`cluster`](https://nodejs.org/api/cluster.html), [`dns`](https://nodejs.org/api/dns.html), [`fs`](https://nodejs.org/api/fs.html), [`os`](https://nodejs.org/api/os.html), and [`report`](https://nodejs.org/api/report.html) modules.
- Initial author of the [`lts`](https://www.npmjs.com/package/lts) module used to generate the Node.js long term support (LTS) schedule [graphic](https://github.com/nodejs/Release/blob/main/schedule.svg).
- Maintaining Node's [postmortem debugging](https://cjihrig.com/postmortem_debugging) metadata, including sending appropriate [patches to the V8 project](https://github.com/v8/v8/commits?author=cjihrig). I also updated the [llnode](https://github.com/nodejs/llnode) tool to support [V8's TurboFan optimizing compiler](https://v8.dev/docs/turbofan).
- Past member of the [Release working group](https://github.com/nodejs/release), [Diagnostics working group](https://github.com/nodejs/diagnostics), and [Security working group](https://github.com/nodejs/security-wg).

### libuv

[libuv](https://libuv.org/) is a C library that provides cross-platform asynchronous I/O and an event loop. It has been used by projects such as Node.js, [BIND](https://bind.isc.org/), [CMake](https://cmake.org/), the [Julia programming language](https://julialang.org/), [Neovim](https://neovim.io/), and [many more](https://github.com/libuv/libuv/blob/v1.x/LINKS.md).

I have been a [libuv maintainer](https://github.com/libuv/libuv/blob/v1.x/MAINTAINERS.md) since 2016 and handled many of its releases. I have also worked on APIs for native file copying, streaming directory iteration, retrieving storage volume information, working with environment variables, and retrieving user information, to name a few. I have also [spoken about libuv](https://www.youtube.com/watch?v=_c51fcXRLGw) at a number of conferences and meetups.

### uvwasi

I created [uvwasi](https://github.com/nodejs/uvwasi), one of the first WebAssembly System Interface implementations. uvwasi was built on top of libuv to maximize platform support. It was donated to the Node.js project, and has been integrated into the following projects:

- Node.js
- The [wasm3](https://github.com/wasm3/wasm3) WebAssembly runtime.
- [WABT: The WebAssembly Binary Toolkit](https://github.com/WebAssembly/wabt).
- The [Grain](https://grain-lang.org/) programming language.
- The [fizzy](https://github.com/wasmx/fizzy) WebAssembly interpreter.
- The [WebAssembly Micro Runtime](https://github.com/bytecodealliance/wasm-micro-runtime) (WAMR).

### gRPC

gRPC is a cross-platform, cross-language Remote Procedure Call (RPC) framework. It was originally developed at Google, and is now a project of the [Cloud Native Computing Foundation](https://www.cncf.io/projects/grpc/) (CNCF).

I created [grpc-server-js](https://github.com/cjihrig/grpc-server-js), the first pure JavaScript gRPC server implementation that I am aware of. I also rewrote the server in TypeScript and upstreamed it to the official [gRPC](https://github.com/grpc/grpc-node) project. I have also [spoken about gRPC](https://www.youtube.com/watch?v=fl9AZieRUaw) at several conferences, including gRPConf.

### hapi

[hapi.js](https://hapi.dev/) is a Node.js web framework that originally gained fame at Walmart for successfully [handling Black Friday traffic](https://www.infoworld.com/article/2608897/walmart-s-investment-in-open-source-isn-t-cheap.html).

I have been involved in the hapi ecosystem in various capacities as a contributor, maintainer, and [Technical Steering Committee](https://github.com/hapijs/hapi#technical-steering-committee-tsc-members) member since 2014.
