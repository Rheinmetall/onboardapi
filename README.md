# onboardapi

**Licenses**

This project consists of two parts with different licensing terms:

- **Interface Definitions:** Licensed under [Eclipse Public License 2.0](LICENSE-EPL-2.0.txt).
  - Pure interface definitions (`.rmodel` files) describing the data model structure.
- **Runtime Libraries:** Distributed under [EULA-RME-SDK-1.0](EULA-RME-SDK-1.0.txt).
  - Includes the header files and pre-compiled libraries required to transmit and synchronize the data model over the network (available in the [Releases section](https://github.com/Rheinmetall/onboardapi/releases)).

For more details, please see the respective license files.

## Overview

The [onboardapi](https://rheinmetall.github.io/onboardapi-documentation) defines a structured data model and middleware for bidirectional communication between distributed components.

It is designed for high-demand, modular systems such as:

- Sensor networks
- Onboard communication layers
- Robotics systems
- Embedded distributed architectures
- Service-oriented edge platforms

The data model is defined using a custom format `.rmodel` based on the ddkit framework (rmodel-api).

For detailed documentation, please refer to the [official documentation](https://rheinmetall.github.io/onboardapi-documentation).

Available for:

- [C++](https://rheinmetall.github.io/onboardapi-documentation/index.html)
  - [CMake Integration](https://rheinmetall.github.io/onboardapi-documentation/impl_example.html#cmake_integration)
  - [C++ Examples](https://rheinmetall.github.io/onboardapi-documentation/impl_example.html)
- [Python](https://rheinmetall.github.io/onboardapi-documentation/wrappers/python/index.html)
- [C# / .NET](https://rheinmetall.github.io/onboardapi-documentation/wrappers/dotnet/index.html)
- [Java](https://rheinmetall.github.io/onboardapi-documentation/wrappers/java/index.html)

## Contributing

Contributions to the onboardapi interface definitions (`.rmodel`-files) are welcome.

## Commercial Support

For commercial support inquiries, please contact:

opensource.rme@rheinmetall.com
