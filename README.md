# Definition of a library for high-level synthesis of extensions for security

Fully synthesizable security extension library for AES side-channel masking. Documentation available. 

### Abstract

High-level synthesis has become a key component in hardware acceleration of applications since
it can significantly reduce complexity of hardware component design by raising the abstraction to
programming languages like C and C++. Thanks to HLS, non-hardware engineers can quickly create
prototype while hardware engineers can build hardware design quicker for emerging fields such as
artificial intelligence and edge computing. In the recent years, security and privacy concern have
become more relevant especially in data driven applications. In this work, we investigate how to
abstract security properties using HLS to integrate them in accelerator design. Previous work has
focused on algorithm-level code obfuscation[1]. In this one, we focus on cryptography algorithms
masking, showing how software level extension can be used to secure hardware solutions while
keeping implementation details transparent to the designer.

