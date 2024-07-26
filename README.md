# 🧩 JavaScript Patterns by Examples

> Patterns for JavaScript, Node.js, and Async programming by platform native examples

| Pattern                 | Pure JavaScript  | Web API  | Node.js  | Domain  |
| ----------------------- | ---------------- | -------- | -------- | ------- |
| 🏭 Creational           | | | | |
| Abstract factory        | | | | |
| Builder                 | Chaining | | stream.pipe.on | Query builder |
| Factory method          | | `document.createElement`  | `crypto.createHash` | |
| Prototype               | Class with private fields and `clone` method, `JSON.stringify/parse`, `structuredClone`, `Object.assign` + `Object.setPrototypeOf` | | `node:v8`, `serialize`, `deserialize` | |
| Singleton               | IIFE, modules, `global`, `window` | esm/cjs modules | `module.exports` | |
| 🤝 Structural           | | | | |
| Adapter                 | promisify / callbackify | `fetch` polyfill around `XMLHttpRequest` | `util.promisify` | |
| Bridge                  | | | | |
| Composite               | | | | |
| Decorator               | Decorator syntax, boxing, wrappers | | | |
| Facade                  |  | `document.querySelector` | `http2.createSecureServer` | |
| Flyweight               | Object pools | | Connection pools | |
| Proxy                   | Built-in `Proxy` | | `node:vm.createContext` | |
| ⚡ Behavioral           | | | | |
| Chain of responsibility | | | `middleware` | |
| Command                 | | | | |
| Interpreter             | | | | |
| Iterator                | `Iterator`, `AsyncIterator` | Streams API | `node:stream` | |
| Mediator                | | | | |
| Memento                 | | | | |
| Observer                | callbacks, events | `EventTarget` | `EventEmitter` | |
| State                   | | | | |
| Strategy                | `Map<key: Function>` | | Routing (end-point collections) | |
| Template method         | | | | |
| Visitor                 | | | | |
