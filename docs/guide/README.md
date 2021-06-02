# Introduction

The Object Link protocol is a simple protocol to link a local object to a remote object. The protocol is designed to be independent from the transport but was designed with websockets in mind.

For this it can be used from browsers, desktop clients or even smaller embedded devices. Due to support for binary message formats and an efficient protocol structure it is possible to send data very efficient.

The protocol is defined as a clean [protocol specification](../protocol) and as a set of reference implementations of the core protocol.

* [ObjectLink Core Typescript](using-ts)
* [ObjectLink Core C++ 14](using-cpp)
* [ObjectLink Core Python](using-py)

All reference implementation share similar tests and features and come with examples for using it with different transport libraries.