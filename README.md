# fxproxytoolkit
Proxy Login handling using proxy-vole

This is just a decoupling of proxy-vole dependencies as they are volatile. It may seem silly to have a library for just one class, which is a JavaFX dialog wrapper and interrupt driven proxy handler, but it is way more flexible for end users choosing which libraries to download, and prevents unnecessary propagation of brittle and volatile proxy-vole dependencies across other libraries that aren't focused on proxy support.
