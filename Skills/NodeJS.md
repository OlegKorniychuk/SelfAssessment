## Node.js and backend

- Internals and concepts
  - Strong and weak sides of node.js: 👂 heard
  - Stateful and stateless servers: 👂 heard
  - Nonblocking I/O and slocking code: 👂 heard
  - Event loop: phases: 👂 heard
  - Event loop: microtasks and macrotasks: 👂 heard
  - Garbage collection: 👂 heard
  - Node.js LTS schedule: 👂 heard
  - I/O-bound, CPU-bound, memory-bound tasks: 👂 heard
  - Interactive applications (close to real-time): 👂 heard
- Modularity, layers and dependencies
  - CommonJS modules: 👂 heard
  - ECMAScript modules: 👂 heard
  - node:module: 👂 heard
  - Caching in CJS and ESM: 👂 heard
  - Modules as singletons: 👂 heard
  - Contexts and scripts node:vm: 👂 heard
  - Dependencies: npm, node_modules: 🖐️ used
  - Dependencies: package.json and package lock: 🖐️ used
  - Module-based permissions model: 👂 heard
  - Isolation with modularity: 👂 heard
  - Dependency injection: 👂 heard
  - DI containers: 👂 heard
  - Coupling and cohesion: 👂 heard
  - Framework agnostic approach: 👂 heard
- Environment
  - Command line arguments: 🎓 known
  - Node.js CLI: 🎓 known
  - Process-based permissions: 👂 heard
  - Graceful shutdown: 👂 heard
  - Clustering: 👂 heard
  - Watch filesystem changes with --watch: 👂 heard
- Internal API
  - Streams API: 👂 heard
  - Web Streams API: 👂 heard
  - Crypto API: 👂 heard
  - Password hashing with node:crypto.scrypt: 👂 heard
  - Web Crypto API: 👂 heard
  - File system API: sync and async: 🎓 known
  - Copy folder recursively: 👂 heard
  - Worker threads: 👂 heard
  - Performance hooks: 👂 heard
  - Native fetch and nodejs/undici: 👂 heard
  - node:async_hooks: 👂 heard
  - AsyncLocalStorage: 👂 heard
  - AsyncResource: 👂 heard
  - Deprecated domain API: 👂 heard
  - Node.js single executable: 👂 heard
  - Stream back pressure: 👂 heard
  - SharedArrayBuffer: 👂 heard
  - node:worker_threads: 👂 heard
  - node:child_process: 👂 heard
  - MessageChannel, MessagePort: 👂 heard
  - BroadcastChannel: 👂 heard
  - Generating crypto random UUID: 👂 heard
  - node:url vs new URL: 👂 heard
  - node:assert: 👂 heard
  - Internationalization: 👂 heard
  - Blob, File, Buffer, node:buffer: 👂 heard
  - Module node:zlib: 👂 heard
- Application structure and architecture
  - Isolation between layer: 👂 heard
  - Multilayer approach: 👂 heard
  - Separation of concerns: 👂 heard
  - Inversion of control: 👂 heard
  - Dependency injection: 👂 heard
  - GRASP: 👂 heard
  - SOLID: 👂 heard
  - GoF patterns: 👂 heard
  - Distributed systems: 👂 heard
  - Highload applications: 👂 heard
  - Clean architecture: 👂 heard
  - DDD: 👂 heard
  - Message Queue: 👂 heard
  - CQS: 👂 heard
  - CQRS: 👂 heard
  - Event sourcing: 👂 heard
  - Load balancing: 🖐️ used
  - Serverless clouds: 🎓 known
  - FaaS clouds: 🎓 known
  - Fat controller: 👂 heard
  - GoF for Node.js: 👂 heard
  - Leaking abstractions: 👂 heard
- Network
  - IP sticky sessions: 👂 heard
  - Endpoint throttling: 👂 heard
  - HTTP(S): 🖐️ used
  - TCP/SSL: 🖐️ used
  - UDP: 🖐️ used
  - TLS: 🖐️ used
  - Websocket: 🖐️ used
  - SSE: 👂 heard
  - HTTP/3 (QUIC): 👂 heard
  - Long polling: 👂 heard
  - REST: 👂 heard
  - RPC: 👂 heard
  - Routing: 🖐️ used
  - DoS: 🎓 known
  - DDoS: 🎓 known
  - XSS: 👂 heard
  - Path traversal: 👂 heard
  - CSRF: 👂 heard
  - DNS: 🖐️ used
  - Fetch API: 👂 heard
  - IncomingMessage: 👂 heard
  - SQL injection: 🙋 explained
  - noDelay: 👂 heard
  - keep-alive: 👂 heard
  - ALPN: 👂 heard
  - SNI callback: 👂 heard
  - SSL certificates: 🖐️ used
  - Protocol agnostic approach: 👂 heard
- Technique and tools
  - Native test runner: 👂 heard
  - Logging: 👂 heard
  - Application configuring: 👂 heard
  - Testing: 🎓 known
  - CI/CD: 🎓 known
  - Readable: 👂 heard
  - Writable: 👂 heard
  - Transform: 👂 heard
  - back pressure: 👂 heard
  - Buffer: 🎓 known
  - Console: 🎓 known
  - Inspector: 👂 heard
  - Reliability: 👂 heard
  - Quality: 👂 heard
  - Availability: 👂 heard
  - Flexibility: 👂 heard
- Data access
  - Data access layer: 👂 heard
  - Repository: 🖐️ used
  - Active record: 👂 heard
  - Query builder: 👂 heard
  - Object-Relational Mapping: 👂 heard
- Error handling and debugging
  - Error: 🎓 known
  - error.cause: 👂 heard
  - error.code: 👂 heard
  - error.message: 🖐️ used
  - error.stack: 👂 heard
  - How to avoid mixins: 👂 heard
  - Error.captureStackTrace: 👂 heard
  - Uncaught exceptions: 👂 heard
  - Heap dump: 👂 heard
  - Debugging tools: 👂 heard
  - Flame graph: 👂 heard
  - Memory leaks: 🎓 known
  - Resource leaks: 🎓 known
  - Data race: 👂 heard
- Integrations and bindings
  - Native addons: 👂 heard
  - C and C++ addons: 👂 heard
  - Rust addons
  - Zig addons
  - NAN (Native Abstractions for Node.js)
  - Node-API (formerly N-API)
  - NAPI C and C++
  - NAPI Rust
  - NAPI Zig
  - Webassembly WAT
  - Webassembly C and C++
  - Webassembly Rust
  - Webassembly Zig
  - Webassembly AssemblyScript
  - Shared memory
  - SharedArrayBuffer
  - V8 binary serialization
