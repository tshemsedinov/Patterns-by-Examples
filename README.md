# 🧩 JavaScript Patterns by Examples

> Patterns for JavaScript, Node.js, and Async programming by platform native examples

| Pattern                 | Pure JavaScript      | Web API example         | Node.js example    | Domain example    |
| ----------------------- | -------------------- | ----------------------- | ------------------ | ----------------- |
| 🏭 Creational           | | | | |
| Abstract factory        | | | | |
| Builder                 | | | | |
| Factory method          | | `document.createElement`  | `crypto.createHash` | |
| Prototype               | | | | |
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
