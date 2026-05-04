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

##  Disclaimer

Your use is governed solely by the terms of the LICENSE file in this repository. Where explicitly indicated in individual source files, a Secondary License may apply; the respective license notices control.

The software is provided “as is,” without warranties or representations of any kind, express or implied, including but not limited to merchantability, fitness for a particular purpose, and non infringement. To the extent permitted by law, liability is disclaimed. Mandatory statutory rights remain unaffected, including liability for intent, gross negligence, and for injury to life, body, or health.

There is no entitlement to support, maintenance, or updates. Community support may be provided on a voluntary, best effort basis via GitHub issues. Any commercial offerings or SLAs, if available, are separate and not part of this project. For commercial support inquiries, please contact: opensource.rme@rheinmetall.com
Please report security vulnerabilities confidentially according to the SECURITY policy at opensource.rme@rheinmetall.com and do not post sensitive or personal information in public issues. For details, see SECURITY.md.

By contributing to this project, you confirm you have the rights necessary to license your contributions and you license them under the EPL 2.0. The rules in CONTRIBUTING.md apply; depending on the project, a DCO sign off or a Contributor License Agreement (CLA) may be required.

Company and product names and logos in this repository are trademarks or trade names of Rheinmetall/onboardapi No trademark or naming rights are granted by the license. Any use requires prior written consent.

Use, distribution, and import of this software may be subject to export control, sanctions, and other applicable laws. You are responsible for complying with all applicable requirements.
In case of any discrepancy, the LICENSE text prevails. This notice is for convenience only and does not modify the license.
