# gradle-native

The home of Gradle's support for natively compiled languages. 

As of 4.1, Gradle includes several plugins for building applications and libraries from C++ and Swift source.

- Issue are tracked in this repo
- This repository also includes some [documentation](docs/README.md) 
- Samples are in the [native-samples](https://github.com/gradle/native-samples) repo.
- The source code for the plugins still lives in the [gradle](https://github.com/gradle/gradle) repo, and will migrate here over time.

## Features

- Compile and link libraries and applications from C++ and Swift source.
- Build C++ for macOS, Linux and Windows.
- Build Swift for macOS and Linux.
- Supports GCC, Clang, Visual Studio, MinGW compilers.
- Fast parallel, incremental compilation.
- Distributed caching of C++ and Swift compilation and linking.
- Transitive dependency management, including support for composite builds and pre-built binaries from a Maven binary repository. Other pre-built binaries are not yet supported
- Tool chain discovery, including discovery of these compilers when running on cygwin.
- Xcode integration, to allow you to generate Xcode workspace and project files from your Gradle build.
- XCTest integration, supported on macOs and Linux.
