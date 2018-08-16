# scalaz-http

[![Join the chat at https://gitter.im/scalaz/scalaz-http](https://badges.gitter.im/scalaz/scalaz-http.svg)](https://gitter.im/scalaz/scalaz-http?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
A purely-functional library for HTTP server and client development.

## Goal
A high-performance, purely-functional library for generating servers, type-safe clients, and rich API documentation from a single type-safe service definition.

## Introduction & Highlights

Scalaz HTTP is a principled functional programming library for building typesafe web applications. The library is focused on composability and scalability. Unlike most other libraries, Scalaz HTTP creates clients and documentation from a single server definition.
* Type-safe client and documentation generation
* Type-safe, purely-functional design that works beautifully with Scalaz
* No macros, runtime reflection, or compiler plug-ins

## Competition

|   |Http4s|Akka-Http|Finch|Rho<sup><a name="footnote">1</a></sup>|Typedapi|
|---|:-:|:-:|:-:|:-:|:-:|
|purely functional|✓|𐄂|𐄂|✓|✓|
|no macros or reflection|✓|𐄂|𐄂|𐄂|𐄂<sup><a name="footnote">2</a></sup>|
|scalaz compatability|𐄂|𐄂|𐄂|𐄂|✓<sup><a name="footnote">3</a></sup>|
|client generation|𐄂|𐄂|𐄂|𐄂|✓|
|documentation generation|𐄂|𐄂|𐄂|𐄂|𐄂|

<sup>[1](#footnote)</sup> Rho is a DSL for creating HTTP endpoints with Http4s</br>
<sup>[2](#footnote)</sup> Typedapi relies on shapeless, therefore uses Macros indirectly</br>
<sup>[3](#footnote)</sup> Typedapi is independent of any HTTP/library implementation

## Background
* [servant](https://haskell-servant.readthedocs.io/en/stable/principles.html) (Haskell)
* [redeyes](https://github.com/redeyes/redeyes) - inspiration


